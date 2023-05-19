---
layout: page
title: Life
permalink: /Life/
---
<h2 class="post-list-heading">Loveship</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "Life" and post.subcategory == "Loveship" %}
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

<h2 class="post-list-heading">Personal</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "Life" and post.subcategory == "Personal" %}
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

