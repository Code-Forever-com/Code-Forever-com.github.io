---
layout: page
title: Yönetim Kurulu
permalink: /yonetim-kurulu/
---


<div class="row">
{% for i in site.data.yk %}
      <div class="col-12 col-md-4 text-center">
        <img src="{{ i.image }}" class="d-block rounded-circle" style="width: 10rem;height: 10rem;margin: 0 auto;"/>
        <div style="margin: 1rem auto;font-size: large;font-weight: 500;">
          {{ i.name }}
        </div>
        <div style="margin: 1rem auto;">
          {{ i.label }}
        </div>
       
      </div>      
  
{% endfor %}
    </div> 
