---
layout: default # Or 'home' if your chosen theme has a specific 'home.html' layout. 'default' is a safe fallback.
title: Welcome to Hatuey Forge | ML & Data Visualization Blog # Page-specific title. This will override the global title if layout uses it.
---

## Welcome to Hatuey Forge!

Greetings! I'm excited to share my journey and projects at the intersection of **Machine Learning**, **Data Visualization**, and **Geospatial Analytics**. This blog serves as a space to delve into the technical details, challenges, and fascinating insights gleaned from working with data, particularly within the real estate domain.

You'll find posts covering:
*   In-depth tutorials on building interactive data visualizations (like my [Puerto Rico Real Estate Recommender](https://hatueyforge.github.io/prlistingrecommender/)).
*   Explorations of machine learning models applied to real-world datasets.
*   Discussions on geospatial analysis techniques and tools.
*   Tips and tricks for developing with Python, JavaScript, and various data frameworks.

My goal is to demystify complex concepts and share practical approaches that you can adapt for your own projects. Whether you're a fellow data enthusiast, a real estate professional, or just curious about how technology can transform data into actionable insights, I hope you find something valuable here.

---

### Latest Insights & Projects

{% for post in site.posts limit: 5 %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    {{ post.excerpt }}
    <p><a href="{{ post.url | relative_url }}">Read more »</a></p>
  </article>
{% endfor %}

Stay tuned for new articles and project updates!

---

<!--Feel free to connect with me on [LinkedIn](link-to-your-linkedin-profile) or [GitHub](link-to-your-github-profile).-->
