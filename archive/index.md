---
layout: page
title: Archive
---

{% for post in site.posts %}
<div class="row">
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

  {{ post.excerpt }}

  [Read more...]({{ post.url}})
</div>
{% endfor %}
