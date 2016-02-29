---
layout: page
title: Blog
excerpt: "An archive of blog posts sorted by date."
search_omit: true
---


<div class="toc">

    <ul class="post">
      {% for item in site.categories.blog do %}
        {% include post-list.html %}
      {% endfor %}
    </ul>  
</div>
