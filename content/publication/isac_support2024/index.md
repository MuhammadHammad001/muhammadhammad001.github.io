---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enhancing Privilege Architecture Support in RISC-V ISAC
subtitle: ''
summary: ''
authors:
- Muhammad Hammad Bashir
- Umer Shahid
- Allen Baum
- S Pawan Kumar
tags: []
categories:
- RISC-V
# - Architectural Compatibility Testing
date: '2024-06-01'
lastmod: 2025-10-01T19:24:50+05:30
featured: false
draft: false
# links:
#   - name: riscv-isac
#     url: /project/riscv-isac
#   - name: riscv-isac
#     url: /project/riscv-ctg
tags:
  - Poster
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
projects: []

publishDate: '2024'
publication_types:
- '9'
abstract: RISCOF, a Python-based framework, ensures RISC-V processor
  implementations comply with instruction set simulators like Spike and
  Sail. It supports both manual and automated test suite generation via
  RISC-V CTG, with coverage analysis performed through RISC-V ISAC.
  However, the coverage analysis of privilege architectural tests has been
  limited due to incomplete support in RISC-V ISAC. To address this, we
  have introduced new features in RISC-V ISAC specifically for privileged
  architecture, along with a more efficient method for writing coverpoints.
  These enhancements aim to improve compliance testing comprehensively.
publication: '*RISC-V Summit Europe, Munich, Germany*'
url_source: https://riscv-europe.org/summit/2024/posters#:~:text=Enhancing%20Privileged%20Architecture%20Support%20in%20RISC%2DV%20ISAC
url_poster: upload/enhancing_privilege_architecture_riscveusummit24.pdf
url_pdf: upload/Extended_Abstract 9_Enhancing_Priv_ISAC.pdf
url_code: https://github.com/riscv-software-src/riscv-isac/pull/80
# url_slides: https://carrv.github.io/2022/slides/CARRV2022_slides_2_Kumar.pdf
---
