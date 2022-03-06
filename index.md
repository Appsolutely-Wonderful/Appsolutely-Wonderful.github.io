---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Appsolutely Wonderful
---

# Welcome to The Workshop!

I'm glad you're here! You've found Daniel's portfolio.
Here you can find some projects I've worked on. I'm always
working on new things so check back often to check out some
cool new projects.

## Projects
Check back often as I continue to add more projects.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

