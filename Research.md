---
layout: page
title: Research
---

I have had the privilage to work with many talented people on a miscellany of topics.
My primary work right now is focused on coordinating projects between Karolinska and Oura, a wearable biometric device company.
In Dr. Carl Johan Sundberg's lab, I have also begun to explore exercise induced adaptations in elite atheletes.
The lab has done some amazing work looking at transcriptomics and metabolomics in skeletal muscle, and I will be extended the work into adipose tissue.
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