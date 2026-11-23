---
title: Trustworthy Telemetry for Quantum Computers and Networks
subtitle: Quantum Computer Cybersecurity
group: quantum
summary: >-
  Quantum machines constantly report on themselves, yet none of these reports can be verified today.
  This aim anchors trust in the classical control hardware to make quantum telemetry attestable.
weight: 3
date: '2026-11-22T00:00:00Z'
authors:
  - admin
---

Most users already access quantum computers through the cloud, where providers compile and run programs from many users on shared hardware. Users of such machines face the three questions of the classic CIA triad: will the machine be available to run my job correctly, will my program stay confidential, and can I trust the integrity of what it executed?

I have begun to address all three: I have shown that a malicious user sharing a quantum chip can sabotage a neighbor's computation through crosstalk and built the first quantum computer antivirus to stop such attacks, contributed to a trusted execution environment that hides users' programs from an untrusted cloud, and developed the first real-time engine that verifies the integrity of the control pulses a quantum computer executes. This work taught me that trust in a quantum computer must be anchored in its classical control hardware, the last point where its behavior can be observed digitally.

Quantum machines constantly report on themselves: cloud providers publish the error rates users rely on to choose machines, and quantum network nodes report whether entanglement has succeeded. None of these reports can be verified today, and a report that can be forged is worthless once it crosses a boundary of trust. Because my integrity engine already fingerprints every pulse at the last digital point before the analog domain, its telemetry can be cryptographically bound to the operations that produced it.

### Roadmap

- **Short term:** Attested telemetry on cloud quantum controllers via the pulse-integrity engine, defining what must be measured and how a remote party can verify it efficiently.
- **Medium term:** Verifiable reports from quantum network nodes.
- **Long term:** Trust infrastructure for commercial quantum clouds and the quantum internet.

### Connections

This direction shares controller-hardware foundations with [Securing Fault-Tolerant Quantum Computers](../aim4-fault-tolerant-qc/).

### Relevant Publications

1. Barbora Hrdá, **Sanjay Deshpande**, Theodoros Trochatos, and Jakub Szefer. [CHEQ: Towards Enabling Circuit Integrity Checking in Quantum Controllers](/publication/glsvlsi2025/). In *Proceedings of the Great Lakes Symposium on VLSI 2025*, GLSVLSI, pages 265–272, June 2025.
