---
title: Performance Analysis of Parameterizable HQC Hardware Architecture 

event: Selected Areas in Cryptography 2026
event_url: 'https://sacworkshop.org/SAC26/'

location: University of Ottawa
address:
  street: 
  city: Ottawa
  region: Ontario
  postcode: ''
  country: Canada

summary: 
abstract: This work presents a constant-time hardware design for HQC (Hamming Quasi-Cyclic), a code-based key encapsulation mechanism selected for standardization by NIST's Post-Quantum Cryptography process. While existing hardware implementations of HQC have achieved limited performance due to area constraints, our work demonstrates that high performance can be attained with minimal hardware overhead using higher datawidth. We present a fully parameterizable, flexible data width, hardware design, configurable for both performance targets and security levels, implementing HQC key generation, encapsulation, and decapsulation in Verilog for FPGA deployment. The three operational modules share a common SHAKE256 hash core to minimize area overhead while maintaining throughput. Our design  significantly outperforms existing HQC hardware implementations in terms of latency, while achieving a similar or smaller value of the area-time (AT) product compared to existing implementations. The improved performance results from the optimizations introduced in the sparse polynomial multiplier and fixed weight vector generator modules. We achieve upto 35% improvement in the AT product when compared to other most efficient unified HQC hardware designs in the literature. For our fastest configuration targeting HQC-1 (the L1 security level), key generation completes in 0.020 ms, encapsulation in 0.040 ms, and decapsulation in 0.081 ms when implemented on a Xilinx Artix 7 FPGA, showcasing a 40% improvement in latency when compared against the fastest design, while maintaining a competitive area footprint.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-08-27T10:00:00Z'
# date_end: '2025-11-21T10:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2026-07-15T00:00:00Z'

authors: ['Sanjay Deshpande']
tags: [Cryptography]

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: ''
#   focal_point: 

links:
#   - icon: 
#     icon_pack: 
#     name: 
#     url: 
# url_code: ''
# url_pdf: ''
# url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
url_slides: '/slides/2026_SAC_HQC.pdf'

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#  - example
---

