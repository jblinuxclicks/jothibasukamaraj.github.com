---
layout: archive
permalink: /devops/
title: "Devops Projects"
---
<div class="postGroup"> 
  <h2 class="archive__subtitle">Recent posts</h2>
  {% for post in site.categories['Devops Projects'] %}
    {% include archive-single-experimental.html %}
  {% endfor %}
</div>
