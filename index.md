---
layout: page
title: Passion Talks
tagline: Connecting Work and Faith
---

# [Passion Talks 2014](/pt14)

----

{% for post in site.posts %}

  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

  {{ post.excerpt }}

  [Read more...]({{ post.url}})
{% endfor %}
