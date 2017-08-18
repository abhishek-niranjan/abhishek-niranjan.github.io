---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<!-- {% for post in site.talks %}
  {% include archive-single.html %}
{% endfor %} -->


### Temporal Analysis of Tasks and Techniques in Computational Linguistics : Natural Language Processing | IIT Kharagpur | Jan '17 - Present

* This project focuses on studying how the popularity of different tasks an techniques related to Natural Language Processing Research emerge/varies with respect to time. 

* Extracted key-phrases and relations from citation-contexts from research articles to study the temporal emergence of various tasks and techniques in Computational Linguistics field. Clustered the research papers based on pre-defined groups such as research task addressed, approach of the solution, etc. by utilising supervised learning with tf-idf vectors of citation context as features. Built a citation network using NetworkX and Graphviz packages to study temporal variation and emergence of different applications and techniques in the field of Computational Linguistics. Future work involves improving the recall while tagging research articles with tasks and techniques. 


### Copying Citation Contexts : Natural Language Processing | IIT Kharagpur | Aug '16 - Jan '17

* We analyzed a massive dataset comprising of nearly 1.5 million computer science articles and more than 26 million citation
contexts to understand the behavior of "Copying Citation Contexts" amongst the researchers. I conducted experiments involving cosine similarity measure to reveal the copying pattern in 24 fields of computer science, and examined the variation, of copying phenomena in the most cited research papers, in subsequent 5 years of their publication. _Research Paper accepted in Joint Conference on Digital Libraries(JCDL), 2017_

* You can [Download the research paper here](https://arxiv.org/pdf/1705.02499.pdf) and visit the [Github Repository here](https://github.com/abhishek-niranjan/Citation-Reuse-and-Copying)

### Competitive Strength Prediction of ATM Vendors in California : Data Analytics | IIT Kharagpur | Jan '17 - Mar '17

* We assessed the competitive strength of 3 major ATM vendors using spatial ATM network and the demographics of California. We visualized feature importance using Tableau and clustered the ATM locations by utilizing k-means approach, and reverse engineered the feature weights by applying Random Forest Classifier on the clustered data for each county. I built a county specific linear regressor to model the revenue of each ATM, and enhanced the whole California state linear model by adding county-specific linear model to estimate the annual revenue generation of each ATM location.

* [Project Report](https://abhishek-niranjan.github.io/files/prj3.pdf)

### Sign Language Translation Through Sensory Gloves : Machine Learning | IIT Kharagpur | Aug '16 - Nov '16

* I worked in a team to translate American sign language gestures to text using flex sensing gloves with positional sensors. We compared different classifiers on input data from sensory gloves to train the alpha-numerical character recognition algorithm, and built a statistical language model based on stochastic grammar to recognise meaningful words from a stream of characters.

* [Github Repository](https://github.com/abhishek-niranjan/SignToSpeech)

### Topic Drift in Comments Section of Articles : Natural Language Processing | IIT Kharagpur | Jan '16 - Apr '16

* I studied the phenomena of Topic Drifting in the comments section of an online article by identifying the comment which
deviates from the topics touched by the article or discussion in the prior comments. I applied LDA (Latent Dirichlet Allocation) Model to generate the topics associated with the content of the article, Thus, tagging article sentences to the corresponding topic. I finally employed cosine similarity metric to map comments to the topics generated from the article to filter out the true negatives.

* [Final Term Project Presentation](https://abhishek-niranjan.github.io/files/prj5.pdf)

### Data Extractor from 2D Plots : Software Development | IIT Kharagpur | Mar '16 - Apr '16

* I worked in a team of 15 members in Inter-Hall Software Development Competition to build a graph extractor that detects
plots in any PDF and digitizes the graphs. I was responsible to build a module which digitizes the plot lines using the pixel values from the graphical(BW) image by aptly scaling them to the given range of the axes imported from the OCR module using Python Imaging Library.

* [Github Repository](https://github.com/abhishek-niranjan/Opensoft-2016)