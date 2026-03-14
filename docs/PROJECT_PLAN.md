# Project Plan

## Objective

Study and evaluate generative recommender approaches with a reproducible baseline and targeted research tracks.

## Phases

1. `Phase_0` - Shared baseline and protocol freeze.
2. `Phase_1` - Parallel research by selected directions.
3. `Phase_2` - Consolidation, comparison, and final write-up.

## Phase_0 Checklist

- Freeze dataset and split rules.
- Freeze metric definitions.
- Run baseline and collect metrics.
- Register run in `experiments/registry.csv`.
- Publish `baseline_report.md`.

## Phase_1 Structure

- Each member owns one research question.
- Experiments must reuse the Phase_0 protocol.
- Every run must be logged in `experiments/registry.csv`.
- Report deltas vs baseline, not isolated absolute values only.

## Phase_2 Outputs

- Unified comparison table across tracks.
- Discussion of tradeoffs (quality, robustness, tail behavior, practicality).
- Final recommendations for real-world adoption constraints.

## Roles (Template)

- `Phase_0 owner`: protocol freeze and baseline reproducibility.
- `Track owners`: one owner per research direction.
- `Integration owner`: merges final results and report narrative.

## Definition of Done

- Reproducible baseline exists and is accepted.
- All track results are comparable under one protocol.
- Final report includes evidence-backed conclusions and limitations.

