---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Asynchronous Team Automata
subtitle: 'Best-artifact award'
summary: 'FM 2026'
authors:
- Davide Basile
- Maurice H. ter Beek
- José Proença
tags: [POISE,Automata]
categories: []
date: '2026-05-18'
lastmod: 2026-02-21T10:03:49+01:00
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
projects: [POISE]
publishDate: '2026-02-21T09:03:49.217253Z'
links:
    - name: Online tool
      url: http://fm-dcc.github.io/a-team
    - name: FM'26
      url: https://conf.researchr.org/home/fm-2026
    - name: Artefact
      url: https://doi.org/10.5281/zenodo.18601856
# doi: 10.1007/...
publication_types:
- '1'
abstract: 'Team automata were introduced as a flexible extension of I/O automata to model collaborative behaviour in component-based and distributed systems. Their distinctive features include multi-party communication and a liberal synchronisation mechanism: components may jointly execute shared actions according to synchronisation policies that specify which subsets of components participate as senders or receivers. While this makes team automata well suited for modelling coordination, existing communication is synchronous and therefore insufficient for capturing certain behavioural aspects (e.g., due to message reordering) of modern networks and distributed systems, in which communication is typically asynchronous and message delays are unpredictable. In this paper, we introduce asynchronous team automata (ATeams), which extend team automata with buffers to model asynchronous communication, in addition to conventional synchronous interaction. ATeams support individual interactions involving multiple senders and receivers, unlike well-known asynchronous models such as communicating finite-state machines and multi-party session types. We formalise the syntax and operational semantics of ATeams, study well-formedness and well-behavedness conditions, and present the prototypical A-Team tool that supports specification, animation and automated checks. This proposes ATeams as a unifying semantic foundation for modelling and analysis of heterogeneous synchronous–asynchronous multi-party interactions.'
publication: '*Formal Methods - 27th international symposium, FM 2026, Tokyo, Japan,
  May 18-22, 2026, Proceedings*'
---
