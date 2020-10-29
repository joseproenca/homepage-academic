---
title: Formal Software on ArcaTools
# subtitle: 
summary: Set of online formal analysis tools (http://arcatools.org) developed together with [Arca](http://arca.di.uminho.pt) members, within the [DaVinci](http://davinci.di.uminho.pt) and [KLEE](http://klee.di.uminho.pt) projects.
# authors:
# - joseproenca
tags: []
# categories: []
date: "2020-10-01T00:00:00Z"
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
projects: [DaVinci,Klee]
---

[ArcaTools](http://arcatools.org) is a framework to bring to the web a collection of tools, decreasing the time to start experimenting with existing tools, while exploiting the interactivity and visualisation capabilities of existing web technologies. Developed mainly by members of ARCA.

All tools follow the following approach:

- Back-end developed mainly in Scala, resorting to other independent projects;
- JavaScript code generated when possible, some parts executed on our servers when needed;
- 3rd party tools are linked internally, such as: [mCRL2](https://mcrl2.org), [UPPAAL](http://uppaal.org), and [SageMath](https://www.sagemath.org);
- All code is open-source and available.

You can find experiment the tools and find the associated resources online:

### {{< icon name="globe" pack="fas">}}[http://arcatools.org](http://arcatools.org)

<p style="padding-top: 20px;">
Some of the featured tools include:
</p>

- An analyser and verifier of families of Reo connectors, based on traced monoidal symmetric categories - http://arcatools.org/preo.

- A simulator of deterministic hybrid programs using algebraic calculations instead of approximate values - http://arcatools.org/#lince.

 - An analyser of coordinating Hubs in the context of a RTOS - http://arcatools.org/hubs.
