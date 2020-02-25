---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
+ Decoupled States in Networks of Limit Cycle Oscillators
We consider networks of rotationally symmetric phase amplitude oscillators (e.g., coupled Stuart Landau) and study a particular type of state.
The state consists of splay states separated from each other by an arbitrary phase difference.
We show how these states arise from the interplay of dynamics and topology.
We demonstrate that these states can arise in networks 

+ Stability of dynamically decoupled synchronized clusters from system symmetries


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
