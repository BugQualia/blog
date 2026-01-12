---
layout: default
---

# Minimal Markdown Blog

Welcome! This is a tiny, GitHub Pages-friendly blog built with Markdown and Jekyll.

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

---

## About

This site is intentionally minimal: a few posts, plain Markdown, and a short index page.
