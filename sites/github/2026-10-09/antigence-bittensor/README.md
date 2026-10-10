# Antigence × Bittensor — Public Technical Review

**Status:** Public research and architecture summary. **Executable mirror: NOT PUBLISHED.**  
**Prepared:** 2026-10-09 · **Project:** biobitworks / Antigence

## Research scope

Antigence is an immune-inspired approach to evaluating AI outputs. Its Bittensor subnet implementation investigates a decentralized verification architecture where **miners act as anomaly detectors** and **validators score their outputs** against controlled evaluation challenges. Four documented evaluation domains are hallucinations, code security, agent reasoning, and bioinformatics workflows.

The working architecture includes pluggable detectors, confidence calibration, false-positive penalties, adversarial evaluation, a weighted ensemble, an `operator_multiband` policy, and a proposed Trust Score API. The framework explores whether competitive evaluation can improve the reliability of AI-output anomaly detection. The biological immune-system analogy is conceptual, not a biological efficacy claim.

## Evidence and limits

- Private working repository: `biobitworks/antigence-bittensor`.
- Separately curated mirror repository: `biobitworks/antigence-subnet` (not publicly accessible at the time of this review).
- Reviewed source-mirror commit: `c111b1c5b66f350b0acb658e0afa119c5f5643b0`.
- Release documentation describes v10.0 simulation/local evidence and **deferred live Bittensor deployment**. The associated metadata also references a later v10.1.0 package; no live-network claim is inferred.
- No verified funded-wallet subnet registration, live validator/miner operation, real-world trust-score performance, or independent security certification is claimed here.
- A public code-snapshot staging check detected possible secret exposures; **full source publication is DEFERRED pending review**. This non-executable page is not a substitute for source or evaluation receipts.

## Akash / decentralization integration hypothesis

**PROPOSED, NOT EXECUTED:** Akash could host bounded miner inference and independent verification workloads, while Bittensor could provide an incentive and validator layer. FCO/FCG would preserve addressable source/evaluation/execution records without equating cryptographic integrity with correctness.

## Related public portfolio

- [GitHub — biobitworks](https://github.com/biobitworks)
- [Glasswork — model-comparison application](https://glasswork.butterbase.dev)
- [Cellico.Bio — computational biology research](https://cellico.bio)
- [LinkedIn](https://www.linkedin.com/in/biobitworks/)

**Document classification:** PUBLIC REVIEW SUMMARY · **Code release:** DEFERRED · **Live-network evidence:** NOT_TESTED / NOT_VERIFIED.
