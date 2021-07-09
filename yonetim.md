---
layout: page
title: Yönetim Kurulu
permalink: /yonetim-kurulu/
---


{% assign count = site.data.yk | size %}
<div class="row">
{% for i in (1..3) %}
    {% if site.data.yk[i] %}
      <div class="col d-flex text-center">
        <img src="{{ site.data.yk[i].image }}" />
        <div>
          {{ site.data.yk[i].name }}
        </div>
        <div>
          {{ site.data.yk[i].label }}
        </div>
      
    {% endif %]
  </div>
  </div>  
  
{% endfor %}
