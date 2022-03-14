---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Appsolutely Wonderful
---

# Welcome to The Workshop!

I'm glad you're here! You've found Daniel's portfolio.
Here you can find some projects I've worked on. I'm always
working on new things so check back often to see some cool
new projects.

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h2><a href="{{ site.baseurl }}{{ post.url }}">Project: {{ post.title }}</a></h2>

      <div class="entry">
        {{ post.description }}
      </div>
    </article>
  {% endfor %}
</div>
