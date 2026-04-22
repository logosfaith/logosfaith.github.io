Markdown
---
layout: default
title: Home
---

<section class="hero">
  <h1>Defending Truth with Reason</h1>
  <p>Exploring Christianity, philosophy, and evidence-based faith.</p>
</section>

<section>
  <h2>Recent Posts</h2>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</section>
