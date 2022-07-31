---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Hi! I’m Allie.
---

# Hi! I’m Allie.

I’m a lead product manager at [Planning Center](http://planningcenter.com), where I focus on end-to-end user experiences in a multi-product ecosystem. I live in Indianapolis with my husband and two small humans.

Sometimes [I write TinyLetters](http://tinyletter.com/allier) (about: the enneagram, motherhood, theology, books, and other things I have feelings about). Some of those words also make their way over here.

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <div class="post-date">{{ post.date | date: "%B %-d, %Y" }}</div>
    </li>
  {% endfor %}
</ul>
