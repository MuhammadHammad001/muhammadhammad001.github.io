---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Comprehensive Verification of the RISC-V Memory Management Unit: Challenges and Solutions'
subtitle: ''
summary: ''
authors:
- Huda Sajjad
- Muhammad Hammad Bashir
- Yazan Hussnain
- Fatima Saleem
tags: []
categories:
- RISC-V
# - Architectural Compatibility Testing
date: '2025-04-01'
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

publishDate: '2025'
publication_types:
- '9'
abstract: The Memory Management Unit (MMU), critical for virtual memory translation and protection, demands rigorous verification due to its inherent complexity. This work details a two-step methodology to ensure MMU compliance with RISC-V Privileged ISA specification. First, a test suite was developed using the RISCOF framework, leveraging RISC-V ISAC for coverage analysis. Second, the suite was executed on the OpenHW Core-V Wally processor, employing ImperasDV as a reference model and riscvISACOV for functional coverage development. This approach identified a critical architectural bug in Core-V Wally’s MMU implementation, demonstrating the methodology’s effectiveness in validating memory management units.
publication: '*RISC-V Summit Europe, Paris, France*'
url_source: https://riscv-europe.org/summit/2025/posters#:~:text=Comprehensive%20Verification%20of%20the%20RISC%2DV%20Memory%20Management%20Unit%3A%20Challenges%20and%20Solutions
url_poster: upload/mmu_verif2025/MMU_Poster.pdf
url_pdf: upload/MMU_Verification.pdf
---
