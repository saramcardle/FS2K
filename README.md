# From Samples to Knowledge 2025 Repo
Jupyter notebooks for teaching QuPath - Feb 2025, QuPath v0.6.0rc3<br>
Hosted by [The Microscopy and Histology Core Facilities at La Jolla Institute](https://www.lji.org/research/research-services/microscopy-histology/)<br>
Sara McArdle<br>
Zbigniew Mikulski<br>
and
Michael Nelson of [LOCI](https://loci.wisc.edu/)

- [YouTube playlist of the recordings](https://www.youtube.com/watch?v=wvi54EbP-7U&list=PLlGXRBscPbCCA1yGCThNqdYKgTPOvjigp) of our QuPath Training Course “From Samples to Knowledge”, which took place at La Jolla Institute for Immunology on February 24-25, 2025. 

## Ask questions in the image.sc forum thread!
We ask that the majority of questions be directed to the [image.sc forum thread here](https://forum.image.sc/t/question-thread-from-samples-to-knowledge-2025/108739), where it will be easiest for all of the hosts to respond to questions and issues as they have time.<br>
If you are interested in keeping up with the topic, make sure to create an image.sc forum profile, and set the post to "Watching" - which will send a notification email whenever there is a new post.<br><Br>
<img src="Images/imagescWatching.PNG" width="500">

## Prepare for the workshop

### Introductory video
Please watch this short video which introduces some QuPath concepts and has some information on installation issues.<br>
[![Introduction video](https://img.youtube.com/vi/Vl9V5PxOQIc/0.jpg)](https://youtu.be/Vl9V5PxOQIc)<br>

### Install QuPath: we will be using: 0.6.0RC3
Make sure to install QuPath **ahead of time**, as some companies/institutes/hospitals <span style="color:red">**require administrator access**</span> to download and set up QuPath.<br>
[Get it here!](https://github.com/qupath/qupath/releases)<br>
<img src= "Images/downloadQuPath.PNG" width="500"><br>

### Download your data and scripts!
If you wait until you arrive, you will be competing with everyone else for bandwidth!<br>
[Download the files from Google Drive](https://drive.google.com/drive/u/1/folders/1t5DtJriZdPpNpuVJBMACkN3Ra16QUjKu)<br>
<img src= "Images/downloadMaterials.PNG" width="500"><br>
You must unzip your files before using them!
See steps 1 and 2 in Session 1 to create your first project!<br>

### Download the Warpy extension and InstanSeg models
Install [the Warpy extension](https://github.com/BIOP/qupath-extension-warpy) into your copy of QuPath 0.6.0<br>
[Warpy download here](https://github.com/biop/qupath-extension-warpy/releases)<br>
There will be a number of .jar files - drag them into an open QuPath window to install, or create an Extensions folder in QuPath's *Preferences* <kbd>Edit > Preferences > Extensions</kbd> and place them in that folder.<br><br><br>
Instructions for InstanSeg setup can be found by scrolling down to [Method 2- One Time Setup, here.](https://github.com/saramcardle/FS2K/blob/main/Session%204-%20Cell%20Detection.ipynb)<br>
<img src= "Images/djlSetup.PNG" width="800"><br><br>
<img src= "Images/instansegSetup.PNG" width="800"><br>

### If you have time, watch this excellent introduction by the author of QuPath!
[![PeteBankheadIntro](https://img.youtube.com/vi/HHo2BIacq8w/0.jpg)](https://youtu.be/HHo2BIacq8w?t=35)<br>
Or skip directly to [the part of the video discussing QuPath](https://youtu.be/HHo2BIacq8w?t=1835)!


# See you there and online!

## Additional resources
![knowledge](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2d1Y3Bqa3loOWI5bnFhNmoxeHpzOTB5ZjVpZDV1eThpNGI0MXg4biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/SXqw0Vpql4sHX9pCl4/giphy.gif)
### Ask questions (the devs check here)
[https://forum.image.sc/tag/qupath](https://forum.image.sc/tag/qupath)<br>

### QuPath documentation for 0.5, the latest stable release<br>
Main docs - [https://qupath.readthedocs.io/en/0.5/](https://qupath.readthedocs.io/en/0.5/) <br>
Scripting Javadocs - [https://qupath.github.io/javadoc/docs/](https://qupath.github.io/javadoc/docs/)<br>

### Introduction to QuPath scripting (unofficial)
[https://www.imagescientist.com/image-analysis](https://www.imagescientist.com/image-analysis)<br>

### Useful plugins and associated software
#### Segmentation<br>
[https://github.com/qupath/qupath-extension-stardist](https://github.com/qupath/qupath-extension-stardist)<br>
[https://github.com/BIOP/qupath-extension-cellpose](https://github.com/BIOP/qupath-extension-cellpose)<br>
[https://github.com/qupath/qupath-extension-instanseg](https://github.com/qupath/qupath-extension-instanseg)<br>
[https://github.com/ksugar/qupath-extension-sam](https://github.com/ksugar/qupath-extension-sam)
#### Aligning images<br>
[https://github.com/qupath/qupath-extension-align](https://github.com/qupath/qupath-extension-align)<br>
[https://imagej.net/plugins/bdv/warpy/warpy-image-combiner](https://imagej.net/plugins/bdv/warpy/warpy-image-combiner)<br>
#### Python access<br>
[https://github.com/Bayer-Group/paquo](https://github.com/Bayer-Group/paquo)<br>


### Interesting reading - imaging and analysis
Start Here<br>
[!!!Introduction to Bioimage Analysis!!!](https://bioimagebook.github.io/index.html)<br>
[Workflows and Components of Bioimage Analysis](https://link.springer.com/chapter/10.1007/978-3-030-22386-1_1)<br>
[A biologist’s guide to planning and performing quantitative bioimaging experiments](https://pmc.ncbi.nlm.nih.gov/articles/PMC10298797/)<br>

General<br>
:heavy_dollar_sign: [Multiplex protein imaging in tumor biology - review](https://www.nature.com/articles/s41568-023-00657-4)<br>
[Spatial analysis by current multiplexed imaging technologies for the molecular characterisation of cancer tissues](https://pmc.ncbi.nlm.nih.gov/articles/PMC11589153/)<br>
[Video - Creating quality microscopy figures for manuscripts](https://youtu.be/CgfnlcxbjuI?t=2415)<br>
[Additional video on figure creation](https://www.youtube.com/watch?v=F6ll37NOgXc)<br>
[Creating and troubleshooting microscopy analysis workflows: Common challenges and common solutions](https://onlinelibrary.wiley.com/doi/10.1111/jmi.13288)<br>
[Developing open-source software for bioimage analysis: opportunities and challenges](https://pmc.ncbi.nlm.nih.gov/articles/PMC8226416/)
[Open-source deep-learning software for bioimage segmentation](https://pmc.ncbi.nlm.nih.gov/articles/PMC8108523/)<br>
[The QuPath community](https://analyticalscience.wiley.com/content/article-do/qupath-community)<br>

Do good things, not bad things!<br>
[Avoiding a replication crisis in deep-learning-based bioimage analysis](https://pubmed.ncbi.nlm.nih.gov/34608322/)<br>
[Avoiding Twisted Pixels: Ethical Guidelines for the Appropriate Use and Manipulation of Scientific Digital Images](https://pmc.ncbi.nlm.nih.gov/articles/PMC4114110/)<br>
[Imaging methods are vastly underreported in biomedical research](https://pmc.ncbi.nlm.nih.gov/articles/PMC7434332/)<br>
[Reproducibility standards for machine learning in the life sciences](https://pmc.ncbi.nlm.nih.gov/articles/PMC9131851/)<br>

# Acknowledgements
Peter Sobolewski, for helping convert this repo into a classier website/Gitbook! <br>
Staff from the [La Jolla Institute](https://www.lji.org/about-us/), including <br>
Lisa Bouker, Admin Assistant Extrordinaire!<br>
Zeynel Savari for AV and IT help<br>
The LJI Facilities department<br>
<br>
Funding: Chan Zuckerberg Initiative Imaging Scientist grant<br>
<br>
[Research group of Pete Bankhead](https://institute-genetics-cancer.ed.ac.uk/research/research-groups-a-z/peter-bankhead-research-group)<br>

