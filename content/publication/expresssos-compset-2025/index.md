---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CoMPSeT: A Framework for Comparing Multiparty Session Types'
# subtitle: '...'
summary: 'EXPRESS/SOS@CONFEST 2025'
authors:
- Telmo Ribeiro
- José Proença
- Mário Florido
tags: [Ibex,CAOS,Hybrid Programs]
categories: []
date: '2025-08-25'
lastmod: 2025-08-25T13:38:32+01:00
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
projects: [Ibex]
publishDate: '2025-08-25T12:38:31.978552Z'
publication_types:
- '1'
abstract: ''
links:
    - name: 'Slides'
      url: expresssos-compset-2025-slides.pdf
    - name: 'CoMPSeT tool' 
      url: https://telmoribeiro.github.io/CoMPSeT
# url_slides: slides/ictac20.pdf
# url_code: https://github.com/arcalab/lince
# doi: 10.1007/978-3-030-64276-1_14
publication: 'Proceedings Combined 32nd International Workshop on Expressiveness in Concurrency and 22nd Workshop on Structural Operational Semantics, EXPRESS/SOS 2025, Aarhus, Denmark, 25th August 2025'

---

## Abstract

Concurrent systems are often complex and difficult to design. Choreographic languages, such as Multiparty Session Types (MPST), allow the description of global protocols of interactions by capturing
valid patterns of interactions between participants. Many variations of MPST exist, each one with its
rather specific features and idiosyncrasies. Here we propose a tool – CoMPSeT– that provides clearer
insights over different features in existing MPST. We select a representative set of MPST examples
and provide mechanisms to combine different features and to animate and compare the semantics of
concrete examples. CoMPSeT is open-source, compiled into JavaScript, and can be directly executed
from any browser, becoming useful both for researchers who want to better understand the landscape
of MPST and for teachers who want to explain global choreographies.