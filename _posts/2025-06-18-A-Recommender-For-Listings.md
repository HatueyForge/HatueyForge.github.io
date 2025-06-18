---
layout: post
title: "Listing Recommendations and Rankings"
date: 2025-06-18 18:00:00 -0400 # Adjust timezone
categories: [webdev, github-pages, data-viz]
tags: [map, visualization, embed, google-analytics]
---

Here's the end result - a map showing listing recommendations for different types of potential buyers:
<iframe src="https://hatueyforge.github.io/prlistingrecommender/" width="100%" height="600px" frameborder="0" allowfullscreen></iframe>

The listings are recommended using a two-tower recommender system I built using pytorch, and the recommender is a multi-layer perceptron that also uses the pytorch framework.

Here I'll describe in more detail how I built it.

