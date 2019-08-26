---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
abstract: "NAND-based solid-state disks (SSDs) are known for their superior random read/write performance due to the high degrees of multi-chip parallelism they exhibit. Currently, as the chip density increases dramatically, fewer 3D NAND chips are needed to build an SSD compared to the previous generation chips. As a result, SSDs can be made more compact. However, this decrease in the number of chips also results in reduced overall throughput, and prevents 3D NAND high density SSDs from being widely-adopted. We analyzed 600 storage workloads, and our analysis revealed that the small read operations suffer significant performance degradation due to reduced chip-level parallelism in newer 3D NAND SSDs. The main question is whether some of the inter-chip parallelism lost in these new SSDs (due to the reduced chip count) can be won back by enhancing intra-chip parallelism. Motivated by this question, we propose a novel SOML (Single-Operation-Multiple-Location) read operation, which can perform several small intra-chip read operations to different locations simultaneously, so that multiple requests can be serviced in parallel, thereby mitigating the parallelism-related bottlenecks. A corresponding SOML read scheduling algorithm is also proposed to fully utilize the SOML read. Our experimental results with various storage workloads indicate that, the SOML read-based SSD with 8 chips can outperform the baseline SSD with 16 chips."
title: "SOML read: Rethinking the Read Operation Granularity of 3D NAND SSDs, The 24th ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS'19)"
subtitle: ""
summary: ""
authors: [Chun-Yi Liu, Jagadish B. Kotra, Myoungsoo Jung, Mahmut T. Kandemir, Chita R. Das]
tags: []
categories: [storage]
url_pdf: pdf/SOML.pdf
date: 2019-08-25T21:50:07-04:00
lastmod: 2019-08-25T21:50:07-04:00
featured: false
draft: false

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
