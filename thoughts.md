---
layout: blog 
title: Thoughts
---

<div class="post">
  <ul class="related-posts">
    {% for post in site.posts limit:3 %}
      <li>
        <h3>
          <a href="{{ post.url }}">
            {{ post.title }}
            <small>{{ post.date | date_to_string }}</small>
          </a>
        </h3>
      </li>
    {% endfor %}
  </ul>
</div>
