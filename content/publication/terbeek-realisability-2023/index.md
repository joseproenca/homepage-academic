---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Realisability of Global Models of Interaction
subtitle: ''
summary: 'ICTAC 2023'
authors:
- M. H. ter Beek
- R. Hennicker
- J. Proença
tags: [VALU3S,Route25,Ibex]
categories: []
date: '2023-12-04'
lastmod: 2023-10-06T10:45:00+01:00
featured: true
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
links:
    - name: Extended version
      url: https://doi.org/10.5281/zenodo.8377188
    - name: Online tool
      url: https://lmf.di.uminho.pt/ceta
    - name: ICTAC'23
      url: https://ictac2023.compsust.utec.edu.pe
    - name: Slides
      url: slides/ictac23.pdf
projects: [VALU3S,Route25,Ibex]
publishDate: '2023-10-04T09:44:59.922602Z'
publication_types:
- '1'
abstract: ''
publication: '*ICTAC - 20th International Colloquium on Theoretical Aspects of Computing, Lima, Peru, December 4-8, 2023, Proceedings*'
---

## Abstract

We consider global models of communicating agents specified as transition systems labelled by interactions in which multiple senders and receivers can participate. A realisation of such a model is a set of local transition systems—one per agent—which are executed concurrently using synchronous communication. Our core challenge is how to check whether a global model is realisable and, if it is, how to synthesise a realisation. We identify and compare two variants to realise global interaction models, both relying on bisimulation equivalence. Then we investigate, for both variants, realisability conditions to be checked on global models. We propose a synthesis method for the construction of realisations by grouping locally indistinguishable states. The paper is accompanied by a tool that implements realisability checks and synthesises realisations.
