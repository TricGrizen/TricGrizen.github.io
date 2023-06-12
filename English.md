---
layout: category
title: English
---

<h2 class="post-list-heading">考研</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "English" and post.subcategory == "考研" %}
      <li>
        <span class="post-meta">{{ post.date | date: "%B %d, %Y" }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title }}
          </a>
        </h3>
      </li>
    {% endif %}
  {% endfor %}
</ul>

<h2 class="post-list-heading">考级</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "English" and post.subcategory == "考级" %}
      <li>
        <span class="post-meta">{{ post.date | date: "%B %d, %Y" }}</span>
        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title }}
          </a>
        </h3>
      </li>
    {% endif %}
  {% endfor %}
</ul>
