---
layout: default
title: Home
---

[Blog](blog)  --  [Projects](projects)  --  [Publications](publications)
==========================
<div class="toc">
  <h2>Recent posts</h2>
  <ul class="post">
  {% for item in site.posts do %}

    {% include post-list.html %}

  {% endfor %}
  </ul>  

</div>

