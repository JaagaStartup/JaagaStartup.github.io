---
layout: page
title: "Meet our experts"
meta_title: "Experts at Jaaga Startup"
subheadline: ""
teaser: ""
permalink: "/experts/"
---

{% for expert in site.data.experts %}
<div class="row">
  <div class="large-6 columns">
  	<a href="http://jaagastartup.in/{{ expert.profile_url }}/" target="_blank"><img src="{{ site.url }}{{ site.baseurl }}/images/{{ expert.image }}" width="200"  alt="{{ expert.name }}"></a>
  </div>
  <div class="large-6 columns" align="center">
    	<h2><a href="http://jaagastartup.in/{{ expert.profil_url }}/">{{ expert.name }}</a></h2>
      <br>
      <subheadline><em> {{ expert.skill }}</em></subheadline>
      <br>
  </div>
</div>

<br>
{% endfor %}
