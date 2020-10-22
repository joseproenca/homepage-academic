---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Coordination of Tasks on a Real-Time OS
subtitle: ''
summary: 'COORDINATION 2019'
authors:
- Guillermina Cledou
- José Proença
- Bernhard H. C. Sputh
- Eric Verhulst
tags: [DaVinci,Reassure]
categories: []
date: '2019-01-01'
lastmod: 2020-10-10T00:22:33+01:00
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
projects: [DaVinci, Reassure]
publishDate: '2020-10-09T23:22:33.667043Z'
publication_types:
- '1'
abstract: 'VirtuosoNext is a distributed real-time operating system (RTOS) featuring a generic programming model dubbed Interacting Entities. This paper focuses on these interactions, implemented as so-called Hubs. Hubs act as synchronisation and communication mechanisms between the application tasks and implement the services provided by the kernel as a kind of Guarded Protected Action with a well defined semantics. While the kernel provides the most basic services, each carefully designed, tested and optimised, tasks are limited to this handful of basic hubs, leaving the development of more complex synchronization and communication mechanisms up to application specific implementations. In this work we investigate how to support a programming paradigm to compositionally build new services, using notions borrowed from the Reo coordination language, and relieving tasks from coordination aspects while delegating them to the hubs. We formalise the semantics of hubs using an automata model, identify the behaviour of existing hubs, and propose an approach to build new hubs by composing simpler ones. We also provide tools and methods to analyse and simplify hubs under our automata interpretation. In a first experiment several hub interactions are combined into a single more complex hub, which raises the level of abstraction and contributes to a higher productivity for the programmer. Finally, we investigate the impact on the performance by comparing different implementations on an embedded board.'
publication: '*Coordination Models and Languages - 21st IFIP WG 6.1 International
  Conference, COORDINATION 2019, Held as Part of the 14th International Federated
  Conference on Distributed Computing Techniques, DisCoTec 2019, Kongens Lyngby, Denmark,
  June 17-21, 2019, Proceedings*'
url_pdf: https://doi.org/10.1007/978-3-030-22397-7_15
url_code: https://github.com/arcalab/hubAutomata
doi: 10.1007/978-3-030-22397-7_15
---
