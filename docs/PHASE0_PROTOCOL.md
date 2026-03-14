# Phase_0 Protocol

## Goal

Build a shared, reproducible baseline for the course project so all Phase_1 experiments are directly comparable.

## Scope

Phase_0 covers only common setup and baseline measurements:

1. Dataset and split agreement.
2. Fixed metric set and reporting format.
3. Baseline training/evaluation run.
4. Baseline result registration.

## What Must Be Fixed

The following settings are fixed for all team members before Phase_1:

- Dataset(s): `TBD` (set once, then freeze)
- Split protocol: `TBD` (exact train/eval/test definition)
- Baseline code revision: commit hash in `RQ-VAE-Recommender-baseline/`
- Baseline model/config: exact config file and runtime overrides
- Metrics:
  - `Recall@10`
  - `NDCG@10`
  - `Recall@50` (optional but recommended)
  - Head/Mid/Tail breakdown (same popularity bucket definition for everyone)
- Negative sampling/evaluation mode: `TBD`

## Required Artifacts

- Baseline run entry in `experiments/registry.csv`
- Baseline report in `experiments/phase0/reports/baseline_report.md`
- Exact command(s) used to run baseline
- Environment note (Python version, key package versions, GPU/CPU)

## Suggested Execution Order

1. Freeze protocol values marked `TBD`.
2. Run baseline end-to-end once.
3. Verify metrics and save outputs.
4. Register run and publish baseline report.
5. Start Phase_1 tracks.

## Done Criteria for Phase_0

Phase_0 is complete when:

- All protocol fields are frozen (no `TBD` left).
- Baseline metrics are reproduced at least once by another team member.
- Team agrees to use this baseline as the reference for all deltas in Phase_1.

