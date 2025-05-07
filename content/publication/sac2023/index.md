---
title: 'Fast and Efficient Hardware Implementation of HQC'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanjay Deshpande
  - Chuanqi Xu
  - Mamuri Nawan
  - Kashif Nawaz
  - Jakub Szefer

# Author notes (optional)
author_notes:
  - 
  - 
  -
  - 
  - 
  - 
  - 

date: '2023-08-14T00:00:00Z'
doi: '10.1007/978-3-031-53368-6_15'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Selected Areas in Cryptography – SAC 2023: 30th International Conference
publication_short: SAC 2023

abstract: This work presents a hardware design for constant-time implementation of the HQC (Hamming Quasi-Cyclic) code-based key encapsulation mechanism. HQC has been selected for the fourth round of NIST's Post-Quantum Cryptography standardization process and this work presents the first, hand-optimized design of HQC key generation, encapsulation, and decapsulation written in Verilog targeting implementation on FPGAs. The three modules further share a common SHAKE256 hash module to reduce area overhead. All the hardware modules are parametrizable at compile time so that designs for the different security levels can be easily generated. The design currently outperforms the other hardware designs for HQC, and many of the fourth-round Post-Quantum Cryptography standardization process, with one of the best time-area products as well. For the combined HighSpeed design targeting the lowest security level, we show that the HQC design can perform key generation in 0.09ms, encapsulation in 0.13ms, and decapsulation in 0.21ms when synthesized for an Xilinx Artix 7 FPGA. Our work shows that when hardware performance is compared, HQC can be a competitive alternative candidate from the fourth round of the NIST PQC competition.

# Summary. An optional shortened abstract.

tags: [Cryptography]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1007/978-3-031-53368-6_15'
url_code: 'https://github.com/caslab-code/pqc-hqc-hardware'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#  - example
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

