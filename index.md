---
layout: page
title: "Welcome"
---
## Welcome to my CTF Archive. Thanks for visiting!

This site will document all my CTF shenanigans.

---

### Latest Writeups

Below you'll find the latest endeavors of my feeble mind.

{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
