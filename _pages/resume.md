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
* __B.S.__ _in Naval Architecture Engineering_, Yildiz Technical University &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &nbsp; 2005 - 2010

Work experience
======
* __Collaborations Pharmaceuticals__ &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;Jan 2023 - Feb 2024\
&nbsp; _Data Science Postdoc_
  * Built state-of-the-art (SOTA) ML and DL models to discover selective compounds for Alzheimer’s Disease; improved the precision of models by 61%; scanned 5M compounds and found 7 hits; paper in submission
  * Built SOTA DL model (few-shot learning) to be used in extremely low data situations; used GNN to create molecular representations; reduced the cost of experiments by 95%
  * Trained an LSTM-based generative model for de novo molecule design; fine-tuned a transformer-based LLM trained on 1.4B compounds to train a general transporter model for the drug discovery pipeline
  * Developed a PGNN model for multivariate regression of organophosphate pesticide (OPP) metabolism; reduced unrealistic concentration values in full decay curve predictions by 100%
  * Implemented DVC for data science experimentation and data versioning to the company’s ML pipeline
  * Wrote one first-author and one co-author, peer-reviewed papers in top tier journals

* __Collaborations Pharmaceuticals__ &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; May - June 2022\
&nbsp; _Data Science Intern_
  * Analyzed a small dataset and explored various data manipulation techniques to improve models’ performances
  * Built a multivariate machine learning and deep learning model to predict dose response curves of compounds on different targets
  * Gave a presentation summarizing the progress made to project collaborators and CEO


* __The University of North Carolina at Chapel Hill__ &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; Aug 2017 - Dec 2022\
&nbsp; _Ph.D. Research Assistant_
  * Collected positional data on animals using computer vision systems; analyzed the positional data statistically and estimated distributions (MLE); analyzed behavior from the evolutionary perspective; paper in submission
  * Collected kinematics data on animals; ran CFD simulations on supercomputer; research became a thesis chapter
  * Performed fluid dynamics experiments on plankton dispersal; performed CFD; published peer-reviewed paper
  * Spearheaded two collaborative research projects and mentored 9 undergraduate students
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
* Currently signed in to 43 different slack teams
