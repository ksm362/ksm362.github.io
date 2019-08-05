---
layout: page
title: Research
---

I have had the privilage to work with many talented people on a miscellany of topics.
My current research in Dr. Jorge Ruas's lab is focused on adipose and sensory nerve communication.
To that end, I have started working with a microfluidic platform to understand how these two organs communicate with one another.
I am also blessed with the opportunity to collaborate with numerous peers and faculty. 
Please check out my current and past projects listed below. 

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