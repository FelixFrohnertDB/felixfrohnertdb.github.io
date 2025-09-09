---
layout: page
title: Podcast
description: Discussing my work on predicting emergent research directions
img: assets/img/Spotify.jpg
importance: 2
category: outreach
related_publications: true
---

I recently joined in the Physics World Weekly podcast to discuss whether artificial intelligence can be used to predict future directions in quantum science research.

<iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/episode/5nrKxwOjyHjM2b4KCA8x2X?utm_source=generator&theme=0" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

The discussion is based on one of my recent publications {% cite frohnert2025discovering %}.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/overPred.png" title="Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview:
    (a) We analyze a dataset of $66,839$ papers with the quant-ph identifier on arXiv, spanning from $1994$ to $2023$. 
    From these papers, we extract $10,235$ quantum physics-related concepts.
    (b) Using the abstracts of these papers, we train an embedding model to capture the evolving relationships between these concepts in vector representations over time. 
    In the visualization, gray dots indicate changes in the embedding model’s weights over the years, while the hues of orange, cyan, and red represent the dynamics of word embeddings' parameters as they change with time.
    (c) The task involves training a machine learning model to predict which currently unconnected concepts (those not yet studied together) are likely to co-occur in the near future, based on the learned embeddings.
</div>