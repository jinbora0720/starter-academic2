---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Bag of DAGs: Inferring Directional Dependence in Spatiotemporal Processes"
summary: "Spatial statistics, Nonstationarity"
authors: [Bora Jin, Michele Peruzzi, and David Dunson]
tags: [Spatial statistics, Nonstationarity]
categories: []
date: 2023-01-20T12:55:07-05:00

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
links:
  - name: PDF
    url: https://doi.org/10.48550/arXiv.2112.11870

  - name: Code
    url: https://github.com/jinbora0720/GBAGs
    #icon_pack: fab
    #icon: twitter

  - name: R package
    url: https://github.com/jinbora0720/bags

#url_code: "https://github.com/jinbora0720/GBAGs"
#url_pdf: "https://doi.org/10.48550/arXiv.2112.11870"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

* [Simple example demonstration](/media/BAGs/example.html)

* Propose a class of nonstationary processes that characterize varying directional associations in space and time for point-referenced data.

* Place a prior over possible directional edges within sparse directed acyclic graphs (DAGs), accounting for uncertainty in directional correlation patterns across a domain.

* The resulting Bag of DAGs processes (BAGs) lead to interpretable nonstationarity and scalability for large data due to sparsity of DAGs in the bag.

* Analyze spatiotemporal variability of fine particulate matter (PM2.5) in California, US, in which a directed edge represents a prevailing wind direction causing some associated covariance in the pollutants.
