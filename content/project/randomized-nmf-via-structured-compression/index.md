---
title: Randomized NMF via Structured Compression
summary: How to fasten an already fast NMF algorithm.
tags:
- Signal Processing
date: 

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/faroya/Faster-than-Fast-NeNMF"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Random projections have been recently implemented in Nonnegative Matrix Factorization (NMF) to speed-up the NMF computations, with a negligible loss of performance. In this paper, we investigate the effects of such projections when the NMF technique uses the fast Nesterov gradient descent (NeNMF). We experimentally show that structured random projections significantly speed-up NeNMF for very large data matrices.
