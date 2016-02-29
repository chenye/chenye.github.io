---
layout: page
title: Publications
excerpt: "An archive of publications sorted by date."
search_omit: true
---


<div class="toc">

    <ul class="post">
      {% for item in site.categories.publications do %}
        {% include post-list.html %}
      {% endfor %}
    </ul>  
</div>
