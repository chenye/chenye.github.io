---
layout: default
title: Home
---

<div class="toc">
  <h2> Posts </h2>
  <ul class="post">
  {% for item in site.posts do %}

    {% include post-list.html %}

  {% endfor %}
  </ul>  

</div>

