---
title: Accelerating FrodoKEM in Hardware
slug: ches2026

event:  IACR Transactions on Cryptographic Hardware and Embedded Systems 2026
event_url: 

location: IACR TCHES 2026
address:
  street: 
  city: Antalya
  region: 
  postcode: ''
  country: Turkey

summary: 
abstract: FrodoKEM, a conservative post-quantum key encapsulation mechanism based on the plain Learning with Errors (LWE) problem, has been recommended for use by several government cybersecurity agencies and is currently undergoing standardization by the International Organization for Standardization (ISO). Despite its robust security guarantees, FrodoKEM's performance remains one of the main challenges to its widespread adoption. This work addresses this concern by presenting a fully standard-compliant, high-performance hardware implementation of FrodoKEM targeting both FPGA and ASIC platforms. The design introduces a scalable parallelization architecture that supports run-time configurability across all twelve parameter sets, covering three security levels (L1, L3, L5), two PRNG variants (SHAKE-based and AES-based), and both standard and ephemeral modes, alongside synthesis-time tunability through a configurable performance parameter to balance throughput and resource utilization. For security level L1 on AMD Artix 7 FPGA, the implementation achieves 2,599, 2,338, and 2,147 operations per second for key generation, encapsulation, and decapsulation, respectively, representing the fastest standard-compliant performance reported to date while consuming only 37.6K LUTs, 64 DSPs, and 10.1K flip-flops. The design achieves a 2.3–159x improvement in the Area-Time Product (ATP) over all prior specification-compliant FPGA implementations. Furthermore, this work presents the first ASIC evaluation of FrodoKEM using the NANGATE45 45~nm technology library, achieving 7,721, 6,946, and 6,378 operations per second for key generation, encapsulation, and decapsulation, respectively, with a logic area of 0.250~mm^2. The ASIC implementation exhibits favorable sub-linear area scaling and competitive energy efficiency across different performance parameter configurations, establishing a baseline for future comparative studies. The results validate FrodoKEM's practical viability for deployment in high-throughput, resource-constrained, and power-sensitive cryptographic applications, demonstrating that conservative post-quantum security can be achieved without compromising performance.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-10-15T10:00:00Z'
# date_end: '2024-09-06T00:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2026-10-15T00:00:00Z'
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
url_slides: '/slides/2026_CHES_FrodoKEM.pdf'

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#  - example
---
