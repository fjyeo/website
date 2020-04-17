---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Freddie's website
---

## What is it?

My website

## How to use it

Read the posts

<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


