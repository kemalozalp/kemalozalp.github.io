---
permalink: /
title: "Professinal Summary"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a data scientist with +1-year experience in drug discovery at a growing start-up. During my postdoc, I developed and implemented state-of-the-art machine learning (ML) and deep learning (DL) models to the company's drug discovery pipeline. I used these models for ADMET modeling and early drug discovery of small and large molecules, specifically for hit-identification and in low-data conditions. Additionally, I spearheaded developing a data science experimentation pipeline using Data Version Control (DVC).

I use Python and its libraries, such as scikit-learn and PyTorch, for ML and DL model development; RDKit and Chembl Structure Pipeline for cheminformatic; SQL for data extraction from databases, such as ChEBML; and Git, DVC and Docker for MLOps. I used AWS for some personal projects, specifically RDS, Lambda and EC2 services.

My goal is to become a full stack data scientist and one of the top voices in the drug development field.

Academic Background
======
I received my Ph.D. in Biology from the University of North Carolina at Chapel Hill in December 2022. In my doctorate, I worked with [Dr. Laura Miller](https://sites.google.com/site/swimflypump/people/LauraMiller?authuser=0) who is now a professor of mathematics at the University of Arizona. In my doctorate, I investigated the movement of saltwater plankton at different spatial scales using statistical modeling, computational, and experimental fluid dynamics. During my master's studies, I developed a conceptual underwater vehicle inspired by squid propulsion. I received my masters in Marine Technology from Istanbul Technical University in 2014. Before my passion for biology, I studied Naval Architecture Engineering at Yildiz Technical University and received my bachelor's degree in 2010.

Why Data Science and Drug Discovery
======
My academic background is often a conversation piece. It is a great story, and I enjoy talking about it. I would be happy to discuss it with you, as well. Briefly, I began questioning why most man-made marine vehicles utilize propellers. Nature offers a wide variety of solutions, including cilia, rowing propulsion, flapping, and metachronal swimming. Problems and solutions found in natural systems are intellectually much more appealing to me than those in man-made systems. That being said, academia primarily focuses on knowledge generation but less on problem-solving. Perhaps because I got the engineering bug in my undergraduate, I decided to channel my energy into solving real-life problems rather than merely investigating intellectually appealing natural mysteries.

I have started coding in Matlab during my undergraduate. In my master's, I switched to Fortran for scientific computing. In my Ph.D., I used Matlab and Python in my thesis. Also, during my Ph.D., I began collecting data and analyzing it for finding the behavioral patterns of plankton. It was almost like a detective job. Finding connections between the movement behavior of plankton and their evolutionary past... This experience led me to develop a passion for data science. My transition to drug development occured after I completed an internship at a drug discovery start-up in 2022. It became clear to me after that moment that I wanted to utilize my skills to solve problems in the pharmaceutical industry.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
