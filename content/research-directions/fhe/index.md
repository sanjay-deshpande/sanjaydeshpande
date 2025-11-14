---
title: Fully Homomorphic Encryption
subtitle: Hardware Acceleration of FHE and vFHE Schemes

# Summary for listings and search engines
summary: >-
  Fully Homomorphic Encryption (FHE), cryptography's holy grail that enables secure computation on encrypted data without decryption. This technology resolves the fundamental tension between data utility and privacy, with applications spanning cloud computing, AI, and secure data analysis.



# Link this post with a project
projects: []

# Date published
date: '2025-11-14T00:00:00Z'

# Date updated
lastmod: '2025-11-14T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ''
  placement: 1
  preview_only: false

authors:
  - admin

tags:
  - 

categories:
  - 
---

<style>
/* Apply justified alignment to common content containers */
body,
main,
article,
section,
.post,
.content,
.entry-content {
  text-align: justify;
}
</style>

Fully Homomorphic Encryption (FHE)—cryptography's holy grail that enables secure computation on encrypted data without decryption. This technology resolves the fundamental tension between data utility and privacy, with applications spanning cloud computing, AI, and secure data analysis. What makes this direction particularly compelling is that FHE schemes share mathematical building blocks with lattice-based post-quantum algorithms, allowing me to leverage components and insights from my PQC research.

### The Road Ahead
Current FHE schemes face a critical trade-off between functionality and efficiency. While traditional schemes lack SIMD parallelism, CKKS enables it. The recent emergence of discrete CKKS represents a breakthrough, combining maximum SIMD parallelism with exact integer arithmetic to enable three powerful operations: arithmetic operations, look-up tables, and modular reduction. My research leverages discrete CKKS to build a comprehensive homomorphic integer computer suitable for homomorphic cryptographic operations, targeting orders-of-magnitude throughput improvements over state-of-the-art implementations.

Beyond performance optimization, my work will investigate verifiable FHE schemes that provide essential integrity guarantees, ensuring computations on encrypted data execute correctly. However, verifiability introduces substantial computational overhead on top of already expensive homomorphic operations. To visualize this challenge: regular computation requires baseline effort, homomorphic computation adds significant overhead, and verifiable homomorphic computation compounds this further. While most hardware optimization efforts focus on reducing the gap between regular and homomorphic computation, my research addresses the largely unexplored problem of minimizing the additional overhead introduced by verifiability through algorithmic optimizations and hardware acceleration. This represents a novel contribution that could make verifiable FHE practical for real-world deployment.
