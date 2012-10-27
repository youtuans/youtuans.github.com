---
layout: page
title: SICP解答
---
{% include JB/setup %}

<div class="row">
  <div class="span8">

<ul class="tag_box inline">
  {% assign tags_list = site.tags %}  
  {% include JB/tags_list %}
</ul>


{% for tag in site.tags %} 
  <h2 id="{{ tag[0] }}-ref">{{ tag[0] }}</h2>
  <ul>
    {% assign pages_list = tag[1] %}  
    {% include JB/reverse_pages_list %}
  </ul>
{% endfor %}
  </div>
  <div class="span4">
<ul class="tag_box inline">
  {% assign categories_list = site.categories %}
  {% include JB/categories_list %}
</ul>
  </div>
</div>


