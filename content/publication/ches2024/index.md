---
title: 'Complete and Improved FPGA Implementation of Classic McEliece'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanjay Deshpande
  - James Howe
  - Jakub Szefer
  - Dongze Yue
  
# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 
 

date: '2024-03-12T00:00:00Z'
doi: 'https://doi.org/10.46586/tches.v2024.i2.215-251'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'In IACR Conference on Cryptographic Hardware and Embedded Systems 2024'
publication_short: 

abstract: 'This work presents the first hardware realisation of the Syndrome-Decoding-in-the-Head (SDitH) signature scheme, which is a candidate in the NIST PQC process for standardising post-quantum secure digital signature schemes. SDitH's hardness is based on conservative code-based assumptions, and it uses the Multi-Party-Computation-in-the-Head (MPCitH) construction. This is the first hardware design of a code-based signature scheme based on traditional decoding problems and only the second for MPCitH constructions, after Picnic. This work presents optimised designs to achieve the best area efficiency, which we evaluate using the Time-Area Product (TAP) metric. This work also proposes a novel hardware architecture by dividing the signature generation algorithm into two phases, namely offline and online phases for optimising the overall clock cycle count. The hardware designs for key generation, signature generation, and signature verification are parameterised for all SDitH parameters, including the NIST security levels, both syndrome decoding base fields (GF256 and GF251), and thus conforms to the SDitH specifications. The hardware design further supports secret share splitting, and the hypercube optimisation which can be applied in this and multiple other NIST PQC candidates. 
The results of this work result in a hardware design with a drastic reducing in clock cycles compared to the optimised AVX2 software implementation, in the range of 2-4x for most operations. Our key generation outperforms software drastically, giving a 11-17x reduction in runtime, despite the significantly faster clock speed. On Artix 7 FPGAs we can perform key generation in 55.1 Kcycles, signature generation in 6.7 Mcycles, and signature verification in 8.6 Mcycles for NIST L1 parameters, which increase for GF251, and for L3 and L5 parameters.'

# Summary. An optional shortened abstract.

tags: [cryptography]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://tches.iacr.org/index.php/TCHES/article/view/11426/10932'
url_code: 'https://github.com/sandbox-quantum/sdith-impl-hw'
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

