---
permalink: /
title: "The Wilkinson lab studies autophagy and cancer pathways"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

We study the interplay between intracellular membrane dynamics - particularly membrane modification by ubiquitin-like proteins and the autophagy pathway - and cell signalling during cancer development and treatment, focussing on processes such as control of gene expression, cellular identity, inflammation and anti-tumoural immunity.

Impact
======
Our team strives for gaining new knowledge every day and uncovering early cellular switches that indicate cancer development. Each cellular pathway is an ocean of knowledge waiting to be discovered.

We have a particular interest in the role of the Endoplasmic Reticulum (ER) in maintaining cellular homeostasis and affecting pathways during pathogenesis. Several genes have shown links between autophagy and cancer development. 

How it Started
======
Simon Wilkinson studied at University of Edinburgh from 1996, gaining a 1st class degree in Biochemistry. In late 2000, he moved to the Institute of Cancer Research in London, to study for his doctorate in the Cancer Research UK Tumour Cell Signalling Unit, under the supervision of Prof. Chris Marshall. His work here investigated the different signalling requirements of diverse tumour cell types for motility and invasion. In the course of this work he became very interested in the different mechanisms by which tumour cells engage protein kinase signalling pathways.

In 2005, Simon joined the Beatson Institute for Cancer Research as a postdoctoral scientist. Here, working with Prof. Kevin Ryan, he became interested in autophagy in cancer and worked on the identification of an ‘autophagy kinome’ - a set of protein kinases that engaged various different forms of autophagy. In 2010, Simon moved back to Edinburgh to work with Prof. Margaret Frame looking at the interplay between autophagy and cell signalling, focussing on Src kinase. In 2012, he was awarded a prestigious Career Development Fellowship from Cancer Research UK in order to establish his own laboratory in Edinburgh. After the award of a Cancer Research UK Senior Fellowship in 2020, his lab now studies the interplay between intracellular membrane dynamics - particularly membrane modification by ubiquitin-like proteins and the autophagy pathway - and cell signalling during cancer development and treatment, focussing on processes such as control of gene expression, cellular identity, inflammation and anti-tumoural immunity. Simon was appointed the Chair of Autophagy and Tissue Homeostasis in the autumn of 2023.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
