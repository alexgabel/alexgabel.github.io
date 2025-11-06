---
title: Data-driven Lie Point Symmetry Detection for Continuous Dynamical Systems

authors:
- admin
- Rick Quax
- Efstratios Gavves

date: '2024-03-01'

publishDate: '2025-11-05T19:46:57.652178Z'

publication_types:
- article-journal

publication: '*Machine Learning: Science and Technology*'
publication_short: "*ML: Sci. and Tech.*"

featured: true

hugoblox:
  ids:
    doi: 10.1088/2632-2153/ad2629

abstract: Symmetry detection, the task of discovering the underlying symmetries of
  a given dataset, has been gaining popularity in the machine learning community,
  particularly in science and engineering applications. Most previous works focus
  on detecting ‘canonical’ symmetries such as translation, scaling, and rotation,
  and cast the task as a modeling problem involving complex inductive biases and architecture
  design of neural networks. We challenge these assumptions and propose that instead
  of constructing biases, we can learn to detect symmetries from raw data without
  prior knowledge. The approach presented in this paper provides a flexible way to
  scale up the detection procedure to non-canonical symmetries, and has the potential
  to detect both known and unknown symmetries alike. Concretely, we focus on predicting
  the generators of Lie point symmetries of partial differential equations, more specifically,
  evolutionary equations for ease of data generation. Our results demonstrate that
  well-established neural network architectures are capable of recognizing symmetry
  generators, even in unseen dynamical systems. These findings have the potential
  to make non-canonical symmetries more accessible to applications, including model
  selection, sparse identification, and data interpretability.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- PDEs
- Lie Theory

links:
- type: url
  url: https://doi.org/10.1088/2632-2153/ad2629
# - type: code
#   url: https://github.com/HugoBlox/hugo-blox-builder
# - type: slides
#   url: https://www.slideshare.net/
# - type: dataset
#   url: "#"
# - type: poster
#   url: "#"
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

---
