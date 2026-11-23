---
title: Hardware for AI and AI for Hardware, Built Securely
subtitle: Classical Security
group: classical
summary: >-
  AI and hardware now shape each other in both directions. This aim builds fully homomorphic encryption (FHE) hardware for privacy-preserving AI,
  and examines whether hardware designed by AI tools can be trusted.
weight: 2
date: '2026-11-22T00:00:00Z'
authors:
  - admin
---

AI and hardware now shape each other in both directions, and each direction raises its own security questions.

### Hardware for AI

Most AI workloads run on proprietary cloud platforms, so users must hand their data to servers they do not control. Fully homomorphic encryption (FHE) addresses this by letting a server compute directly on encrypted data, but it remains orders of magnitude slower than computing on plain data, especially for AI. Non-linear functions such as ReLU and GeLU require functional bootstrapping, FHE's most expensive operation. The hardware techniques behind lattice-based PQC, such as fast polynomial arithmetic, carry directly to FHE.

With funding from Microsoft Research, I am leading the near-term phase: a trace-based framework linking encrypted AI workloads to hardware models, a study of how parameters, precision, and word length trade accuracy against hardware cost, and an optimized number-theoretic transform core shared with lattice-based PQC. Building on these results, I will develop a unified CKKS accelerator with dedicated key-switching and bootstrapping engines, prototyped first on FPGAs and scaled toward a multi-chip ASIC for end-to-end privacy-preserving AI services.

### AI for Hardware

AI tools are beginning to generate hardware designs, yet they optimize for functional correctness rather than security. In work currently under review, I have begun examining whether AI-generated cryptographic hardware that passes functional tests still leaks secrets through side channels. Building on it, I will develop verification methods that catch such leakage and, in the long term, security-aware AI-assisted design flows.

### Roadmap

- **Short term:** Profiling AI workloads under FHE; side-channel leakage in AI-generated cryptographic designs.
- **Medium term:** Encrypted AI inference on an FPGA prototype; verifying AI-generated hardware.
- **Long term:** A multi-chip FHE ASIC; security-aware AI-assisted design flows.

### Connections

This direction shares lattice arithmetic and hardware-design techniques with [Side-Channel-Secure Post-Quantum Cryptography](../aim1-side-channel-secure-pqc/).

### Relevant Publications

1. Xuan Wang, **Sanjay Deshpande**, Jaehyung Kim, Jakub Szefer, Tajana Rosing, and Patrick Longa. [CKKS Acceleration for Next-Wave Homomorphic Encryption](/publication/2026_eprint/). *Cryptology ePrint Archive*, Paper 2026/2921, 2026.
