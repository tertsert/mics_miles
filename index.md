---
layout: default
title: Home
---

# Welcome to My Blog

My name is Michael and starting July 6th 2025 I will be biking from the Canadian Border
all the way down to the Mexico border along the West Coast.

I will have daily updates posted here so follow along!

Check out my latest post below 👇

{% for post in site.posts limit:1 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
