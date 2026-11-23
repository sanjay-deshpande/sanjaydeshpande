---
title: Securing Fault-Tolerant Quantum Computers from the Design Stage
subtitle: Quantum Computer Cybersecurity
group: quantum
summary: >-
  As quantum computers become fault tolerant, they will rely even more heavily on classical hardware that can leak information.
  This aim secures error-correction decoders and fault-tolerant architectures before they are deployed.
weight: 4
date: '2026-11-22T00:00:00Z'
authors:
  - admin
---

{{< figure src="quantum-cia-cloud.png" alt="Quantum computer security projects mapped to the CIA triad and the cloud quantum computing workflow" caption="(a) The CIA triad, adapted from NIST, with each of my quantum security projects placed on the pillar it addresses. (b) A typical cloud-based quantum computing workflow, divided into software and hardware stacks; circled numbers show where each project in (a) operates." >}}

The field is moving from today's noisy intermediate-scale quantum (NISQ) machines toward fault-tolerant quantum computers (FTQC), which will continuously correct their own errors; industry roadmaps target the first such machines within this decade.

Error correction depends on real-time decoders running on classical hardware such as FPGAs, the same kind of hardware I have spent years building and attacking. Decoder activity, the order in which encoded qubits are accessed, and the routing of logical operations will all leave observable traces that can reveal what is being computed.

### Roadmap

- **Short term:** A threat model for FTQCs; measuring the power and timing leakage of FPGA decoders.
- **Medium term:** Fault injection against decoders; how code choice, chip layout, and compilation shape leakage.
- **Long term:** Secure-by-design fault-tolerant quantum computer architectures.

### Connections

This direction builds on the controller hardware of [Trustworthy Telemetry for Quantum Computers and Networks](../aim3-quantum-telemetry/) and the side-channel methods of [Side-Channel-Secure Post-Quantum Cryptography](../aim1-side-channel-secure-pqc/).

### Relevant Publications

1. Barbora Hrdá, **Sanjay Deshpande**, Theodoros Trochatos, and Jakub Szefer. [CHEQ: Towards Enabling Circuit Integrity Checking in Quantum Controllers](/publication/glsvlsi2025/). In *Proceedings of the Great Lakes Symposium on VLSI 2025*, GLSVLSI, pages 265–272, June 2025.
2. Theodoros Trochatos, Chuanqi Xu, **Sanjay Deshpande**, Yao Lu, Yongshan Ding, and Jakub Szefer. Trusted Execution Environments for Quantum Computers. *Frontiers in Computer Science*, 7, 2025.
3. Theodoros Trochatos, Chuanqi Xu, **Sanjay Deshpande**, Yao Lu, Yongshan Ding, and Jakub Szefer. [Protecting Quantum Computers with a Trusted Controller](/publication/qce2024/). In *International Conference on Quantum Computing and Engineering*, QCE, September 2024.
4. Theodoros Trochatos, **Sanjay Deshpande**, Chuanqi Xu, Yao Lu, Yongshan Ding, and Jakub Szefer. [Dynamic Pulse Switching for Protection of Quantum Computation on Untrusted Clouds](/publication/host2024/). In *International Symposium on Hardware Oriented Security and Trust*, HOST, May 2024.
5. Theodoros Trochatos, Chuanqi Xu, **Sanjay Deshpande**, Yao Lu, Yongshan Ding, and Jakub Szefer. [A Quantum Computer Trusted Execution Environment](/publication/cal2023/). *IEEE Computer Architecture Letters*, 22(2):177–180, 2023. **Best of IEEE CAL Award**
6. **Sanjay Deshpande**, Chuanqi Xu, Theodoros Trochatos, Hanrui Wang, Ferhat Erata, Song Han, Yongshan Ding, and Jakub Szefer. [Design of Quantum Computer Antivirus](/publication/host2023/). In *Proceedings of the International Symposium on Hardware Oriented Security and Trust*, HOST, May 2023. (Also accepted for presentation at Quantum Computer Cybersecurity Symposium (QCCS 2023).)
7. **Sanjay Deshpande**, Chuanqi Xu, Theodoros Trochatos, Yongshan Ding, and Jakub Szefer. [Towards an Antivirus for Quantum Computers](/publication/host2022/). In *Proceedings of the International Symposium on Hardware Oriented Security and Trust*, HOST, Jun. 2022.
