---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Animating Rebeca'
subtitle: ''
summary: 'Marjan Festscrhift@FSEN 2025'
authors:
- Maurice ter Beek
- José Proença
tags: [Route25,CAOS]
categories: []
date: '2025-04-08'
lastmod: 2025-01-22T13:38:32+01:00
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
projects: [Route25]
publishDate: '2025-04-08T12:38:31.978552Z'
publication_types:
- '1'
abstract: ''
links:
    - name: 'RebeCaos tool' 
      url: https://fm-dcc.github.io/rebecaos
# url_slides: slides/ictac20.pdf
url_code: https://github.com/fm-dcc.github.io/rebecaos
# doi: 10.1007/978-3-030-64276-1_14
publication: 'Proceedings of Marjan Festscrhift @ FSEN 2025, Västerås, Sweden, 9th of November 2025'

---

## Abstract

Rebeca is 20+ years old. Introduced by Marjan Sirjani and colleagues for modelling and analysing actor-based systems, it comes with a variety of tool support, including dedicated model checkers, simulators, and code generators.
When encountering Rebeca for the first time, either as a student, as a researcher, or as a practitioner from industry, one needs to grasp the subtleties of Rebeca's semantics, which includes variants with probabilities and time.

This paper presents a user-friendly web-based front-end, based on the Caos library for Scala, to animate different operational semantics of (timed) Rebeca. This can facilitate the dissemination and awareness of Rebeca, provide insights into the differences among existing semantics, and support quick experimentation of new variants (e.g., when the order of received messages is preserved). The tool is illustrated by means of a ticket service use case from the literature.