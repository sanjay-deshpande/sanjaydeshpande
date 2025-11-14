---
title: Post Quantum Cryptography
subtitle: Hardware Evaluation of Post-Quantum Cryptographic Algorithms

# Summary for listings and search engines
summary: >-
#  Quantum computing's advancement threatens current cryptographic systems. Quantum algorithm called Shor's algorithm can efficiently break widely-used encryption like RSA and ECC, exposing sensitive data including biometric information and encryption keys. This necessitates urgent migration to quantum-safe alternatives. Post-quantum cryptographic (PQC) algorithms offer resistance to quantum attacks. Organizations like NIST, ISO, IETF, etc. are working towards standardizing PQC algorithms for secure communication in the quantum era. An essential aspect of these standardization processes is hardware implementation and security evaluation of these algorithms.

# Quantum computers offer some security advantages. The no-cloning theorem prevents exact copying of unknown quantum states, eliminating attack vectors like buffer overflow exploits that rely on replicating memory. However, quantum systems face entirely new vulnerabilities.
# Unlike classical processors, quantum computers require extensive classical control infrastructure—signal generators, mixers, and FPGAs—that remain understudied from a security perspective. Their large physical footprint makes them more accessible to physical probing and side-channel attacks targeting classical control pathways.
# Without quantum memory or networking, current systems embed all data directly in quantum programs. On cloud platforms, submitted jobs contain hardcoded constants and data that, if intercepted, could expose sensitive information. These unique challenges create significant research opportunities. As quantum computing becomes practical, system security has emerged as a critical research frontier. Recent studies reveal vulnerabilities across the entire quantum stack—from hardware to compilers to algorithms—while proposing innovative defense mechanisms. The following discusses current threats and defenses.

# **Hardware-Level Vulnerabilities**
# Quantum crosstalk enables attacks in multi-tenant cloud environments, where malicious circuits degrade victim computations on shared processors. Side-channel attacks leak information through timing analysis, power consumption traces, and improperly cleared qubit states that allow data leakage between consecutive circuits. My work demonstrates practicality of these attacks on real quantum hardware.

# **Software and Algorithm-Layer Threats**
# Malicious compilers threaten intellectual property through circuit theft. Sophisticated attacks like QTrojan manipulate hardware configuration files to disable data encoding while masquerading as routine calibrations.

# **Building Defense-in-Depth**
# Countermeasures span multiple layers, hardware defenses include Quantum Trusted Execution Environments, QPUFs, device fingerprinting, and circuit watermarking. Circuit obfuscation protects cloud-deployed IP. Software defenses include quantum antivirus systems detecting malicious patterns and circuit splitting across processors to limit information exposure.

# **Taxonomizing the Threat Landscape**
# Recent surveys categorize quantum security threats into three classes - (1) Information Leak attacks extracting sensitive data, (2) Untargeted Attacks degrading performance opportunistically, and (3) Targeted Attacks achieving precise malicious goals through deep system knowledge.

# **The Path Forward**
# As quantum systems advance, security must evolve alongside. Robust defenses across hardware, software, and algorithms are essential to ensure quantum computing delivers trustworthy, resilient systems for sensitive computations. My work contributes to this critical research frontier, exploring vulnerabilities and pioneering defenses to safeguard the quantum future.



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
<!-- Quantum computing is emerging as a transformative technology capable of solving problems beyond classical supercomputers' reach. Major platforms like IBM Quantum, Amazon Braket, and Microsoft Azure now offer cloud-based quantum processors, making this technology widely accessible. While much attention focuses on post-quantum cryptography, protecting classical systems from quantum attacks, my work focuses on complementary aspects: securing quantum computers themselves from security threats.

Quantum computers offer some security advantages. The no-cloning theorem prevents exact copying of unknown quantum states, eliminating attack vectors like buffer overflow exploits that rely on replicating memory. However, quantum systems face entirely new vulnerabilities. Unlike classical processors, quantum computers require extensive classical control infrastructure—signal generators, mixers, and FPGAs—that remain understudied from a security perspective. Their large physical footprint makes them more accessible to physical probing and side-channel attacks targeting classical control pathways. Without quantum memory or networking, current systems embed all data directly in quantum programs. On cloud platforms, submitted jobs contain hardcoded constants and data that, if intercepted, could expose sensitive information. These unique challenges create significant research opportunities. As quantum computing becomes practical, system security has emerged as a critical research frontier. Recent studies reveal vulnerabilities across the entire quantum stack—from hardware to compilers to algorithms—while proposing innovative defense mechanisms. -->

<!-- ### Hardware-Level Vulnerabilities
Quantum crosstalk enables attacks in multi-tenant cloud environments, where malicious circuits degrade victim computations on shared processors. Side-channel attacks leak information through timing analysis, power consumption traces, and improperly cleared qubit states that allow data leakage between consecutive circuits. My work demonstrates practicality of these attacks on real quantum hardware.

### Software and Algorithm-Layer Threats
Malicious compilers threaten intellectual property through circuit theft. Sophisticated attacks like QTrojan manipulate hardware configuration files to disable data encoding while masquerading as routine calibrations.

### Building Defense-in-Depth
Countermeasures span multiple layers, hardware defenses include Quantum Trusted Execution Environments, QPUFs, device fingerprinting, and circuit watermarking. Circuit obfuscation protects cloud-deployed IP. Software defenses include quantum antivirus systems detecting malicious patterns and circuit splitting across processors to limit information exposure.

### Taxonomizing the Threat Landscape
Recent surveys categorize quantum security threats into three classes - (1) Information Leak attacks extracting sensitive data, (2) Untargeted Attacks degrading performance opportunistically, and (3) Targeted Attacks achieving precise malicious goals through deep system knowledge. -->

<!-- ### The Path Forward
As quantum systems advance, security must evolve alongside. Robust defenses across hardware, software, and algorithms are essential to ensure quantum computing delivers trustworthy, resilient systems for sensitive computations. My research work contributes to this critical research frontier, exploring vulnerabilities and pioneering defenses to safeguard the quantum future. -->
