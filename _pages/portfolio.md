---
layout: archive
title: "PORTFOLIO"
permalink: /portfolio/
author_profile: true
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-FTB71GTS1Y"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-FTB71GTS1Y');
</script>

<!-- {% include base_path %} -->


<!-- {% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %} -->

## Deep Reinforcement Learning for Network Resource Management
[![View on Github](https://img.shields.io/badge/GitHub-View_on_GitHub-red?logo=GitHub)](https://github.com/linhhoang-ex/edgecomputing-drl) [![Open on IEEE Xplore](https://img.shields.io/badge/PDF-View_on_IEEE_Xplore-blue?logo=adobe-acrobat-reader&logoColor=white)](https://ieeexplore.ieee.org/document/10102429) [![Open on IEEE Xplore](https://img.shields.io/badge/PDF-Preprint_on_TechRxiv-blue?logo=adobe-acrobat-reader&logoColor=white)](/files/TechRxiv-ToN-DualConnectivity.pdf)
<p style='width:700px'>Designed an actor-critic DRL framework to assign mobile users to edge servers based on their traffic and network conditions. The objective is to minimize energy consumption given a delay threshold and with queue stability constraints. The actor module is based on a CNN (using Tensorflow), and the critic module is backed by Lyapunov optimization. The method reduces the energy to a 3% gap compared to an exhaustive search. The research was partly presented at IEEE ICC 2022 (won the <a href="https://icc2022.ieee-icc.org/registration/student-travel-grants.html">IEEE ComSoc Travel Grant</a>) and published in <a href="https://ieeexplore.ieee.org/document/10102429">IEEE/ACM Transactions on Networking</a>.</p>
<img src='/images/portfolio-ToN-methodology.png' width='700'>
<hr width="700px">

## SpaceX Falcon 9 First Stage Landing Prediction 
[![View on Github](https://img.shields.io/badge/GitHub-View_on_GitHub-red?logo=GitHub)](https://github.com/linhhoang-ex/SpaceX-Falcon9) [![open Project Report](https://img.shields.io/badge/PDF-View_Project_Report-blue?logo=adobe-acrobat-reader&logoColor=white)](/files/ds-capstone-project-report.pdf)

<p style='width:700px'>Collected SpaceX Falcon 9 launch data via web scraping (on Wikipedia) and making a request to the SpaceX API. Data wrangling, exploratory data analysis, and feature engineering were performed using SQL and Pandas. Used Plotly to build an interactive dashboard and Folium for launch sites locations analysis. Several machine learning models (SVM, Classification Trees, and Logistic Regression) were fine-tuned for successful landing prediction with an accuracy of 83%.</p>
<img src='/images/spacex-landing.gif' width='500'>
<hr width="700px">

## IBM Data Science Professional Certificate 
[![View on Github](https://img.shields.io/badge/GitHub-View_on_Github-red?logo=GitHub)](https://github.com/linhhoang-ex/ibm-ds-labs)
<p style='width:700px'>In this 10-course program, I practiced data science tools and skills with various real-world data sets in the IBM Cloud, including relational databases, SQL, Python, data visualization, data analysis, predictive modeling, and machine learning algorithms.</p>
<a href="https://www.coursera.org/account/accomplishments/specialization/certificate/T5J82G4VLTFP"><img src='/images/certi-ibm-ds.png' width='500'></a>
<hr width="700px">

## DeepLearning.AI Deep Learning Specialization
<p style='width:700px'>In this 5-course program, I built Convolutional Neural Networks, Recurrent Neural Networks, LSTMs, Transformers using Tensorflow to tackle various applications, such as object detection, speech recognition, music synthesis, and machine translation.</p>
<a href="https://www.coursera.org/account/accomplishments/specialization/certificate/TT2MHF48M4MA"><img src='/images/Certi-DL-Specialization.png' width='500'></a>
