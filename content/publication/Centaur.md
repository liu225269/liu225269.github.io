---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
abstract: "Due to the high density storage demand coming from applications from different domains, 3D NAND flash is becoming a promising candidate to replace 2D NAND flash as the dominant non-volatile memory. However, denser 3D NAND presents various performance and reliability issues, which can be addressed by the 3D NAND specific full-sequence program (FSP) operation. The FSP programs multiple pages simultaneously to mitigate the performance degradation caused by the long latency 3D NAND baseline program operations. However, the FSP-enabled 3D NAND-based SSDs introduce lifetime degradation due to the larger write granularities accessed by the FSP. To address the lifetime issue, in this paper, we propose and experimentally evaluate Centaur, a heterogeneous 2D/3D NAND heterogeneous SSD, as a solution. Centaur has three main components: a lifetime-aware inter-NAND request dispatcher, a lifetime-aware inter-NAND work stealer, and a data migration strategy from 2D NAND to 3D NAND. We used twelve SSD workloads to compare Centaur against a state-of-the-art 3D NAND-based SSD with the same capacity. Our experimental results indicate that the SSD lifetime and performance are improved by 3.7x and 1.11x, respectively, when using our 2D/3D heterogeneous SSD."
title: "Centaur: A Novel Architecture for Reliable, Low-Wear, High-Density 3D NAND Storage, In Proceedings of the ACM on Measurement and Analysis of Computing Systems (POMACS Journal) (SIGMETRICS'20)"
subtitle: ""
summary: ""
authors: [Chun-Yi Liu, Jagadish B. Kotra, Myoungsoo Jung, Mahmut T. Kandemir]
tags: []
categories: [storage]
url_pdf: pdf/Centaur.pdf
date: 2020-08-25T21:50:07-04:00
lastmod: 2020-08-25T21:50:07-04:00
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
