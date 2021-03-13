---
layout: template.html
title: One Direction Albums
tags: page
---
    
# {{ title }}! 

<ul>
        {% for album in 1dAlbums -%}
      <li>  {{ album }} </li>
        {% endfor %}
</ul>