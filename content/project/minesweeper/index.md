---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Minesweeper"
subtitle: ""
summary: "Created an agent for taking inference informed actions (based on CSP) to play the game of minesweeper"
authors: []
tags: []
categories: []
date: 2019-10-01T02:01:15-04:00
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
Created an agent to play the game of minesweeper by taking inference informed actions using the following levels of inference:
1. Baseline Inference - Used local knowledge about a cell and its eight immediate neighbors
2. Inference Queue - Used global knowledge from all currently opened cells
3. Constraint Satisfaction Problem - Logically combined more than one clues to deduce new information