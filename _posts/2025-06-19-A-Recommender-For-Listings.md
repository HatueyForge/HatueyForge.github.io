---
layout: post
title: "Generate and Visualize Real Estate Recommendations"
date: 2025-06-19 11:00:00 -0400 # Adjust timezone
categories: [webdev, github-pages, data-viz]
tags: [map, visualization, embeddings, pytorch, recommendation systems]
---

Let's start with the end result - a map showing listing recommendations for different types of potential buyers:

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe src="https://hatueyforge.github.io/prlistingrecommender/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" frameborder="0" allowfullscreen></iframe>
</div>

Whole-page map at: [Puerto Rico Real Estate Recommender](https://hatueyforge.github.io/prlistingrecommender/)

The listings are recommended using a two-tower recommender system and ranked with a multi-layer perceptron implemented using the PyTorch deep learning framework.

Here I'll describe in more detail how I built it! I'll probably split this into several posts...