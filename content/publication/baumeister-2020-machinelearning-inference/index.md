---
# Documentation: https://hugoblox.com/docs/managing-content/

title: Machine-Learning Inference of the Interior Structure of Low-mass Exoplanets
subtitle: ''
summary: ''
authors:
- admin
- Sebastiano Padovan
- Nicola Tosi
- Grégoire Montavon
- Nadine Nettelmann
- Jasmine MacKenzie
- Mareike Godolt
tags: []
categories: []
date: '2020-01-23'
lastmod: 2024-01-16T14:17:06+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-01-16T13:17:06.137644Z'
publication_types:
  - "article-journal"
abstract: "We explore the application of machine-learning based on mixture density neural networks (MDNs) to the 
interior characterization of low-mass exoplanets up to 25 Earth masses constrained by mass, radius, and fluid Love 
number, $k_2$. We create a data set of 900,000 synthetic planets, consisting of an iron-rich core, a silicate mantle,
 a high-pressure ice shell, and a gaseous H/He envelope, to train a MDN using planetary mass and radius as inputs to 
 the network. For this layered structure, we show that the MDN is able to infer the distribution of possible 
 thicknesses of each planetary layer from mass and radius of the planet. This approach obviates the time-consuming task of calculating such distributions with a dedicated set of forward models for each individual planet. While gas-rich planets may be characterized by compositional gradients rather than distinct layers, the method presented here can be easily extended to any interior structure model. The fluid Love number $k_2$ bears constraints on the mass distribution in the planets' interiors and will be measured for an increasing number of exoplanets in the future. Adding $k_2$ as an input to the MDN significantly decreases the degeneracy of the possible interior structures. In an open repository, we provide the trained MDN to be used through a Python Notebook."
publication: '*The Astrophysical Journal*'
doi: 10.3847/1538-4357/ab5d32

url_pdf: 'https://iopscience.iop.org/article/10.3847/1538-4357/ab5d32/pdf'
url_code: "https://github.com/philippbaumeister/MDN_exoplanets"
url_dataset: ''
url_poster: 'https://meetingorganizer.copernicus.org/EGU2020/presentation/EGU2020-7520'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

