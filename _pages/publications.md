---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<!-- TEMP WAY -->
* Amit Nagarkoti\*, <strong> Revant Teotia</strong>\*, Amith K. Mahale, and Pankaj K. Das, ”Realtime Indoor Workout Analysis Using Machine Learning & Computer Vision”, 41st Annual International Conference of the IEEE Engineering in Medicine and Biology Society (<strong>EMBC</strong>), Berlin, Germany, July 2019  <br>
  (* : equal contribution) <br>
  [paper](https://ieeexplore.ieee.org/document/8856547)

More publications coming soon ...

<!-- TEMP WAY END -->
<!-- TODO : IN FUTURE ADD PROJECS IN _projects and use the code below -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
