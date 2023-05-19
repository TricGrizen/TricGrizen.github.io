---
layout: category
title: Math
---

<h2 class="post-list-heading">Calculus</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "Math" and post.subcategory == "Calculus" %}
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

<h2 class="post-list-heading">Linear Algebra</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "Math" and post.subcategory == "Linear Algebra" %}
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

<h2 class="post-list-heading">Probability Theory</h2>
<ul class="post-list">
  {% for post in site.posts %}
    {% if post.category == "Math" and post.subcategory == "Probability Theory" %}
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

