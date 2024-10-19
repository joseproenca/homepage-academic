---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The CAOS framework for Scala: computer-aided design of SOS'
subtitle: ''
summary: 'SCP 2024'
authors:
- José Proença
- Luc Edixhoven
tags: [Ibex,Route25]
categories: []
date: '2024-10-18'
lastmod: 2024-10-18T00:10:00+01:00
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
publishDate: '2024-10-19T10:00:00.446263Z'
publication_types:
- '2'
abstract: ''
publication: '*Science of Computer Programming*'
url_pdf: https://doi.org/10.1016/j.scico.2024.103222
url_code: https://github.com/arcalab/caos
doi: 10.1016/j.scico.2024.103222
---

## Abstract
We present Caos: a programming framework for computer-aided design of structural operational semantics for formal models. This framework includes a set of Scala libraries and a workflow to produce visual and interactive diagrams that animate and provide insights over the structure and the semantics of a given abstract model with operational rules.

Caos follows an approach where theoretical foundations and a practical tool are built together, as an alternative to foundations-first design ("tool justifies theory") or tool-first design ("foundations justify practice"). The advantage of Caos is that the tool-under-development can immediately be used to automatically run numerous and sizeable examples in order to identify subtle mistakes, unexpected outcomes, and unforeseen limitations in the foundations-under-development, as early as possible.

More concretely, Caos supports the quick creation of interactive websites that help the end-users better understand a new language, structure, or analysis. End-users can be research colleagues trying to understand a companion paper or students learning about a new simple language or operational semantics. We include a list of open-source projects with a web frontend supported by Caos that are used both in research and teaching contexts.

__Keywords:__ visualisation, structural operational semantics, formal methods, web-frontend, pedagogical tools
