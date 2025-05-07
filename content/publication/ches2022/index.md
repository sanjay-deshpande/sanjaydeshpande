---
title: 'Complete and Improved FPGA Implementation of Classic McEliece'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Po-Jen Chen
  - Tung Chou
  - Sanjay Deshpande
  - Norman Lahr
  - Ruben Niederhagen
  - Jakub Szefer
  - Wen Wang

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 
  - 'Equal contribution'
  - 
  - 
  - 
  - 

date: '2022-09-01T00:00:00Z'
doi: '10.46586/tches.v2022.i3.71-113'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'In IACR Conference on Cryptographic Hardware and Embedded Systems 2022'
publication_short: 

abstract: 'We present the first specification-compliant constant-time FPGA implementation of the Classic McEliece cryptosystem from the third-round of NIST’s Post-Quantum Cryptography standardization process. In particular, we present the first complete implementation including encapsulation and decapsulation modules as well as key generation with seed expansion. All the hardware modules are parametrizable, at compile time, with security level and performance parameters. As the most time consuming operation of Classic McEliece is the systemization of the public key matrix during key generation, we present and evaluate three new algorithms that can be used for systemization while complying with the specification: hybrid early-abort systemizer (HEA), single-pass early-abort systemizer (SPEA), and dual-pass earlyabort systemizer (DPEA). All of the designs outperform the prior systemizer designs for Classic McEliece by 2.2x to 2.6x in average runtime and by 1.7x to 2.4x in time-area efficiency. We show that our complete Classic McEliece design for example can perform key generation in 5.2 ms to 20 ms, encapsulation in 0.1 ms to 0.5 ms, and decapsulation in 0.7 ms to 1.5 ms for all security levels on an Xlilinx Artix 7 FPGA. The performance can be increased even further at the cost of resources by increasing the level of parallelization using the performance parameters of our design.'

# Summary. An optional shortened abstract.

tags: [cryptography]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2022/412.pdf'
url_code: 'https://caslab.csl.yale.edu/code/pqc-classic-mceliece/'
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
#projects:
#  - example
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

