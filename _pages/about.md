---
permalink: /
title: "Huanyu Tian"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Huanyu Tian is a Postdoctoral Research Associate in Surgical & Interventional Engineering at King's College London and a Consultant in AI for Microscopy Images at Conceivable Life Sciences. He received his Ph.D. in Medical Robotics from Beijing Institute of Technology in 2024. His work sits at the intersection of surgical autonomy, robot learning, shared autonomy, and perception-driven control. Tian develops embodied robotic agents that blend learning-based perception with physics-informed planning to deliver safe, precise assistance in contact-rich clinical settings.

Current projects explore vision-guided micromanipulation, foundation models for life-science microscopy, uncertainty-aware shared control, and semi-autonomous laparoscopic docking. He frequently collaborates with clinical partners to translate algorithms into workflow-aware systems that respect surgeon intent while improving accuracy and reducing setup time. His research has been recognized through the Bota Systems Research Sponsorship, the NVIDIA Academic Grant Program, the Outstanding Doctoral Dissertation Award from Beijing Institute of Technology, and a Best Student Paper Award at IEEE CYBER.

Selected Publications
======
{% assign featured_publications = site.publications | where: "featured", true | sort: "featured_order" %}
{% for post in featured_publications %}
  {% include archive-single.html %}
{% endfor %}
