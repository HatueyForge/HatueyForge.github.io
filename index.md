---
layout: default
title: Hatuey Forge | Data & AI Projects
---

## Exploring Data, Building AI Solutions

Hello, World! Welcome to HatueyForge, our space for sharing hands-on projects and insights from the realms of **Data Science** and **Applied Artificial Intelligence**. Here, we embark on a journey that begins with a specific business need or opportunity (or just curiosity!), transforming raw data into meaningful insights and functional solutions.

We keep in mind, and will comment upon, real-world challenges in taking a prokect from concept to deployment. This often encompasses not only the technical execution, but also evaluating and choosing a technology stack, orchestrating of complex project components and the integration of diverse technical efforts to bring impactful solutions to life. For instance, the [Puerto Rico Real Estate Recommender](https://hatueyforge.github.io/prlistingrecommender/) is an example of an **end-to-end system**, from data acquisition and processing to a deployed, interactive visualization designed for practical use. While geospatial analysis is a fascinating part of our interests, we will also explore diverse applications, such as building robust classification models for complex datasets or developing recommender systems for various industries.

On this blog, you'll find an honest look at the development process, the technical hurdles encountered, and the lessons learned. Our aim is to share practical approaches and functional code that may be helpful to others.

Our posts will cover these areas:

*   **Applied Machine Learning:** Building and deploying models to address specific challenges.
*   **Data Pipelines & Engineering:** AI models need data, here we'll see the journey it takes from source to solution.
*   **Data Visualization:** If humans will make decisions based on AI recommendations, clear and interactive ways to understand data are essential.
*   **System Design & Deployment:** Can we get out a minimum viable prototype? What about scaling? Bridging the gap from prototype to usable application.
*   **Machine Learning Foundations & Customization:** Frameworks and libraries have plenty of pre-built components, but we need to understand what's going on to troubleshoot or extend them. Deep dives into algorithms, loss functions, optimization techniques, and advanced model tuning.

---

### Recent Posts

<!-- IMPORTANT: Many Jekyll themes will automatically display a list of your latest blog posts
     on the homepage when you use a layout like 'default' or 'home'.
     You might NOT need the Liquid code below.

     However, if your theme does NOT automatically list posts, you can uncomment
     and use the following Liquid code to display recent articles. -->

{% comment %}
{% for post in site.posts limit: 5 %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    {{ post.excerpt }}
    <p><a href="{{ post.url | relative_url }}">Read more »</a></p>
  </article>
{% endfor %}
{% endcomment %}

---

**Connect with us:** [GitHub](https://github.com/HatueyForge) | <a href="mailto:HatueyForge@proton.me">Email</a>

<p style="font-size: 0.8em; color: #777; margin-top: 2em;">
    *This site's content and structure were brainstormed and refined with the helpful assistance of AI.*
</p>
