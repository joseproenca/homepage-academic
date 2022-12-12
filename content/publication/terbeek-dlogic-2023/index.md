---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Can we Communicate? Using Dynamic Logic to Verify Team Automata
subtitle: ''
summary: 'FM 2023'
authors:
- Maurice H. ter Beek
- Guillermina Cledou
- Rolf Hennicker
- José Proença
tags: [Ibex,VALU3S,Variability,Automata]
categories: []
date: '2023-03-06'
lastmod: 2022-12-12T09:51:38Z
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
projects: [Ibex,VALU3S]
publishDate: '2022-12-12T09:51:25.220589Z'
publication_types:
- '1'
links:
    - name: Tech. Report
      url: https://doi.org/10.5281/zenodo.7418074
    - name: Online tool
      url: http://arcatools.org/feta
    - name: FM'23
      url: https://fm2023.isp.uni-luebeck.de
abstract: 'Team automata describe networks of automata with input and output actions, extended with synchronisation policies guiding how many interacting components can synchronise on a shared input/output action. Given such a team automaton, we can reason over communication properties such as receptiveness (sent messages must be received) and responsiveness (pending receives must be satisfied). Previous work focused on how to identify these communication properties. However, automatically verifying these properties is non-trivial, as it may involve traversing networks of interacting automata with large state spaces. This paper investigates (1) how to characterise communication properties for team automata (and subsumed models) using test-free propositional dynamic logic, and (2) how to use this characterisation to verify communication properties by model checking. A prototype tool supports the theory, using a transformation to interact with the mCRL2 tool for model checking.'
publication: '*Formal Methods - 25th international symposium, FM 2023, Lübeck, Germany,
  March 6-10, 2023, Proceedings*'
---
