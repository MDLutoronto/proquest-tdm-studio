---
title: "ProQuest TDM Studio"
layout: "home"
description:  "An overview of ProQuest TDM Studio and tutorial covering its main features"
permalink: "/"
created_date:  "2021-09-23"
has_children: False  # Set to True if the page has sub-pages.
---

# ProQuest TDM Studio

* [What is Proquest TDM Studio?](#what-is-proquest-tdm-studio)
* [What is Text Analysis?](#what-is-text-analysis)
* [What Tools and Resources are Available for me to Access?](#what-tools-and-resources-are-available-for-me-to-access)
     * [TDM Studio Visualization](#tdm-studio-visualization)     
       * [Logging in](#logging-in)
       * [Creating a Project and Running Algorithms](#creating-a-project-and-running-algorithms)
     * [TDM Studio Workbench](#tdm-studio-workbench)
       * [Creating a Dataset](#creating-a-dataset)            
       * [Downloading metadata extracts in Workbench](#downloading-metadata-extracts-in-workbench)
       * [Working with your Data in Workbench](#working-with-your-data-in-workbench)
       * [Collaborating in Workbench](#collaborating-in-workbench)
       * [Exporting Results](#exporting-results)
* [FAQs](#faq)
* [Additional Resources](#additional-resources) 

## What is ProQuest TDM Studio?
ProQuest TDM Studio is a web platform for running text analyses on thousands of ProQuest datasets, including, but not limited to, databases such as ProQuest Dissertations & Theses and the New York Times. TDM Studio has two components: 

* Visualizations, which is an entirely browser-based, point-and-click interface with data visualizations
* Workbench, for researchers and their teams coding with R or Python in Jupyter notebooks.
  
If you wish to have access to both components, you must request them separately.

## What is Text Analysis?
Text Analysis, using the tools available through the HTRC, allows researchers to quickly analyze a large number of documents (more than a human could read, and faster). Some questions that can be answered using text analysis would be:

* What are these texts about?
* How are these texts connected?
* What emotions (or affects) are found within these texts?
* What names are used in these texts?
* Which of these texts are most similar?

These questions can be addressed using techniques such as finding word frequencies, performing topic modelling, or performing named entity recognition

## What Tools and Resources are Available for me to Access?
ProQuest TDM Studio provides several ways of accessing and analyzing texts. While some require knowledge of the Python or R programming languages, others are point and click. Please note that the options below may include different subsets of the corpus, as well as different levels of access (metadata vs. full text) and data types.

## TDM Studio Visualizations

### Logging in
<a href="https://tdmstudio.proquest.com/createaccount">Create an account</a> with ProQuest. *Note: in order to gain access to licensed UofT collections you must use your UTORONTO email address in the form (@mail.utoronto.ca, @utoronto.ca, @rotman.utoronto.ca, etc.)* This account will provide you with access to both Visualizations and Workbench.

<img src="{{ '/assets/images/SC1.jpg' | relative_url }}" data-entity-uuid="af474e7c-843b-4969-8436-76530027ee7b" data-entity-type="file" alt="Image showing the process for creating an account on ProQuest TDM Studio" width="711" height="725" vspace="20">

Once you have created your account and successfully logged in, select *Visualizations* Dashboard from the main login screen.

<img src="{{ '/assets/images/SC2.jpg' | relative_url }}" data-entity-uuid="2f369047-2a8c-40b3-b340-83b966186f98" data-entity-type="file" alt="Image showing main screen with Workbench and Visualizations dashboards side-by-side" width="1920" height="939" vspace="20">

### Creating a Project and Running Algorithms

Once logged in, you can build collections of texts called "projects" that can then be analyzed in your browser using TDM Studio visualizations. Visualizations allows you to manage as many as five simultaneous research projects of 10,000 documents each.

<img src="{{ '/assets/images/SC3.jpg' | relative_url' }}" data-entity-uuid="916bddad-09ad-4e4c-8db4-47e1fbf1eb9d" data-entity-type="file" alt="TDM Studio project page displaying project information and design features in a structured format." width="1241" height="791" vspace="20">

Before searching Proquest's databases, you'll need to select which pre-built algorithms you'd like to apply to your search results. Visualizations currently supports *Topic Modelling*, *Geographic Analysis*, and *Sentiment Analysis*, although there are plans to add additional algorithms based on demand. Note that it is currently not possible to customize these algorithms.

<img src="{{ '/assets/images/SC4.jpg' | relative_url }}" data-entity-uuid="6dd0e099-615a-426c-88fc-059614813e57" data-entity-type="file" alt="Screenshot showing a data visualization interface with buttons for Geographic Analysis, Topic Modeling, and Sentiment Analysis" width="1457" height="1103">

Once you've selected your algorithms, search and refined your search results to under 10,000 records, then select "Review Content".

<img src="{{ '/assets/images/SC5.jpg' | relative_url }}" data-entity-uuid="338454c0-e5a3-4605-8451-d52fdacdbd73" data-entity-type="file" alt="Image showing webpage where datasources can be selected and searched" width="1881" height="1205" vspace="20">

You will be asked to provide your dataset a name, then click "Create project".

<img src="{{ '/assets/images/SC6.jpg' | relative_url }}" data-entity-uuid="824cf766-6d83-40a6-bf5d-a222190b3413" data-entity-type="file" alt="Screenshot of the Create New Project page showing project summary details" width="1865" height="843" vspace="20">

Your dataset will now be visible in your TDM Studio Visualizations Dashboard. Note that the algorithms you selected will be greyed-out initially, until processing is complete. Processing may take several hours depending on the size of your dataset and the analyses selected.

<img src="{{ '/assets/images/SC7.jpg' | relative_url }}" data-entity-uuid="8b1e0df8-9c1f-494b-a2d5-65a7aae6e238" data-entity-type="file" alt="Image showing updated Your Projects list and providing buttons for different visualizations" width="1521" height="931" vspace="20">

Once processing is complete, you will be able to select and explore your visualizations. The underlying data can be downloaded as zipped CSV files or GeoJSON (geographic analysis only).

<img src="{{ '/assets/images/SC8.jpg' | relative_url }}" data-entity-uuid="e333ce72-3331-4a1c-a215-e736697c4bef" data-entity-type="file" alt="A world map displaying blue dots of different sizes" width="1611" height="1109">

All zips includes CSV of basic metadata for each record (such as ID, Title, Publication, Date). While there is not currently an option to download visualizations as images, they can be manually saved as screenshots.

Read this short <a href="https://proquest.libguides.com/tdmstudio/visualizationproject">ProQuest guide</a> for more information on creating a project.

***A note on corpus:*** As of January 2025, TDM Studio Visualizations now includes the vast majority of UofT's licensed content. Previously, only a small subset of content had been available so this may impact datasets created prior to 2025. For a complete list of databases currently accessible via Visualizations, please contact the <a href="mailto:mdl@library.utoronto.ca">Map &amp; Data Library.</a>

### TDM Studio Workbench

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

#### Downloading Metadata Extracts in Workbench
As of August 2023, it is now possible to extract basic citation metadata, or more complete (extended) metadata for your datasets in Workbench. This is done via the Workbench Dashboard, and does not require you to open the Workbench Virtual Machine. This option can be found by selecting the download arrow immediately to the right of your dataset information. Metadata will download as a single .csv file.

<img src="{{ '/assets/images/download.png' | relative_url }}" data-entity-type="file" alt="Image of screen indicating metadata extract is ready for download" width="736" height="343" vspace="20">

Please note that this option will not appear for any datasets created prior to August 2023. To extract metadata for those datasets, they will need to be recreated.

#### Working with your Data in Workbench
Once your dataset is "Completed", you can work with it in the Workbench Virtual Machine (VM). If this is the first time you've used the VM, or you've been offline for several days, you'll need to restart your virtual machine by toggling it "on" from the slider on the top right corner of the dashboard. After the button is switched to 'On', click on 'Open Jupyter Notebook' to launch the Virtual Machine.

<img src="{{ '/assets/images/SC12.jpg' | relative_url }}" data-entity-uuid="be0daddf-4056-4881-81f3-992fcbfcb6da" data-entity-type="file" alt="Screenshot showing toggle for turning on Virtual Machine environment in the Workbench" width="1263" height="612" vspace="20">

The VM provides 4 processors, 156GB RAM and 100 GB of storage. This can be upgraded on request by contacting ProQuest's <a href="mailto:email.technicalsupport@proquest.com ">technical support.</a>

Each VM comes pre-loaded with Jupyter Notebooks, and several pre-configured environments both in Python and R that include libraries and modules commonly using in text and data mining. Additional packages can be installed within the VM using <a href="https://docs.conda.io/en/latest/">conda</a>. Example Python scripts are available in Jupyter under the **ProQuest TDM Studio Samples** folder.

<img src="{{ '/assets/images/SC14_3.jpg' | relative_url }}" data-entity-uuid="d6706ec5-f9ec-448a-b89d-c9e7c6b8e8dc" data-entity-type="file" alt="Screenshot of folder containing ProQuest TDM Studio Samples" width="1165" height="495">

Example R Scripts can be found here: **Getting Started R &gt; [last update date] &gt; TDM Studio Samples**

<img src="{{ '/assets/images/SC14.jpg' | relative_url }}" data-entity-uuid="70182fd8-12ac-4ed2-956f-81a1c8aeb72d" data-entity-type="file" alt="Image showing folder containing ProQuest TDM Studio R Samples" width="1309" height="668" vspace="20">

Importing outside scripts and data to work with inside of the VM is also possible. More information is provided in this short <a href="https://pq-edu.com/Camtasia%20Product%20Training%20Videos/TDM%20Studio/Uploading%20Content%20to%20TDM%20Studio/Uploading%20Content%20to%20TDM%20Studio_player.html">ProQuest video</a>, and in the <strong>Uploading Instructions.ipynb&nbsp;</strong>file in the<strong>ProQuest TDM Studio Manual </strong>folder of the VM Jupyter Notebook.

<img src="{{ '/assets/images/SC15.jpg' | relative_url }}" data-entity-uuid="3615dbfd-1ee2-4ec5-a252-f6024d021e82" data-entity-type="file" alt="Image showing web folder containing ProQuest TDM Studio Manuals" width="1302" height="632" vspace="20">

It is also possible to work with the raw XML files in the VM by opening a Terminal window in Jupyter. These XML files can be found in the **data** folder of Jupyter, organized under your chosen dataset name.

<img src="{{ '/assets/images/SC16.jpg' | relative_url }}" data-entity-uuid="e7e3195c-073a-49cb-aece-1470ef74e134" data-entity-type="file" alt="Screenshot showing how to open a Terminal player in Jupyter" width="1160" height="435">

```Note: do not click on your dataset folder, as this action will often crash the VM as it tries to open thousands of individual files!```

#### Collaborating in Workbench
TDM Studio Workbench allows you to add up to 4 additional users to your Workbench, using their institutional emails. Accounts can be linked on request by emailing their technical support:&nbsp;<a href="mailto:email.technicalsupport@proquest.com" aria-expanded="false" aria-haspopup="menu" data-remove-tab-index="true" data-sk="tooltip_parent" data-stringify-link="mailto:email.technicalsupport@proquest.com" delay="150" rel="noopener noreferrer" tabindex="-1" target="_blank">email.technicalsupport@proquest.com</a>.&nbsp;

#### Exporting Results
Derived data or results of your analysis can be exported by running the **Export Instructions.ipynb** script in the **ProQuest TDM Studio Manual** folder of the VM Jupyter Notebook. You will receive a download link to retrieve your results (download links for all export requests will be sent to all users on that account).

Exports are limited to 15MB per week. Note that larger exports are possible on request&nbsp;by contacting ProQuest's <a href="mailto:email.technicalsupport@proquest.com ">technical support.</a>

<img src="{{ '/assets/images/SC17.jpg' | relative_url }}" data-entity-uuid="7110226a-c06e-4a92-9ef3-131ebbef6dcb" data-entity-type="file" alt="Screenshot showing how to export files from TDM Studio" width="1164" height="656">

## FAQ

### How do I cite a dataset and tool?
ProQuest is currently developing documentation around citation styles for datasets, as well as for Visualization Algorithms and Workbench tools. In the interim, tools can be cited with reference to the Algorithm used or to Workbench. For example:

```“ProQuest TDM Studio Visualization.” Geographic Visualization. Accessed February 16, 2022. <a href="https://analytics.hathitrust.org/algorithms">https://tdmstudio.proquest.com/</a>```

## Additional Resources
* See a&nbsp;<a href="https://play.library.utoronto.ca/watch/dcee158db446cb9a2dc4168eccf30f77?t=1830.08" tabindex="-1">demo of TDM Studio - Visualizations</a>
* See a&nbsp;<a href="https://play.library.utoronto.ca/watch/dcee158db446cb9a2dc4168eccf30f77?t=2277.29" tabindex="-1">demo of TDM Studio - Workbench</a>

### Official Guides
* <a href="https://proquest.libguides.com/tdmstudio/home">Proquest's Official User Guide</a>
* <a href="https://share.vidyard.com/watch/GdyeQtdPF4uZMtmyVvJtoc">TDM Studio Workbench Dashboard Walkthrough</a>
* <a href="https://proquest.libguides.com/ld.php?content_id=74086531">TDM Studio Researcher FAQ&nbsp;</a>

### Guides from other institutions:
* USC: <a href="https://libguides.usc.edu/contentmining">https://libguides.usc.edu/contentmining</a> (excellent overview of TDM with links to different tools including TDM Studio)
* Dartmouth: <a href="https://researchguides.dartmouth.edu/proquest_tdm_studio/intro">https://researchguides.dartmouth.edu/proquest_tdm_studio/intro</a> (this one is dedicated just to TDM Studio)
* NYU: <a href='https://guides.nyu.edu/tdm>https://guides.nyu.edu/tdm'>https://guides.nyu.edu/tdm>https://guides.nyu.edu/tdm</a> (a solid data science/text data mining guide with a great TDM Studio page)
* Carnegie Mellon: <a href='https://guides.library.cmu.edu/TDMStudio'>https://guides.library.cmu.edu/TDMStudio</a> (this one is dedicated just to TDM Studio)
* University of Chicago: <a href='https://guides.lib.uchicago.edu/tdmstudio<'>https://guides.lib.uchicago.edu/tdmstudio</a> (this one is dedicated just to TDM Studio)

### Need more Help?
 If you need technical assistance with TDM Studio, please feel free to contact us at the Map &amp; Data Library. You can either email&nbsp;<a href="mailto:mdl@library.utoronto.ca" tabindex="-1">mdl@library.utoronto.ca</a>&nbsp;or reach out with the MDL contact form. If you have any questions or concerns about Workbench access in particular, please email&nbsp;<a href="https://onesearch.library.utoronto.ca/library-staff/13291/sean-forbes">Sean Forbes, Director of the Milt Harris Library</a>
