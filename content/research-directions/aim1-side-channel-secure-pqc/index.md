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
