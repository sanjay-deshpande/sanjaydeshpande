---
title: 'Modular Inverse for Integers using Fast Constant Time GCD Algorithm and its Applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanjay Deshpande
  - Santos Merino del Pozo
  - Victor Mateu
  - Marc Manzano
  - Najwa Aaraj
  - Jakub Szefer

# Author notes (optional)
author_notes:

date: '2021-08-30T00:00:00Z'
doi: '10.1109/FPL53798.2021.00028'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-12T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 31st International Conference on Field-Programmable Logic and Applications (FPL 2021) 
publication_short: 

abstract: Modular inversion, the multiplicative inverse of an integer in the ring of integers modulo a prime number, is widely used in public-key cryptography. However, it is one of the most computationally intensive operations, thus, it remains the main performance bottleneck for many cryptographic algorithms.This paper presents to the best of the author’s knowledge, the first FPGA-based hardware design for computing the multiplicative inverse using the recently proposed fast constant-time Greatest Common Divisor (GCD) algorithm. This paper introduces two distinct design architectures targeting different applications: (a) a full-width design and (b) a sequential design. The presented designs are compact, parameterizable, and scalable in terms of area and speed. The evaluation shows the proposed designs, which are constant-time and protect against timing-based attacks, outperform existing software and hardware implementations that use other modular inversion techniques. As a specific example, this work presents an evaluation focusing on the use of the multiplicative inverse hardware module to accelerate the ElGamal cryptosystem. The proposed design achieves a speed-up of 90% in the modular inverse calculation and a speed-up of 45% in the overall ElGamal decryption algorithm using our sequential hardware design of fast constant-time GCD algorithm.In addition to developing the fast hardware implementation, this work potentially opens up a new direction for designing cryptosystems: the inverse operation is often avoided when designing algorithms, due to its complexity. With the new hardware module, using the inverse becomes more tractable, making it more appealing to use in the design of new cryptosystems.

# Summary. An optional shortened abstract.

tags: [cryptography]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://eprint.iacr.org/2022/412.pdf'
url_code: 'https://caslab.csl.yale.edu/code/fast-constant-time-gcd/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=EL6MMDWwyxE'

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
slides: fpl2021.pdf
---

