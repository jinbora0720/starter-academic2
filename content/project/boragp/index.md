---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Spatial Predictions on Physically Constrained Domains: Applications to Arctic Sea Salinity Data"
summary: "Spatial statistics, Nonstationarity"
authors: [Bora Jin, Amy H. Herring, and David Dunson]
tags: [Spatial statistics, Nonstationarity]
categories: []
date: 2023-01-20T12:55:05-05:00

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
    url: https://doi.org/10.48550/arXiv.2210.03913

  - name: Code
    url: https://github.com/jinbora0720/boraGP-sss
    #icon_pack: fab
    #icon: twitter

  - name: R package
    url: https://github.com/jinbora0720/boraGP

#url_code: "https://github.com/jinbora0720/boraGP-sss"
#url_pdf: "https://doi.org/10.48550/arXiv.2210.03913"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

* Motivated by applications in point-referenced geostatistics that have measurements collected and meaningful only within a constrained domain.

* Develop the Barrier Overlap-Removal Acyclic directed graph GP (BORA-GP), a scalable GP method that incorporates the constrained domain via sparsity-inducing DAGs.  

* Enable characterization of dependence in constrained domains by removing an edge in a DAG if a linear path between two points overlaps physical barriers.

* Analyze sea surface salinity in the Arctic Ocean.
