# DELTA: An Update-efficient Decentralized Storage Network Based on Erasure Coding

## Appendix

This repository contains the appendix for the paper **"DELTA: An Update-efficient Decentralized Storage Network Based on Erasure Coding"**. 

The appendix provides detailed mathematical derivations, proofs of correctness, and security analysis to support the claims made in the main paper.

### Contents

*   **Appendix A: Storage Price and RS Parameter Derivation**
    *   Details the relationship between storage cost, desired fault tolerance, and the selection of Reed-Solomon (RS) coding parameters (k, m).
    *   Provides mathematical derivation showing how the target fault tolerance ratio $	au$ and node failure rate $p$ determine the required RS parameters and total storage cost.
*   **Appendix B: Correctness of Signature Scheme**
    *   Provides step-by-step mathematical proofs for the cryptographic primitives used in DELTA.
    *   Includes derivations for:
        *   Signature Verification
        *   Storage Proof Verification
        *   Aggregated Proof Verification
        *   Signature Increment Correctness
*   **Appendix C: Security and Correctness of DELTA**
    *   Establishes the security and correctness of the DELTA system from both the auditing scheme and protocol-level perspectives.
    *   Includes formal proofs (Theorems 1-5) demonstrating the scheme's resistance to:
        *   Signature Forgery
        *   Signature Increment Forgery
        *   Storage Proof Forgery
        *   Generation Attacks
        *   Replay Attacks
    *   Proves key protocol properties (Propositions 2 & 3) regarding consistent read operations and asynchronous auditing mechanisms under concurrent updates.

### Usage

This document is intended as supplementary material for peer review and further research reference.

