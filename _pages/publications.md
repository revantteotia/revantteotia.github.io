---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- TEMP WAY -->
* <strong>Affective Faces for Goal-Driven Dyadic Communication</strong> <br>
  Scott Geng, <strong>Revant Teotia</strong>, Purva Tendulkar, Sachit Menon, Carl Vondrick 
  <br>
  In submission <br>
  [arXiv](https://arxiv.org/abs/2301.10939) [project page](https://realtalk.cs.columbia.edu/)

* <strong>Doubly Right Object Recognition: A Why Prompt for Visual Rationales</strong> <br>
  Chengzhi Mao, <strong>Revant Teotia</strong>, Amrutha Sundar, Sachit Menon, Junfeng Yang, Xin Wang, Carl Vondrick 
  <br>
  CVPR 2023 <br>
  [arXiv](https://arxiv.org/abs/2212.06202)

* <strong>COFAR: Commonsense and Factual Reasoning in Image Search</strong> <br>
  Prajwal Gatti, Abhirama Subramanyam Penamakuri, <strong>Revant Teotia</strong>, Anand Mishra, Shubhashis Sengupta, Roshni Ramnani 
  <br>
  AACL-IJCNLP 2022 <br>
  [paper](https://aclanthology.org/2022.aacl-main.87/) | [project page](https://vl2g.github.io/projects/cofar/)

  
* <strong>Doubly Right Object Recognition</strong> <br>
  <strong>Revant Teotia</strong>, Chengzhi Mao, Carl Vondrick 
  <br>
  ICML 2022 Workshop on Spurious Correlations, Invariance, and Stability (<strong>Spotlight talk, among top-5 papers</strong>) <br>
  [paper](https://openreview.net/pdf?id=O0hJOvsYUlt)

* <strong>Finding Spuriously Correlated Visual Attributes</strong> <br>
  <strong>Revant Teotia</strong>, Chengzhi Mao, Carl Vondrick 
  <br>
  ICML 2022 Workshop on Spurious Correlations, Invariance, and Stability <br>
  [paper](https://openreview.net/pdf?id=HeqIy9TbctF)

* <strong>Few-shot Visual Relationship Co-localization</strong> <br>
  <strong>Revant Teotia</strong>, Vaibhav Mishra, Mayank Maheshwari, Anand Mishra <br>
  ICCV 2021 <br>
  [paper](https://openaccess.thecvf.com/content/ICCV2021/html/Teotia_Few-Shot_Visual_Relationship_Co-Localization_ICCV_2021_paper.html) | [project page](https://vl2g.github.io/projects/vrc/) | [code](https://github.com/vl2g/VRC.git)

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
