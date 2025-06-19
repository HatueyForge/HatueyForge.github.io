---
layout: default
title: Hatuey Forge | Practical ML
---

## Exploring Data, Building Solutions

Welcome to HatueyForge, our space for sharing hands-on projects and insights across **Data Science** and **Applied Artificial Intelligence**. Here, we'll embark on a journey that begins with a specific business need or opportunity (or sometimes just curiosity!), meticulously transforming raw data into meaningful insights and functional solutions.

Our work often involves tackling real-world challenges from concept to deployment. This encompasses not only the technical execution, but also the orchestration of complex project components and the integration of diverse technical efforts required to bring impactful solutions to life. The [Puerto Rico Real Estate Recommender](https://hatueyforge.github.io/prlistingrecommender/) is a prime example of an **end-to-end system**, from data acquisition and processing to a deployed, interactive visualization designed for practical use.

On this blog, you'll find first person account of the development process, technical hurdles encountered, and lessons learned. Our aim is to share practical approaches and functional code that may be helpful to others!

---

### Recent Posts

{% for post in site.posts limit: 5 %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    {{ post.excerpt }}
    <p><a href="{{ post.url | relative_url }}">Read more »</a></p>
  </article>
{% endfor %}

---

**Connect with us:** [GitHub](https://github.com/HatueyForge) | <a href="mailto:HatueyForge@proton.me">Email</a>

<p style="font-size: 0.8em; color: #777; margin-top: 2em;">
    *This site's content and structure were brainstormed and refined with the helpful assistance of AI!*
</p>