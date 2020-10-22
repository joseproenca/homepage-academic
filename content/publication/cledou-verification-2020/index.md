---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Verification of Real-Time Coordination in VirtuosoNext (extended version)
subtitle: ''
summary: ''
authors:
- Guillermina Cledou
- José Proença
- Bernhard H.C. Sputh
- Eric Verhulst
tags:
- 'Compositional semantics'
- 'Coordination'
- 'Real-time OS'
- 'Timed automata'
- 'Uppaal'
- DaVinci
- Reassure
- VALU3S
categories: []
date: '2020-05-01'
lastmod: 2020-10-22T13:58:20+01:00
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
projects:
- DaVinci
- Reassure
- VALU3S
publishDate: '2020-10-22T12:58:20.137961Z'
publication_types:
- '4'
abstract: VirtuosoNextTM is a distributed real-time operating system (RTOS) featuring
  a generic programming model dubbed Interacting Entities. This paper focuses on these
  interactions, implemented as so-called Hubs. Hubs act as synchronisation and communication
  mechanisms between the application tasks and implement the services provided by
  the kernel as a kind of Guarded Protected Action with a well defined semantics.
  While the kernel provides the most basic services, each carefully designed, tested
  and optimised, tasks are limited to this handful of basic hubs, leaving the development
  of more complex mechanisms up to application specific implementations. In this work
  we investigate how to support a programming paradigm to compositionally build new
  services, using notions borrowed from the Reo coordination language, and relieving
  tasks from coordination aspects while delegating them to the hubs. We formalise
  the semantics of hubs using an automata model with notions of dataflow and time,
  identify the behaviour of existing hubs, and propose an approach to build new hubs
  by composing simpler ones. We also provide open-source tools and methods to analyse
  and verify hubs under our automata interpretation, including time-sensitive behaviour
  via the Uppaal model checker, usable on http://arcatools.org/hubs. In a first experiment
  several hub interactions are combined into a single more complex hub, which raises
  the level of abstraction and contributes to a higher productivity for the programmer.
  We illustrate the proposed tools and methods by verifying key properties on different
  interaction scenarios between tasks and the specified hub. Finally, we investigate
  the impact on the performance by comparing different implementations on an embedded
  board.
publication: ''
url_pdf: https://zenodo.org/record/3818020
doi: 10.5281/ZENODO.3818020
---
