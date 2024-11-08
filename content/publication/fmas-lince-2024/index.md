---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Formal Simulation and Visualisation of Hybrid Programs'
subtitle: 'An Extension of a Proof-of-Concept Tool'
summary: 'FMAS@iFM 2024'
authors:
- Pedro Mendes
- Ricardo Correia
- Renato Neves
- José Proença
tags: [Ibex,Route25,Lince,Hybrid Programs]
categories: []
date: '2024-11-11'
lastmod: 2024-11-08T13:38:32+01:00
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
projects: [Ibex,Route25]
publishDate: '2024-11-08T12:38:31.978552Z'
publication_types:
- '1'
abstract: ''
links:
    # - name: 'Slides'
    #   url: slides/ictac20.pdf
    - name: 'Lince tool' 
      url: http://arcatools.org/lince
# url_slides: slides/ictac20.pdf
url_code: https://github.com/arcalab/lince
# doi: 10.1007/978-3-030-64276-1_14
publication: 'Proceedings Sixth International Workshop on Formal Methods for Autonomous Systems, FMAS@iFM 2024, Manchester, UK, 11th-13th of November 2024'

---

## Abstract

Hybrid programs combine digital control with differential equations, and naturally appear in a wide range of application domains, from biology and control theory to real-time software engineering. The entanglement of discrete and continuous behaviour inherent to such programs goes beyond the established computer science foundations, producing challenges related to e.g. infinite iteration and combination of hybrid behaviour with other effects. A systematic treatment of hybridness as a dedicated computational effect has emerged recently. In particular, a generic idealized functional language HybCore with a sound and adequate operational semantics has been proposed. The latter semantics however did not provide hints to implementing HybCore as a runnable language, suitable for hybrid system simulation (e.g. the semantics features rules with uncountably many premises). We introduce an imperative counterpart of HybCore, whose semantics is simpler and runnable, and yet intimately related with the semantics of HybCore at the level of hybrid monads. We then establish a corresponding soundness and adequacy theorem. To attest that the resulting semantics can serve as a firm basis for the implementation of typical tools of programming oriented to the hybrid domain, we present a web-based prototype implementation to evaluate and inspect hybrid programs, in the spirit of GHCi for Haskell and UTop for OCaml. The major asset of our implementation is that it formally follows the operational semantic rules.