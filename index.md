---
layout: single
title: ""
author_profile: true
permalink: /
---

I am currently a postdoc at [COSIC, KU Leuven](https://www.esat.kuleuven.be/cosic/), where I also completed my PhD in 2025 under the supervision of [Nigel Smart](https://nigelsmart.github.io/) and [Svetla Nikova](https://www.esat.kuleuven.be/cosic/people/svetla-petkova-nikova/).
My research interests revolve around the applications and practical aspects of multi-party computation, as well as the interactions between MPC and other PETs, namely zero-knowledge proofs and homomorphic encryption.


From March to August 2023, I did a research internship at Nokia Bell Labs in Antwerp, where I worked on delegating the computation of zero-knowledge proofs.

From July 2020 to May 2023, I was involved in the [SNIPPET project](https://www.esat.kuleuven.be/cosic/project/snippet/), where I worked on the design of privacy-preserving market mechanisms for the p2p electricity market using multi-party computation.

Previously, I was a research assistant at [Instituto de Telecomunicações](https://www.it.pt/), working on quantum primitives for MPC protocols. 
Before that, I received my MSc in Applied Mathematics and my BSc in Physics from [Instituto Superior Técnico](https://tecnico.ulisboa.pt/en/) in Lisbon, Portugal. 

##### Some projects I worked on:
**[Verifiable FHE decryption](https://github.com/KULeuven-COSIC/blind_zkSNARKs/tree/main/proof-of-decryption)**: C implementation of the lattice-based ZK proof of correct FHE decryption described in [Blind zkSNARKs](https://eprint.iacr.org/2024/1684). We leveraged basic primitives provided in the [LaZer](https://eprint.iacr.org/2024/1846) library for lattice-based zero-knowledge proofs and thoroughly extended it to construct our proof of decryption for BFV and [GBFV](https://eprint.iacr.org/2024/1587).

**[Relay-based MPC system for realistic networks](https://github.com/mmargama/relay-based-mpc)**: A rust implementation of the MPC protocol described in [this paper](https://eprint.iacr.org/2023/096). The communication network, where the MPC parties communicate through a few central relay nodes, was also implemented from scratch and employs the gRPC remote-procedure-call framework for the party-relay interaction.

**[FHE-based Private Set Intersection](https://github.com/microsoft/APSI)**: A C++ implementation of the PSI protocol described in [this paper](https://eprint.iacr.org/2021/1116). 
Besides the SEAL-based implementation, there is also a version of the protocol with nearly constant communication implemented in HElib. 

### News
- **[April 25] -** I will be attending the [Dagstuhl seminar]( https://www.dagstuhl.de/25312) on privacy-preserving technologies of societal impact at the end of July.
- **[March 25] -** Our paper on [Blind zkSNARKs](https://eprint.iacr.org/2024/1684) was accepted to be presented at [ZKProof 7](https://zkproof.org/events/zkproof-7-sofia/) and at the [FHE.org 2025 conference](https://fhe.org/conferences/conference-2025/).
- **[February 25] -** I defended my PhD thesis "MPC in the Real World: Practical Aspects of Multi-Party Computation".
- **[October 24] -** Our paper [Blind zkSNARKs for Private Proof Delegation and Verifiable Computation over Encrypted Data](https://eprint.iacr.org/2024/1684) is now available online! 
- **[July 24] -** I will be presenting recent results on zero-knowledge proof delegation at the [Portugal Crypto Day](https://cryptoday.pt/) in December. 
