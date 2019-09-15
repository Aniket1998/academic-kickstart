---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Probabilistic Models for Joint Image and Video Generation"
summary: ""
authors: []
tags: ["sophomore"]
categories: []
date: 2019-02-16T02:22:35+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Worked on developing a hierarchical model that first generates a summary frame for the video, and then models individual frames by adding to the summary frame's latent code, sequentially dependent residual vectors conditioned on the summary frame. Further extended this idea to video generation models that disentangle content from dynamics, by adding to the base content representation, a residual vector at each timestep conditioned on the base content vector and the dynamics of the given timestep. We achieved significant improvements over the respective baselines for both video and image generation and the work is currently submitted to the Winter Conference on the Applications of Computer Vision 2020 (WACV 2020)
