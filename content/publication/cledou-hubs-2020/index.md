---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Hubs for VirtuosoNext: Online verification of real-time coordinators'
subtitle: ''
summary: 'SCP 2020'
authors:
- Guillermina Cledou
- José Proença
- Bernhard H. C. Sputh
- Eric Verhulst
tags: [DaVinci, Reassure, PReFECT, VALU3S]
categories: []
date: '2020-11-02'
lastmod: 2020-11-02T00:10:00+01:00
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
projects: [DaVinci, Reassure, PReFECT, VALU3S]
publishDate: '2020-11-02T10:00:00.446263Z'
publication_types:
- '2'
abstract: ''
publication: '*Science of Computer Programming*'
url_pdf: https://doi.org/10.1016/j.scico.2020.102566
url_code: https://github.com/arcalab/hubAutomata
doi: 10.1016/j.scico.2020.102566
---

## Abstract
VirtuosoNext is a distributed real-time operating system (RTOS) fea- turing a generic programming model dubbed Interacting Entities. This pa- per focuses on these interactions, implemented as so-called Hubs. Hubs act as synchronisation and communication mechanisms between the application tasks and implement the services provided by the kernel. While the kernel provides the most basic services, each carefully designed, tested and opti- mised, tasks are limited to this handful of basic hubs, leaving the development of more complex mechanisms up to application specific implementations.

This work presents a toolset that supports the building of new services compositionally, using notions borrowed from the Reo coordination language, on which the developer can delegate coordination-related duties. This toolset uses a formal compositional semantics for hubs that captures dataflow and time, formalising the behaviour of existing hubs, and allowing the defini- tion of new ones. Furthermore, it enables the analysis and verification of hubs under our automata interpretation, including time-sensitive behaviour via the Uppaal model checker, usable on http://arcatools.org/hubs. We illustrate the proposed tools and methods by verifying key properties on different interaction scenarios between tasks and a composed hub.

__Keywords:__ Coordination, Uppaal, Real-time OS, Compositional semantics
