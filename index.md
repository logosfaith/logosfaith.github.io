---
layout: default
title: Home
---

<section class="hero">
  <h1>Defending Truth with Reason</h1>
  <p>Exploring Christianity, philosophy, and evidence-based faith.</p>
</section>

<section class="featured">
  <h2>Featured Post</h2>
  <ul>
    {% for post in site.posts limit:1 %}
      <li>
        <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endfor %}
  </ul>
</section>

<section class="topics">
  <h2>Topics</h2>
  <ul>
    <li>Philosophy</li>
    <li>Atheism</li>
    <li>Morality</li>
    <li>Bible Reliability</li>
  </ul>
</section>

<section class="recent">
  <h2>Recent Posts</h2>
  <ul>
    {% for post in site.posts limit:5 %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</section>
