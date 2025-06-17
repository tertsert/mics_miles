---
layout: default
title: Home
---

# Welcome to My Blog

Here's my Wandrer map embedded below:

<iframe src="https://wandrer.earth/users/your-wandrer-username/embed" width="100%" height="600" frameborder="0" scrolling="no"></iframe>

Check out my latest post below 👇

{% for post in site.posts limit:1 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
