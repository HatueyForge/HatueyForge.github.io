---
layout: home
title: HatueyForge AI Experiments 
---

Welcome to HatueyForge! I'll be sharing thoughts and experiments mostly related to AI.

---

### Latest Posts

This section (or the layout itself) will typically list your most recent articles.

<!-- The content below is often handled by your Jekyll theme's 'home' or 'default' layout.
     If your theme doesn't automatically list posts, you might need to add something like this: -->

{% for post in site.posts limit: 5 %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</p>
    {{ post.excerpt }}
    <p><a href="{{ post.url | relative_url }}">Continue reading »</a></p>
  </article>
{% endfor %}
