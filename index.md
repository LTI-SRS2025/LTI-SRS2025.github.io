---
layout: page
title: LTI-SRS
subtitle: "The 2025 LTI Student Research Symposium"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (Gates & Hillman Centers (GHC) 6115, Carnegie Mellon University, April 18, 2025)
</div>

<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />

# Reviewer Nomination

If you'd like to become a reviewer for the Symposium, or recommend someone, [please use this form](https://docs.google.com/forms/d/e/1FAIpQLSdiOWaFpBVvKZUFwPii0ZDiVnp8eHdQKgYrQ28cpKJ9Kq2v8w/viewform?usp=dialog).

# Overview

The Student Research Symposium (SRS) is an LTI-wide event for students to show their recent and/or ongoing research and projects to the community. Submissions from students are selected to be presented as talks or posters/demos throughout the day-long event. During the event, talks and posters/demos are judged by a panel of students and faculty. This is a great chance to enjoy the camaraderie of students and faculty, and munch on good food together! In addition, if you have a speaking requirement for your degree program (e.g., MLT), participating in this event can fulfill that requirement!


## Topics of Interest
For a list of relevant submission topics, see the submission topics under [EMNLP 2024’s call for papers](https://2024.emnlp.org/calls/main_conference_papers/) as well as [COLM 2025’s call for papers](https://colmweb.org/cfp.html). These include (but are not limited to):
- Computational Social Science and Cultural Analytics
- Dialogue and Interactive Systems
- Discourse and Pragmatics
- Efficient Methods for NLP
- Ethics and NLP
- Generation
- Information Extraction
- Information Retrieval and Text Mining
- Interpretability and Analysis of Models for NLP
- Knowledge Representation and Reasoning 
- Language Grounding to Vision, Robotics, and Beyond
- Linguistic theories, Cognitive Modeling and Psycholinguistics
- Machine Learning for NLP
- Machine Translation and Multilinguality
- Multimodality
- NLP Applications
- Phonology, Morphology, and Word Segmentation
- Question Answering
- Resources and Evaluation
- Semantics: Lexical
- Semantics: Sentence-level Semantics, Textual Inference, and Other areas
- Sentiment Analysis, Stylistic Analysis, and Argument Mining
- Speech Processing, Speech Recognition, Speech Synthesis
- Summarization

[Submission Link](https://openreview.net/group?id=cmu.edu/CMU/2025/LTI-SRS). Please refer to [Call for Papers](./cfp/) for submission guidance.

<hr>

# Speakers

<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% if forloop.index<=5 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>5 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Organizing Committee
- Student Members: 
  - Lindia Tjuatja (lindiat@andrew.cmu.edu)
  - Weihua Du (weihuad@andrew.cmu.edu)
  - Weiwei Sun (weiweis@andrew.cmu.edu)
- Faculty Members: 
  - Ralf Brown (ralf@andrew.cmu.edu)
  - Lori Levin (levin@andrew.cmu.edu)
  - Sean Welleck (swelleck@andrew.cmu.edu)

<!-- # Program Committee
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr>

# Related Venues

<div class="container" style="margin-bottom: 10px;"></div>
- [ICML'24 Workshop on AI4MATH - AI for Math Workshop @ ICML 2024](https://sites.google.com/view/ai4mathworkshopicml2024)
- [NeurIPS'23 Workshop on LTI-SRS - The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- [NeurIPS'22 Workshop on LTI-SRS - Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- [NeurIPS'21 workshop on MATHAI4ED - Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)
- [ICLR'21 workshop on LTI-SRS - The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- [NeurIPS'20 Workshop on KR2ML - Knowledge Representation & Reasoning Meets Machine Learning](https://kr2ml.github.io/2020)
- [NeurIPS'20 workshop on Advances and Opportunities: Machine Learning for Education](https://www.ml4ed.org/)
- [ICML'20 workshop on Bridge  Between Perception and Reasoning: Graph Neural Networks & Beyond](https://logicalreasoninggnn.github.io)

<div class="container" style="margin-bottom: 10px;"></div>

<hr> -->

Contact: feel free to contact any student organizers if you have questions or suggestions.
