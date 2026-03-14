# Generative Recommender Course Project Workspace

This repository is our workspace for the team course project on generative recommender systems.

## Workspace Structure

- `MY_FILES/`
  - Papers, reports, and reference documents.
- `RQ-VAE-Recommender-baseline/`
  - Upstream baseline code used as the common starting point.
- `docs/`
  - Project protocol, plan, and operating context.
- `experiments/`
  - Reproducible runs, configs, scripts, and result reports.

## Project Plan (High Level)

1. `Phase_0` (shared foundation)
2. `Phase_1` (parallel individual research tracks)
3. `Phase_2` (synthesis and final conclusions)

The team must complete `Phase_0` first so all later experiments are comparable.

## Phase_0 Deliverables

- Fixed evaluation protocol: dataset(s), splits, metrics, and reporting format.
- Reproducible baseline training/evaluation run from `RQ-VAE-Recommender-baseline/`.
- Baseline results saved in:
  - `experiments/phase0/reports/baseline_report.md`
  - `experiments/registry.csv`

## Key Docs

- `docs/PHASE0_PROTOCOL.md` - What is fixed and how we evaluate.
- `docs/PROJECT_PLAN.md` - End-to-end project phases and ownership model.
- `experiments/registry.csv` - Experiment tracking table for all runs.

## Working Rules

- Keep baseline code in `RQ-VAE-Recommender-baseline/` as close to upstream as possible.
- Put team-specific scripts/configs under `experiments/phase0/` (and later phases).
- Every experiment must be registered in `experiments/registry.csv`.
