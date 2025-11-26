---
layout: default
title: Home
---

# Welcome to My Coding Journey! 👋

![Coding Journey](https://via.placeholder.com/800x400/4A90E2/FFFFFF?text=My+Coding+Adventure)

I'm on an exciting journey to become a developer! This site documents my progress, projects, and learning experiences.

## 🚀 Quick Links
- [📚 Learning Notes](/notes)
- [💻 My Projects](/projects)
- [🛠️ Code Snippets](/code-snippets)
- [📖 Resources](/resources)

## 🎯 Current Focus
- Mastering Git & GitHub
- Learning web development fundamentals
- Building my first projects

## 📈 Recent Updates
{% for post in site.posts limit:3 %}
- **[{{ post.date | date: "%b %d, %Y" }}]** [{{ post.title }}]({{ post.url }})
{% endfor %}

---
*Last updated: {{ site.time | date: "%B %d, %Y" }}*
