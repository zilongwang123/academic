---
title: "Zilong Wang, Gideon Mohr, Klaus von Gleissenthall, Jan Reineke, Marco Guarnieri. Specification and Verification of Side-channel Security for Open-source Processors via Leakage Contracts"
collection: publications
category: conferences
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: ''
date: 2023-01-01
venue: 'CCS 2023'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3576915.3623192'
---

Leakage contracts have recently been proposed as a new security
abstraction at the Instruction Set Architecture (ISA) level. Leakage contracts aim to capture the information that processors leak
through their microarchitectural implementations. However, so far,
we lack a methodology to verify that a processor actually satisfies
a given leakage contract.
In this paper, we address this challenge by developing LeaVe,
the first tool for verifying register-transfer-level (RTL) processor designs against ISA-level leakage contracts. To this end, we show how
to decouple security and functional correctness concerns. LeaVe
leverages this decoupling to make verification of contract satisfaction practical. To scale to realistic processor designs, LeaVe further
employs inductive reasoning on relational abstractions. Using
LeaVe, we precisely characterize the side-channel security guarantees of three open-source RISC-V processors, thereby obtaining
the first proofs of contract satisfaction for RTL processor designs
