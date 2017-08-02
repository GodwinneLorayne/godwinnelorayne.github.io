---
title: Home Page
---

# Welcome To My Website



We are ready to get this going in earnest.



And now we have edit and auto-serve working.

# Posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>