---
layout: default
title: "My articles in my blog"
permalink: /
---

<h1>Article list</h1>
{% for post in site.posts %}
<article>
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
<time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
</article>
{% endfor %}
