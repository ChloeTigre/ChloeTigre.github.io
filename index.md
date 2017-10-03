---
title: 🐯🐯🐯 Chloé Tigre Rouge 🐯🐯🐯
---
# Chloé Tigre Rouge's Site
Just a personal site where I'll write about software, system admnistration and automation, when I have the occasion or something to share.

I'll try to post recipes, random thoughts and stuff like this aswell.

One day I may even decide to dig old contents and share it here.

# Blog posts

{% for post in site.posts %}
-- Render the post layout for this post.
<a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
