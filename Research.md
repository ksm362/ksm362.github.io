---
layout: page
title: Research
---
<img src="{{ site.baseurl }}images/ABM_atrophy.png">

Skeletal muscles are dynamic organs, constantly adapting in response to stimuli.
The same muscle could regenerate following ischemia or atrophy during chachexia. 
While my previous work was focused on muscle specific adaptation and computational modeling (see projects below), my current work explores inter-organ communication.
All organs talk to one another during physiological and pathological conditions.
I am personally interested in muscle-driven inter-organ communication, such as during exercise.
To that end I have started working with a microfluidic platform to understand organ crosstalk.
I am also blessed to have the opportunity to collaborate with numerous peers and faculty. 
Please check out my projects and collaborations listed below. 

Projects
=======
<h3>
  {% assign post_list = site.posts %}
  {% for node in post_list %}
	{% if node.subtype != null %}
	  {% if node.subtype == page.title %}
		<a href="{{ node.url }}">{{ node.title }}<br></a>
	  {% endif %}
	{% endif %}
  {% endfor %}
  </h3>