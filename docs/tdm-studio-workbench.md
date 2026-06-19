---
title: TDM Studio Workbench
parent: What Tools and Resources are Available for me to Access?
grand_parent: "ProQuest TDM Studio"
layout: "home"
created_date:  "2021-09-23"
staff:
 - name: Kelly Schultz
   link: https://library.utoronto.ca/staff/kelly-schultz
 - name: Neil Aitken
   link: https://library.utoronto.ca/staff/neil-aitken
maintainer:
 - name: Neil Aitken
   link: https://library.utoronto.ca/staff/neil-aitken
nav_order: 2.2
---
## TDM Studio Workbench
* [Creating a Dataset](#creating-a-dataset)            
* [Downloading metadata extracts in Workbench](#downloading-metadata-extracts-in-workbench)
* [Working with your Data in Workbench](#working-with-your-data-in-workbench)
* [Collaborating in Workbench](#collaborating-in-workbench)
* [Exporting Results](#exporting-results)

Create an account with ProQuest. *Note: in order to gain access to licensed UofT collections you must use your UTORONTO email address in the form (@mail.utoronto.ca, @utoronto.ca, @rotman.utoronto.ca, etc.)* This account will provide you with access to both Visualizations and Workbench.

Once you have created your account and successfully logged in, select *Workbench Dashboard* from the main login screen. 

### Creating a Dataset
In Workbench, you can create a maximum of 10 datasets of up to 2,000,000 documents. You can begin your search by selecting either individual publication titles or complete databases, and then running a search on content in those titles/databases (for example, <a href="https://about.proquest.com/en/products-services/globalnewsstream/">ProQuest Global Newsstream</a>).

<img src="{{ '/assets/images/SC10.jpg' | relative_url }}" data-entity-uuid="3bea5e2e-d852-46ee-ad76-2b38c1691c79" data-entity-type="file" alt="Screenshot showing a list of documents that match search criteria" width="1301" height="611" vspace="20">

Once you're happy with your search results, select "Review Content", where you will be asked to provide your dataset a name and optional description. Then select "Create Dataset". Your dataset will now be visible in your TDM Studio Workbench Dashboard with the status of “In Process". Once your dataset is complete, it will show a status as "Completed".

<img src="{{ '/assets/images/SC11.jpg' | relative_url }}" data-entity-uuid="22132af5-f349-47be-b2c5-a0d9fbf83a93" data-entity-type="file" alt="Image of screen reviewing and naming the dataset" width="1302" height="1215" vspace="20">

Note that TDM Studio processes 100,000 of documents an hour. This processing involves gathering the data on ProQuest's servers, and then transferring this onto Amazon Web Service (AWS) servers, which power the Workbench Virtual Machines. Due to this, processing may take several hours. Note that once a dataset is "Completed" it can be deleted from your Dashboard, as it has already been transferred into the Virtual Machine environment.

This <a href="https://proquest.libguides.com/tdmstudio/dataset">ProQuest Guide </a>provides more information on creating a dataset.

***A note on corpus:*** TDM Studio Visualizations includes the majority of UofT's licensed content, over 300 databases. This represents both recent and more deeply historical scholarly publications (books and journals), primary source texts in the humanities, business, public policy, public health and other scientific literature, as well as extensive recent and older newspaper articles from across the globe. Note that a small number of databases are not currently available for TDM in Workbench due to technical or licensing restrictions. For a complete list of databases currently accessible via Workbench, please contact the <a href="mailto:mdl@library.utoronto.ca">Map &amp; Data Library.</a>

### Downloading Metadata Extracts in Workbench
As of August 2023, it is now possible to extract basic citation metadata, or more complete (extended) metadata for your datasets in Workbench. This is done via the Workbench Dashboard, and does not require you to open the Workbench Virtual Machine. This option can be found by selecting the download arrow immediately to the right of your dataset information. Metadata will download as a single .csv file.

<img src="{{ '/assets/images/download.png' | relative_url }}" data-entity-type="file" alt="Image of screen indicating metadata extract is ready for download" width="736" height="343" vspace="20">

Please note that this option will not appear for any datasets created prior to August 2023. To extract metadata for those datasets, they will need to be recreated.

### Working with your Data in Workbench
Once your dataset is "Completed", you can work with it in the Workbench Virtual Machine (VM). If this is the first time you've used the VM, or you've been offline for several days, you'll need to restart your virtual machine by toggling it "on" from the slider on the top right corner of the dashboard. After the button is switched to 'On', click on 'Open Jupyter Notebook' to launch the Virtual Machine.

<img src="{{ '/assets/images/SC12.jpg' | relative_url }}" data-entity-uuid="be0daddf-4056-4881-81f3-992fcbfcb6da" data-entity-type="file" alt="Screenshot showing toggle for turning on Virtual Machine environment in the Workbench" width="1263" height="612" vspace="20">

The VM provides 4 processors, 156GB RAM and 100 GB of storage. This can be upgraded on request by contacting ProQuest's <a href="mailto:email.technicalsupport@proquest.com ">technical support.</a>

Each VM comes pre-loaded with Jupyter Notebooks, and several pre-configured environments both in Python and R that include libraries and modules commonly using in text and data mining. Additional packages can be installed within the VM using <a href="https://docs.conda.io/en/latest/">conda</a>. Example Python scripts are available in Jupyter under the **ProQuest TDM Studio Samples** folder.

<img src="{{ '/assets/images/SC14_3.jpg' | relative_url }}" data-entity-uuid="d6706ec5-f9ec-448a-b89d-c9e7c6b8e8dc" data-entity-type="file" alt="Screenshot of folder containing ProQuest TDM Studio Samples" width="1165" height="495">

Example R Scripts can be found here: **Getting Started R &gt; [last update date] &gt; TDM Studio Samples**

<img src="{{ '/assets/images/SC14.jpg' | relative_url }}" data-entity-uuid="70182fd8-12ac-4ed2-956f-81a1c8aeb72d" data-entity-type="file" alt="Image showing folder containing ProQuest TDM Studio R Samples" width="1309" height="668" vspace="20">

Importing outside scripts and data to work with inside of the VM is also possible. More information is provided in this short <a href="https://pq-edu.com/Camtasia%20Product%20Training%20Videos/TDM%20Studio/Uploading%20Content%20to%20TDM%20Studio/Uploading%20Content%20to%20TDM%20Studio_player.html">ProQuest video</a>, and in the <strong>Uploading Instructions.ipynb&nbsp;</strong>file in the<strong> ProQuest TDM Studio Manual </strong>folder of the VM Jupyter Notebook.

<img src="{{ '/assets/images/SC15.jpg' | relative_url }}" data-entity-uuid="3615dbfd-1ee2-4ec5-a252-f6024d021e82" data-entity-type="file" alt="Image showing web folder containing ProQuest TDM Studio Manuals" width="1302" height="632" vspace="20">

It is also possible to work with the raw XML files in the VM by opening a Terminal window in Jupyter. These XML files can be found in the **data** folder of Jupyter, organized under your chosen dataset name.

<img src="{{ '/assets/images/SC16.jpg' | relative_url }}" data-entity-uuid="e7e3195c-073a-49cb-aece-1470ef74e134" data-entity-type="file" alt="Screenshot showing how to open a Terminal player in Jupyter" width="1160" height="435">

**Note:** do not click on your dataset folder, as this action will often crash the VM as it tries to open thousands of individual files!

### Collaborating in Workbench
TDM Studio Workbench allows you to add up to 4 additional users to your Workbench, using their institutional emails. Accounts can be linked on request by emailing their technical support:&nbsp;<a href="mailto:email.technicalsupport@proquest.com" aria-expanded="false" aria-haspopup="menu" data-remove-tab-index="true" data-sk="tooltip_parent" data-stringify-link="mailto:email.technicalsupport@proquest.com" delay="150" rel="noopener noreferrer" tabindex="-1" target="_blank">email.technicalsupport@proquest.com</a>.&nbsp;

### Exporting Results
Derived data or results of your analysis can be exported by running the **Export Instructions.ipynb** script in the **ProQuest TDM Studio Manual** folder of the VM Jupyter Notebook. You will receive a download link to retrieve your results (download links for all export requests will be sent to all users on that account).

Exports are limited to 15MB per week. Note that larger exports are possible on request&nbsp;by contacting ProQuest's <a href="mailto:email.technicalsupport@proquest.com ">technical support.</a>

<img src="{{ '/assets/images/SC17.jpg' | relative_url }}" data-entity-uuid="7110226a-c06e-4a92-9ef3-131ebbef6dcb" data-entity-type="file" alt="Screenshot showing how to export files from TDM Studio" width="1164" height="656">

 **Technique:** [Text and Data Mining](https://mdlutoronto.github.io/tutorials-search/?technique=Text+and+Data+Mining) \| **Tools:** [ProQuest TDM Studio](https://mdlutoronto.github.io/tutorials-search/?tool=ProQuest+TDM+Studio)