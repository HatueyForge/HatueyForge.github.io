---
layout: post
title: "Listing Recommendations and Rankings"
date: 2025-06-18 18:00:00 -0400 # Adjust timezone
categories: [webdev, github-pages, data-viz]
tags: [map, visualization, embed, google-analytics]
---

Here's the end result - a map showing listing recommendations for different types of potential buyers:

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe src="https://hatueyforge.github.io/prlistingrecommender/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allowfullscreen></iframe>
</div>

The listings are recommended using a two-tower recommender system I built using pytorch, and the recommender is a multi-layer perceptron that also uses the pytorch framework.

Here I'll describe in more detail how I built it.

