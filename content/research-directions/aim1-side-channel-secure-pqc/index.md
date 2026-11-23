---
title: Side-Channel-Secure Post-Quantum Cryptography
subtitle: Classical Security
group: classical
summary: >-
  Post-quantum schemes are already being deployed, yet most hardware designs optimize speed first and add protection later, if at all.
  This aim evaluates and hardens standardized PQC against side-channel and fault-injection attacks across platforms.
weight: 1
date: '2026-11-22T00:00:00Z'
authors:
  - admin
---

{{< figure src="pqc-timeline.png" alt="Post-quantum cryptography standardization timeline" caption="Post-quantum cryptography standardization timeline. (1) NIST's main PQC standardization process; (2) NIST's additional digital signature process. Green boxes mark my published hardware work on each scheme; (3) shows how my proposed research extends into the migration and deployment phase, from efficient implementations to side-channel and fault-injection-resistant designs across hardware platforms." >}}

NIST has proposed retiring today's public-key algorithms by 2030, and post-quantum schemes are already being deployed. Yet most hardware designs for them optimize speed first and add protection later, if at all.

I have built efficient hardware implementations of six PQC schemes from four mathematical families, many of them during NIST's evaluation, and released them openly. NIST's report explaining its selection of HQC for standardization (NIST IR 8545) cites my HQC hardware design. Building and evaluating these designs taught me that speed is not enough: an implementation must also withstand side-channel and fault-injection attacks before it is deployed.

Our recent power side-channel attack on a hardware implementation of HQC showed why: a design whose running time is independent of its secrets still leaked its key through power.

### Roadmap

- **Short term:** Evaluate side-channel and fault-injection leakage of standardized PQC schemes across platforms, from microcontrollers to FPGAs and dedicated accelerators.
- **Medium term:** Design protected versions of the building blocks many schemes share, such as pseudorandom number generators, so that one secured module strengthens every scheme that uses it, and release them as an open-source library of protected PQC modules.
- **Long term:** An evaluation methodology that can inform future standards and schemes.

### Connections

This direction shares lattice arithmetic and hardware-design techniques with [Hardware for AI and AI for Hardware](../aim2-hardware-for-ai/), and its side-channel methods carry over to [Securing Fault-Tolerant Quantum Computers](../aim4-fault-tolerant-qc/).

### Relevant Publications

1. Stef Halmans, Niklas Höher, Dina Hesse, **Sanjay Deshpande**, Jakub Szefer, and Tim Güneysu. [Storing Less in-the-Head: An Area-Efficient Hardware Architecture for SDitH-v2](/publication/asiacrypt2026/). In *Advances in Cryptology – ASIACRYPT 2026* (to appear), 2026.
2. **Sanjay Deshpande**, Patrick Longa, and Jakub Szefer. [Accelerating FrodoKEM in Hardware](/publication/ches2026-0/). *IACR Transactions on Cryptographic Hardware and Embedded Systems*, 2026(3):881–907, Jul. 2026.
3. Nishant Pandey, **Sanjay Deshpande**, Dixit Dutt Bohra, Debapriya Basu Roy, Dip Sankar Banerjee, and Jakub Szefer. [Performance Analysis of Parameterizable HQC Hardware Architecture](/publication/sac2026/). In *Proceedings of the Selected Areas in Cryptography*, SAC, Aug. 2026. (Also accepted for presentation at International Workshop on Code-Based Cryptography (CBCrypto 2026).)
4. **Sanjay Deshpande**, Yongseok Lee, Mamuri Nawan, Kashif Nawaz, Ruben Niederhagen, Yunheung Paek, and Jakub Szefer. [Unified MEDS Accelerator](/publication/sac2025/). In *Selected Areas in Cryptography – SAC 2025*, pages 391–421, Cham, 2026. Springer Nature Switzerland. (Also accepted for presentation at International Workshop on Code-Based Cryptography (CBCrypto 2026).)
5. **Sanjay Deshpande**, Yongseok Lee, Cansu Karakuzu, Jakub Szefer, and Yunheung Paek. [SPHINCSLET: An Area-Efficient Accelerator for the Full SPHINCS+ Digital Signature Algorithm](/publication/tecs2025/). *ACM Transactions on Embedded Computing Systems*, April 2025. (Also accepted for presentation at Sixth NIST PQC conference.)
6. **Sanjay Deshpande**, James Howe, Jakub Szefer, and Dongze Yue. [SDitH in Hardware](/publication/ches2024/). *IACR Transactions on Cryptographic Hardware and Embedded Systems*, 2024(2):215–251, Mar. 2024. (Also accepted for presentation at Fifth NIST PQC conference and International Workshop on Code-Based Cryptography (CBCrypto 2024).)
7. **Sanjay Deshpande**, Chuanqi Xu, Mamuri Nawan, Kashif Nawaz, and Jakub Szefer. [Fast and Efficient Hardware Implementation of HQC](/publication/sac2023/). In *Proceedings of the Selected Areas in Cryptography*, SAC, Aug. 2023. (Also accepted for presentation at Fourth NIST PQC conference and International Workshop on Code-Based Cryptography (CBCrypto 2023).)
8. Po-Jen Chen, Tung Chou, **Sanjay Deshpande**, Norman Lahr, Ruben Niederhagen, Jakub Szefer, and Wen Wang. [Complete and Improved FPGA Implementation of Classic McEliece](/publication/ches2022/). *IACR Transactions on Cryptographic Hardware and Embedded Systems*, 2022(3):71–113, Jun. 2022. (Also accepted for presentation at Fourth NIST PQC Standardization conference.)
9. **Sanjay Deshpande**, Santos Merino del Pozo, Victor Mateu, Marc Manzano, Najwa Aaraj, and Jakub Szefer. [Modular Inverse for Integers using Fast Constant Time GCD Algorithm and its Applications](/publication/fpl2021/). In *Proceedings of the International Conference on Field Programmable Logic and Applications*, FPL, Aug. 2021.
10. **Sanjay Deshpande** and Kris Gaj. [Analysis and Inner-Round Pipelined Implementation of Selected Parallelizable CAESAR Competition Candidates](/publication/dsd2017/). In *2017 Euromicro Conference on Digital System Design (DSD)*, pages 274–282, 2017.
