---
layout: page
title: Yönetim Kurulu
permalink: /yonetim-kurulu/
---


<div class="row">
{% for i in site.data.yk %}
      <div class="col-12 col-md-4 d-flex text-center">
        <img src="{{ i.image }}" />
        <div>
          {{ i.name }}
        </div>
       
      </div>      
  
{% endfor %}
    </div> 
