---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /cv
---

{% include base_path %}

Education
======
* __Ph.D__ _in Biology_, The University of North Carolina at Chapel Hill &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;&emsp; &emsp; &emsp;2017 - 2022
* __M.S.__ _in Marine Technology_, Istanbul Technical University &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;&emsp; &emsp; &emsp; 2012 - 2014
* __B.S.__ _in Naval Architecture Engineering_, University of Applied Sciences Kiel &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &nbsp; 2008 - 2009
* __B.S.__ _in Naval Architecture Engineering_, Yildiz Technical University &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp; 2005 - 2010

Work experience
======
* __Collaborations Pharmaceuticals__ &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; Jan 2023 - Feb 2024\
 _Data Science Postdoc_
  * Built state-of-the-art (SOTA) ML and DL models to discover selective compounds for Alzheimer’s Disease; improved the precision of models by 61%; scanned 5M compounds and found 7 hits; paper in submission
  * Built SOTA DL model (few-shot learning) to be used in extremely low data situations; used GNN to create molecular representations; reduced the cost of experiments by 95%
  * Trained an LSTM-based generative model for de novo molecule design; fine-tuned a transformer-based LLM trained on 1.4B compounds to train a general transporter model for the drug discovery pipeline
  * Developed a PGNN model for multivariate regression of organophosphate pesticide (OPP) metabolism; reduced unrealistic concentration values in full decay curve predictions by 100%
  * Implemented DVC for data science experimentation and data versioning to the company’s ML pipeline
  * Wrote one first-author and one co-author, peer-reviewed papers in top tier journals

* __Collaborations Pharmaceuticals__ &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp;May - June 2022\
_Data Science Intern_
  * Analyzed a small dataset and explored various data manipulation techniques to improve models’ performances
  * Built a multivariate machine learning and deep learning model to predict dose response curves of compounds on different targets
  * Gave a presentation summarizing the progress made to project collaborators and CEO


* __The University of North Carolina at Chapel Hill__ &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &ensp;Aug 2017 - Dec 2022\
_Ph.D. Research Assistant_
  * Collected positional data on animals using computer vision systems; analyzed the positional data statistically and estimated distributions (MLE); analyzed behavior from the evolutionary perspective; paper in submission
  * Collected kinematics data on animals; ran CFD simulations on HPC; research became a thesis chapter
  * Performed fluid dynamics experiments on plankton dispersal; performed CFD; published peer-reviewed paper
  * Spearheaded two collaborative research projects and mentored 9 undergraduate students
  
Skills
======
* __Programming:__ Python &nbsp;&#124;&nbsp; SQL &nbsp;&#124;&nbsp; PySpark &nbsp;&#124;&nbsp; Unix shell  &nbsp;&#124;&nbsp; SLURM
* __MLOps:__ Git &nbsp;&#124;&nbsp; Data Version Control (DVC) &nbsp;&#124;&nbsp; Docker
* __ML/AI:__ PyTorch &nbsp;&#124;&nbsp; scikit_learn &nbsp;&#124;&nbsp; dgl &nbsp;&#124;&nbsp; dgllife
* __Cheminformatics:__ RDKit &nbsp;&#124;&nbsp; Chembl Structure Library &nbsp;&#124;&nbsp; ADMET modeling &nbsp;&#124;&nbsp; small and large molecule drug discovery &nbsp;&#124;&nbsp; hit-identification &nbsp;&#124;&nbsp; virtual screening

Certifications & Specializations
======
* [__Introduction to Chemistry: Reactions and Ratios by Duke University on Coursera__](https://coursera.org/verify/J9YLGLPXVK9W){:target='_blank'}
* [__Introduction to Chemistry: Structures and Solutions by Duke University on Coursera__](https://coursera.org/verify/Z4T7DHUH995B){:target='_blank'}
* [__Clinical Trials Operations Specialization by Johns Hopkins University on Coursera__](https://coursera.org/verify/specialization/2955H7UPVXBU){:target='_blank'}

Awards
======
* __Quick Thinking Award__ &#124; Collaboration Pharmaceuticals\
_For extinguishing fire at the workplace and saving company assets_
* __ARPA Graduate Degree Completion Grant ($8,000)__ &#124; UNC at Chapel Hill\
_Toward running experiments for a thesis chapter_
* __L. I. Gilbert Grant ($1,500)__ &#124; UNC at Chapel Hill\
_To attend “Computational Principles to Organize Complexity” Summer School_
* __Vehbi Koc Foundation Research Grant ($2,500)__ &#124; Istanbul Technical University\
_Toward the conceptual design of a pulsed-jet underwater vehicle inspired by squids_

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* __Volunteer__ at [Table NC](https://tablenc.org/who-we-are/){:target='_blank'}, _a non-profit organization which delivers healthy food and nutrition education to children in Orange County, NC_
