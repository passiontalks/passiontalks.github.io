---
layout: page
title: Passion Talks 2014
title_url: /pt14
tagline: "Connecting Work and Faith | Conference: August 23rd, 2014, Berkeley"
---

{% for post in site.posts %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>

  {{ post.excerpt }}

  [Read more...]({{ post.url}})
{% endfor %}
