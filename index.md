---
layout: default
title: Home
---

This is my personal technical website that blends a blog and a portfolio. It contains contents related to multi-agent simulation, artificial intelligence, as well as many other interesting topics in computer science and engineering.


The posts are classified into three categories:

* Blog - includes posts about the problems I encountered and the way to solve them.

* Projects - the projects related to my personal interests in computer science. Some of them may be related to the publications. They are usually open source and available in my github.

* Publications - introduces my published research articles. Sometimes, related code and data is provided.


Please either find posts in these three categories from the hidden side-bar, or just browse through the list of recent posts from all categories as follows.

<div class="toc">
  <h2>Recent posts</h2>
  <ul class="post">
  {% for item in site.posts do %}

    {% include post-list.html %}

  {% endfor %}
  </ul>  

</div>

