---
layout: page
title: Research
---
<img src="{{ site.baseurl }}images/ABM_atrophy.png">

Skeletal muscles are a dynamic organ, constantly adapting in response to stimuli.
The same muscle could regenerate following ischemia, hypertrophy from exercise, and atrophy during chachexia (maybe not all at one). 
Yet all of the aforementioned adaptations are orchestrated by the same cells and cellular structures. 
I am developing novel computational models to study muscle adaptation, focusing on cellular interactions to elucidate how adaptation is driven. 
To date, I have focused on disuse-induced atrophy and muscle inflammation and regeneration following injury.
I have also used experiments, in conjunction with computational models, to investigate muscle regeneration. 
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