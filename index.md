---
layout: home
title: Frauditor
---

# Frauditor

It takes one to know one.

## Table of Contents

{% for chapter in site.chapters %}
1. [{{ chapter.title }}]({{ chapter.url | relative_url }})
{% endfor %}

## Supplementary Content

- [Wiki Pages](/wiki)
- [Research Notes](/research)
