---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
+ **Decoupled States in Networks of Limit Cycle Oscillators**

In progress

We consider networks of rotationally symmetric phase amplitude oscillators (e.g., coupled Stuart Landau) and study a particular type of state.
The state consists of splay states separated from each other by an arbitrary phase difference.
We show how these states arise from the interplay of dynamics and topology.
We demonstrate that these states can arise in networks 

+ **Stability of dynamically decoupled synchronized clusters from system symmetries*

In progress

We study the dynamically decoupled synchronization on a ring of coupled nanoelectromechanical oscillators.
This synchronization pattern is a result of the rotational symmetries of the full dynamics as well as the symmetries of the ring network.
We show how using these symmetries (both structural and beyond) can be used to simplify stability calculations.

+ **Koopman operator and its approximations for systems with symmetries**

**A Salova**, J Emenheiser, A Rupe, JP Crutchfield, RM D’Souza

+ Exotic states in a simple network of nanoelectromechanical oscillators

Matthew H Matheny, Jeffrey Emenheiser, Warren Fon, Airlie Chapman, **Anastasiya Salova**, Martin Rohden, Jarvis Li, Mathias Hudoba de Badyn, Márton Pósfai, Leonardo Duenas-Osorio, Mehran Mesbahi, James P Crutchfield, Michael C Cross, Raissa M D’Souza, Michael L Roukes

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
