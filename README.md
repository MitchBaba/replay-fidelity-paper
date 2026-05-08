# Replay-Fidelity

This repository contains the draft paper:

**Replay-Fidelity: A Structural Audit of Public Conversational AI Datasets for Deterministic Replay**

The paper argues that many public conversational AI datasets are useful for analysis, but do not always preserve enough structure for deterministic multi-turn replay.

The focus is on structural requirements such as:

- turn order
- role attribution
- conversation completeness
- record-boundary integrity
- replay-grade evaluation

This is not a model paper, benchmark proposal, or attack paper. It is a structural audit / measurement-validity paper.

## Reproducibility Tool

The structural audit tool used for this paper is available here:

https://github.com/MitchBaba/replay-fidelity-auditor

The auditor checks dataset structure for replay-fidelity properties such as enumerable turns, role attribution, alternation depth, missing required roles, and truncation / summary markers.

## Author

Mitchell Ryan Baba  
Founder / Lead Researcher, DriftForge Systems

## Research Context

DriftForge Systems is an independent research effort focused on multi-turn conversational AI behavior, replay-fidelity, defensive AI security evaluation, and controlled red-team methodology.

## Contact

contact@driftforge.systems
