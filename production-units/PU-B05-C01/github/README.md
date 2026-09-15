# MLOps Foundations Laboratory

This repository component supports **SRAI Book 5, Lesson 1 (PU-B05-C01)**. It demonstrates a fail-closed MLOps workflow with synthetic agricultural-risk data.

## What the notebook demonstrates

- deterministic data generation and splits;
- data acceptance and run configuration;
- baseline and candidate comparison;
- aggregate and regional slice metrics;
- immutable data and model hashes;
- interface and artifact contract tests;
- population stability monitoring;
- model card, release manifest and rollback record;
- explicit separation between technical gates and governance authorization.

## Runtime

The notebook is designed for both Google Colab and VS Code/Jupyter. It uses ordinary public Python packages and creates its outputs beneath `artifacts/pu_b05_c01/`.

## Reproduce

1. Start a clean Python runtime.
2. Open `V5_N01_mlops_foundations.ipynb`.
3. Select **Run all**.
4. Verify zero cell errors and inspect the evidence inventory.
5. Confirm that `authorized_release` remains `false` in the canonical run.

## Responsible-use boundary

All data are synthetic. This project is for education and controlled workflow demonstration only. It is not validated for decisions affecting farms, learners, patients, residents, credit, insurance or public benefits.
