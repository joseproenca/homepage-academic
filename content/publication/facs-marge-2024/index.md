---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Reactive graphs in action
subtitle: ''
summary: 'FACS 2024'
authors:
- David Tinoco
- Manuel A. Martins
- Alexandre Madeira
- José Proença
tags: [Ibex]
categories: []
date: '2024-09-06'
lastmod: 2024-09-06T00:10:00+01:00
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
publishDate: '2024-09-06T10:00:33.832862Z'
publication_types:
- '1'
abstract: ''
publication: '*Formal Aspects of Component Software - 20th International Conference, FACS 2024, Milan, Italy, September 9-10, 2024, Revised Selected Papers*'
# url_pdf: https://doi.org/10.1007/...
url_code: https://github.com/fm-dcc/marge
links:
  - name: Marge tool
    url: https://fm-dcc.github.io/MARGe
  - name: Tutoral video (by David Tinoco)
    url: https://www.dropbox.com/scl/fo/cm0tw42zlebqqzh7s054a/h?rlkey=urd0z5ern6akgkc3l8dqq8l7c&e=1&st=iu6c3xs5&dl=0
  - name: Slides
    url: SlidesFACS24.pdf
  - name: DOI
    url: https://doi.org/10.1007/978-3-031-71261-6_6
# url_slides: https://docs.google.com/presentation/...
# url_slides: SlidesFACS24.pdf
# doi: 10.1007/978-3-031-71261-6_6
---

_Reactive graphs_ are transition structures whereas edges become active and inactive during its evolution, that were introduced by Dov Gabbay from a mathematical’s perspective. This paper presents __Marge__ (https://fm-dcc.github.io/MARGe), a web-based tool to visualise and analyse reactive graphs enriched with labels. __Marge__ animates the operational semantics of reactive graphs and offers different graphical views to provide insights over concrete systems. We motivate the applicability of reactive graphs for adaptive systems and for featured transition systems, using __Marge__ to tighten the gap between the existing theoretical models and their usage to analyse concrete systems.