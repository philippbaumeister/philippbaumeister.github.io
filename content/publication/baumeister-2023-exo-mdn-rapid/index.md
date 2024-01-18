---
# Documentation: https://hugoblox.com/docs/managing-content/

title: 'ExoMDN: Rapid characterization of exoplanet interior structures with mixture density networks'
subtitle: ''
summary: 'We present ExoMDN, a machine-learning model for the interior 
characterization of exoplanets. The model is trained on a large dataset of 
more than 5.6 million synthetic planets. Given mass, radius, and equilibrium temperature, ExoMDN can deliver a full 
planetary interior inference in under a second. ExoMDN is freely accessible online, including the training routines.'
authors:
  - admin
  - Nicola Tosi
tags:
  - ''
categories: [ ]
date: '2023-08-17'
lastmod: 2024-01-16T14:17:07+01:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Smart'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [ ]
publishDate: '2024-01-16T13:17:06.898646Z'
publication_types:
  - 'article-journal'
abstract: '<br> *Aims.* Characterizing the interior structure of exoplanets is essential for understanding their 
diversity, formation, and evolution. As the interior of exoplanets is inaccessible to observations, an inverse problem must be 
solved, where numerical structure models need to conform to observable parameters such as mass and radius. This is a 
highly degenerate problem whose solution often relies on computationally-expensive and time-consuming inference 
methods such as Markov Chain Monte Carlo.</br> <br>*Methods.* We present ExoMDN, a machine-learning model for the interior 
characterization of exoplanets based on Mixture Density Networks (MDN). The model is trained on a large dataset of 
more than 5.6 million synthetic planets below 25 Earth masses consisting of an iron core, a silicate mantle, a water 
and high-pressure ice layer, and a H/He atmosphere. We employ log-ratio transformations to convert the interior 
structure data into a form that the MDN can easily handle.</br> 
<br>*Results.* Given mass, radius, and equilibrium temperature, we show that ExoMDN can deliver a full posterior 
distribution of mass fractions and thicknesses of each planetary layer in 
under a second on a standard Intel i5 CPU. Observational uncertainties can be easily accounted for through repeated 
predictions from within the uncertainties. We use ExoMDN to characterize the interior of 22 confirmed exoplanets 
with mass and radius uncertainties below 10% and 5% respectively, including the well studied GJ 1214 b, GJ 486 b, 
and the TRAPPIST-1 planets. We discuss the inclusion of the fluid Love number $k_2$ as an additional (potential) 
observable, showing how it can significantly reduce the degeneracy of interior structures. Utilizing the fast 
predictions of ExoMDN, we show that measuring $k_2$ with an accuracy of 10% can constrain the thickness of core and 
mantle of an Earth analog to around 13% of the true values.</br>'
publication: '*Astronomy & Astrophysics*'
doi: 10.1051/0004-6361/202346216

url_code: 'https://github.com/philippbaumeister/exomdn'
url_dataset: 'https://cdsarc.cds.unistra.fr/viz-bin/cat/J/A+A/676/A106'
url_pdf: 'https://www.aanda.org/articles/aa/pdf/2023/08/aa46216-23.pdf'
---
