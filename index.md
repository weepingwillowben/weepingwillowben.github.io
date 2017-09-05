---
title: "Splash Page"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
excerpt: "hi there."
intro:
  - excerpt: 'hi there again'
feature_row1:
  - image_path: images/home/code_screen.png
    alt: "code pic"
    title: "Coding posts"
    excerpt: 'Posts that walk through intermediate coders of how to think through more complex problems'
    url: "coding_posts"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row2:
  - image_path: images/home/cityscreen.png
    alt: "intelligent algorithm image"
    title: "Intelligence ideas"
    excerpt: 'Papers that explain my ideas of intelligence and how they can be implemented. For a more advanced audience interested in AI.'
    url: "exploration_intelligence"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row3:
  - image_path: images/home/neural_nets.png
    alt: "neural nets dynamics graph"
    title: "Intuition behind neural networks"
    excerpt: 'Showing how ideas from different parts of math, neuroscience, phycology, philosophy, and computer science come together to form the ideas behind neural networks. Theory and implementations.'
    url: "neural_posts"
    btn_label: "Read More"
    btn_class: "btn--inverse"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}