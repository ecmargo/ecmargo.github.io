---
layout: list
title: Eli Margolin - Resume
download: /assets/files/Margolin_Resume.pdf
sections:
  - label: Summary
    items:
      - body: "PhD candidate in Computer and Information Science at the University of Pennsylvania working at the intersection of applied cryptography, zero-knowledge proofs, and formal methods. Builds and performance-optimizes fast, succinct non-interactive proof systems for formal languages, implemented in Rust and released open-source, with publications at IEEE S&P, USENIX Security, and SOSP. Pairs deep cryptography with three years of security engineering at Meta and a rigorous eye for soundness and correctness. Current focus: using cryptographic tools, including zero-knowledge proofs, to make AI systems auditable and accountable."
  - label: Technical Skills
    items:
      - title: "Cryptography"
        body: "Zero-knowledge proofs / SNARKs; verifiable computation; ZK circuit design &amp; prover performance optimization; protocol design &amp; implementation; MPC, threshold signatures, distributed key generation, secret sharing (protocol-level); signature schemes (Schnorr, EdDSA, ECDSA, BIP-340)."
      - title: "Formal Methods"
        body: "Interactive theorem proving (Coq); SMT solvers; program analysis; circuit/constraint compilation (CirC); reasoning about soundness &amp; correctness."
      - title: "Privacy &amp; Security"
        body: "Differential privacy; federated / private analytics; threat modeling, threat &amp; abuse detection, security-sensitive code &amp; design review."
      - title: "Languages &amp; Tools"
        body: "Rust, C++, Python; Coq; LLVM / MLIR; distributed &amp; privacy-preserving systems."
  - label: Experience
    items:
      - title: "University of Pennsylvania — PhD Researcher, Applied Cryptography &amp; Formal Methods"
        meta: "2021–present"
        body: "<ul><li>Build and performance-optimize fast, succinct non-interactive ZK proof systems for formal languages — regular expressions (Reef) and context-free grammars (Coral) — designing ZK circuits and constraint systems and tuning prover runtime and proof size; implemented in Rust and open-sourced.</li><li>Reason rigorously about the soundness, correctness, and security assumptions of cryptographic proof systems using SMT solvers and interactive theorem proving (Coq).</li><li>Apply cryptographic tools, including zero-knowledge proofs, to bring auditability and accountability to AI systems; advised by Sebastian Angel (dissertation: <em>Zero Knowledge Proofs of Formal Languages</em>).</li></ul>"
      - title: "Brave Software — Research Intern"
        meta: "Summer 2024"
        body: "<ul><li>Designed and implemented zero-knowledge protocols for privacy-preserving fraud detection, taking research designs through to deployable implementations.</li><li>Reviewed and hardened cryptographic tooling to interoperate with modern TLS stacks, bridging research prototypes and production.</li></ul>"
      - title: "Meta Platforms — Security Engineer"
        meta: "2019–2021 (Contingent Worker, 2022)"
        body: "<ul><li>Performed threat modeling and security analysis to design and own company-wide insider-threat and abuse-detection tooling for security and legal investigations teams.</li><li>Scaled alert-processing pipelines through automation, increasing throughput while driving down false-positive rates.</li><li>Led cross-functional security and privacy reviews with Legal and Policy to reduce the data footprint of detection systems without sacrificing efficacy.</li></ul>"
      - title: "Duke University — Research Assistant, Differential Privacy"
        meta: "2019"
        body: "<ul><li>Quantified tradeoffs between differential-privacy guarantees and Voting Rights Act compliance for the 2020 U.S. Census, in collaboration with the U.S. Census Bureau.</li></ul>"
  - label: Selected Publications
    items:
      - title: "Coral: Fast Succinct Non-Interactive Zero-Knowledge CFG Proofs"
        meta: "IEEE S&P 2026"
        body: "S. Angel, S. Celi, E. Margolin*, P. Mishra, M. Sander, J. Woods."
        links:
          - text: code
            url: https://github.com/eniac/coral
      - title: "Reef: Fast Succinct Non-Interactive Zero-Knowledge Regex Proofs"
        meta: "USENIX Security 2024"
        body: "S. Angel, E. Ioannidis, E. Margolin*, S. Setty, J. Woods."
        links:
          - text: code
            url: https://github.com/eniac/Reef
      - title: "Arboretum: A Planner for Large-Scale Federated Analytics with Differential Privacy"
        meta: "SOSP 2023"
        body: "E. Margolin, K. Newatia, E. Roth, T. Luo, A. Haeberlen. <em>* Authors listed in alphabetical order.</em>"
  - label: Education
    items:
      - title: "University of Pennsylvania — PhD, Computer and Information Science"
        meta: "In progress"
      - title: "Duke University — MS, Economics and Computation"
      - title: "Stanford University — BA, Political Science, with Honors in International Security"
  - label: Selected Activities
    items:
      - title: "Team USA — National Team Athlete (Rowing); USRowing Athlete Council"
        meta: "2025–present"
        body: "Competed at the 2025 World Rowing Championships, Shanghai."
---
