---
title: Branching Pomsets for choreographies – adding choices to pomsets
# subtitle: 
summary: Talk given online in the DCC talks, at the Faculty of Sciences of the University of Porto (FCUP), Portugal
# authors:
# - joseproenca
tags: []
# categories: []
date: "2024-04-15T00:00:00Z"
# lastMod: "2015-05-13T00:00:00Z"
featured: true
draft: false


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects: [Ibex]

links:
    - name: Slides (@DCC-Talks)
      url: slides/bpomsets-dccTalks24.pdf
    - name: Slides (@ICE'23 by Luc)
      url: slides/ice23.pdf
    - name: Slides (@ICE'22 by Luc)
      url: slides/ice22.pdf
    - name: JLAMP'23 paper
      url: publication/edixhoven-branching-2023/edixhoven-branching-2023.pdf
    - name: ICE'22 paper
      url: publication/edixhoven-branching-2022/edixhoven-branching-2022.pdf
    - name: Tool
      url: http://lmf.di.uminho.pt/b-pomset/
---

Choreographic languages describe possible sequences of interactions among a set of agents. Typical models are based on languages or automata over sending and receiving actions. Pomsets provide a more compact alternative by using a partial order to explicitly represent causality and concurrency between these actions. However, pomsets offer no representation of choices, thus a set of pomsets is required to represent branching behaviour. For example, if an agent Alice can send one of two possible messages to Bob three times, one would need a set of 2 × 2 × 2 distinct pomsets to represent all possible branches of Alice’s behaviour. In this talk we propose an extension of pomsets, named branching pomsets, with a branching structure that can represent Alice’s behaviour using 2 + 2 + 2 ordered actions. We encode choreographies as branching pomsets and define well-formedness conditions on branching pomsets, inspired by multiparty session types, which are sufficient to show realisability of the represented communication protocol.

This is joint work with Luc Edixhoven, Sung-Shik Jongmans, and Ilaria Castellani.

## Related artefacts

 - [DCC Seminar](https://www.dcc.fc.up.pt/site/eventos/talks-at-dcc-por-jose-proenca-dcc-fcup-cister)

 - [Slides for this presentation](/slides/bpomsets-dccTalks24.pdf)

 - [Prototype tool](http://lmf.di.uminho.pt/b-pomset/) that implements our theory of branching pomsets

 - [Slides presented at ICE'23 by Luc Edixhoven](/slides/ice23.pdf)

 - [Slides presented at ICE'22 by Luc Edixhoven](/slides/ice22.pdf)

 - [Paper published on JLAMP'23, relating to event structures](/publication/edixhoven-branching-2023/edixhoven-branching-2023.pdf)

 - [Paper published on ICE'22, introducing the formalism](/publication/edixhoven-branching-2022/edixhoven-branching-2022.pdf)

<!-- The slides are available [online](https://docs.google.com/presentation/d/1Preif0pc99FxSlXRImtWv1SHTSXKwG150pDVy9bOWpU/edit?usp=sharing). -->

