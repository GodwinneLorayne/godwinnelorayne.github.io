---
title: Home Page
---

# Welcome To My Website



We are ready to get this going in earnest.



And now we have edit and auto-serve working.

And now we can work on stuff in the left pane, and all we have to do is refresh the right pane and it will update.

This is definitely really cool stuff going on here. Must show it to some peoples.

The next step is to experiment with a bunch of themes and templates. We want to be able to show the list of all posts on the site by date in a pane on the...right? left?

# Posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>