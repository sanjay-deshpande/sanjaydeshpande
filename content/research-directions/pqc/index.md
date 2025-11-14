---
title: Post Quantum Cryptography
subtitle: Hardware Evaluation of Post-Quantum Cryptographic Algorithms

# Summary for listings and search engines
summary: >-
  Quantum computing's advancement threatens current cryptographic systems. Quantum algorithm called Shor's algorithm can efficiently break widely-used encryption like RSA and ECC, exposing sensitive data including biometric information and encryption keys. This necessitates urgent migration to quantum-safe alternatives. 
#  Post-quantum cryptographic (PQC) algorithms offer resistance to quantum attacks. Organizations like NIST, ISO, IETF, etc. are working towards standardizing PQC algorithms for secure communication in the quantum era. An essential aspect of these standardization processes is hardware implementation and security evaluation of these algorithms.



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

"Quantum computing's rapid advancement promises transformative breakthroughs across numerous disciplines. However, while quantum computers offer unprecedented capabilities for solving complex mathematical problems, they simultaneously threaten the security foundations of our existing cryptographic infrastructure. Shor's algorithm, a quantum algorithm, can efficiently compromise widely deployed public-key encryption systems including Rivest-Shamir-Adleman (RSA) and Elliptic Curve Cryptography (ECC), exposing sensitive information to potential attacks. This vulnerable information spans critical assets such as biometric data, encryption keys, and other confidential materials. The quantum threat creates an urgent imperative to transition toward quantum-resistant alternatives before adversaries with quantum capabilities emerge.

Addressing this challenge, post-quantum cryptographic (PQC) algorithms represent a critical defense, providing cryptographic schemes designed to withstand both classical and quantum attacks. The National Institute of Standards and Technology (NIST), alongside international cryptographic organizations, is actively working to standardize PQC algorithms. Hardware implementation and rigorous evaluation form essential components of these standardization efforts, ensuring practical deployability and security validation.

My work advances practical understanding of PQC algorithms through comprehensive hardware implementation and performance analysis. The work examines six distinct algorithms—three key encapsulation mechanisms and three digital signature schemes—representing four unique cryptographic families, providing insights into optimal hardware realization strategies for quantum-resistant cryptography.

### Looking Ahead
Post-quantum cryptography is essential for protecting digital infrastructure against quantum computer threats. NIST has standardized five algorithms and is evaluating 14 additional candidates to provide diverse cryptographic options for varying use cases and security requirements. Prototyping and assessing these algorithms across hardware and software platforms is crucial for informing deployment decisions.
My research plans to address this need by developing efficient, secure, side-channel-resistant implementations tailored to specific applications—from resource-constrained IoT devices to high-performance cloud infrastructure. Using RTL and high-level synthesis, I optimize the performance-security tradeoff for each deployment scenario, recognizing that different applications demand different solutions. My work encompasses the full hardware acceleration spectrum, from CPU extensions to custom accelerators, with quantitative evaluation identifying optimal designs for each use case.

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
