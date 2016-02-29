---
layout: page
title: Projects
excerpt: "An archive of projects sorted by date."
search_omit: true
---


<div class="toc">

    <ul class="post">
      {% for item in site.categories.projects do %}
        {% include post-list.html %}
      {% endfor %}
    </ul>  
</div>
