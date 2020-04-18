---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to Freddie's website
---

## What is it?

This website was set up during the **coronavirus lockdown**. this webstite constists of post of stunning pictures to updates on life for Fredddie Yeo in the covid-19 crisis. Please enjoy this webstie and the regular posts and improvemens whch comes with it :)




<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


