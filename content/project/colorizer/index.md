---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Colorizer"
subtitle: ""
summary: "Generated colourized version of a grayscale image using K-means clustering and Artificial Neural Network"
authors: []
tags: []
categories: []
date: 2019-12-01T02:16:59-04:00
lastmod: 2020-06-25T02:16:59-04:00
featured: false
draft: false


#external_link: "https://github.com/mareeshissar" 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
- Generated colorized version of a grayscale image (240 pixels X 420 pixels) using K-means clustering and Artificial Neural Network
- Explored K-means clustering algorithm to reduce the color palette of the image from 16777216 possible combinations to 29 most dominant colors
- Implemented a two Layer Artificial Neural Network consisting of 60 nodes with sigmoid activation function in the hidden layer and softmax activation function in the output layer
- Resolved ambiguity present in mapping multiple RGB values to a single grayscale value by taking a 3 X 3 window of pixels to make use of the contextual information present around a single grayscale pixel