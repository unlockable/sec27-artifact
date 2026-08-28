# Probing Before the Attacker Does
## Artifact for Anonymous Review

This repository contains the artifact accompanying our paper:

## Quick Check

```bash
python verify_artifact.py

The verifier checks the main paper-aligned artifact counts, hashes, probe populations, exposure-mechanism mapping, baseline summaries, and RQ3 results.

## Contents
metadata/ — API corpus and candidate metadata
probe_source/ — generated probe source code
binaries/ — evaluated probe binaries
results/ — paper-aligned RQ1–RQ3 results
known_techniques/ — known-technique benchmark sources
rq3_mitigations/ — RQ3 mitigation sources
PAPER_CLAIM_MAP.md — mapping from paper claims to artifact files

The final proactive result consists of 91 probe patterns spanning 23 exposure mechanisms.

The simple-generator and RAG controls are provided as paper-level aggregate records.

This artifact supports inspection and consistency checking of the released results, but does not provide end-to-end replay of every experiment.
