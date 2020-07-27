---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Bayesian hunting"
subtitle: ""
summary: "Used Bayesian inference for tracking the location of a target hidden in a multi-terrain landscape"
authors: []
tags: []
categories: []
date: 2019-11-01T02:01:15-04:00
lastmod: 2020-06-25T02:01:15-04:00
featured: false
draft: false

#external_link: "https://github.com/mareeshissar" 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Image credit: [**W. Cowan**](https://www.cs.rutgers.edu/~cwcowan/)"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Used Bayesian inference for tracking the location of a target hidden in a multi-terrain landscape by using the following rules:
1. Searching the cell with the highest probability of finding the target
2. Searching the cell with the highest probability of containing the target
