---

title: "Joint Image and Video Generation using Residual Vectors"
authors: ["Yatin Dandi", "Aniket Das", "Soumye Singhal", "Piyush Rai", "Vinay P. Namboodiri"]
date: 2019-09-11T07:04:00+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-11T07:04:00+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to the Winter Conference on Applications of Computer Vision 2020"
publication_short: "WACV"

abstract: ""

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

#url_pdf:
#url_code:
#url_dataset:
#url_poster:
#url_project:
#url_slides:
#url_source:
#url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Proposed Approach for Joint Image and Video Generation"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["3wacv"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
We propose a hierarchical model that first generates a summary frame for the video, and then models individual frames by adding to the summary frame's latent code, sequentially dependent residual vectors conditioned on the summary frame. We further extended this idea to video generation models that disentangle content from dynamics, by adding to the base content representation, a residual vector at each timestep conditioned on the base content vector and the dynamics of the given timestep. Currently submitted to *Winter Conference on the Applications of Computer Vision (WACV) 2020*. Pre-print and code will be made public soon
