---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- TEMP WAY -->
* <strong>COFAR: Commonsense and Factual Reasoning in Image Search</strong> <br>
  Prajwal Gatti, Abhirama Subramanyam Penamakuri, Anand Mishra, <strong>Revant Teotia</strong>, Shubhashis Sengupta, Roshni Ramnani 
  <br>
  Accepted in AACL-IJCNLP 2022

* <strong>Doubly Right Object Recognition</strong> <br>
  <strong>Revant Teotia</strong>, Chengzhi Mao, Carl Vondrick 
  <br>
  ICML 2022 Workshop on Spurious Correlations, Invariance, and Stability (<strong>Spotlight talk, among top-5 papers</strong>)

* <strong>Finding Spuriously Correlated Visual Attributes</strong> <br>
  <strong>Revant Teotia</strong>, Chengzhi Mao, Carl Vondrick 
  <br>
  ICML 2022 Workshop on Spurious Correlations, Invariance, and Stability

* <strong>Few-shot Visual Relationship Co-localization</strong> <br>
  <strong>Revant Teotia</strong>, Vaibhav Mishra, Mayank Maheshwari, Anand Mishra <br>
  ICCV 2021 <br>
  [paper](https://arxiv.org/abs/2108.11618) | [project page](https://vl2g.github.io/projects/vrc/) | [code](https://github.com/vl2g/VRC.git)

* <strong>Realtime Indoor Workout Analysis Using Machine Learning & Computer Vision</strong> <br>
  Amit Nagarkoti, <strong> Revant Teotia</strong>, Amith K. Mahale, and Pankaj K. Das <br>
  IEEE EMBC 2019 <br>
  [paper](https://ieeexplore.ieee.org/document/8856547)

<!-- TEMP WAY END -->
<!-- TODO : IN FUTURE ADD PROJECS IN _projects and use the code below -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
