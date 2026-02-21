---
layout: default
title: The Hybrid Systems Engineer
---

# The Hybrid Systems Engineer

Real-world Microsoft hybrid infrastructure, identity, and automation engineering.

---

## Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

---

## About

I document practical lessons from operating hybrid Microsoft environments — where Active Directory, Entra ID, endpoint management, and automation intersect.

Automation is not convenience — it is operational survival.

---

## Toolkit

[Enterprise Hybrid Toolkit](/toolkit)
