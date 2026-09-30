# ROU-TransQA-v2 Anonymous Reproducibility Package

This package contains the source code, configuration files, data-placement notes, verification records, tests, and reproducibility documentation for the ROU-TransQA-v2 contract question-answering workflow.

## Package contents

- `src/rou_transqa/` — Python modules for data handling, model components, decoding, evaluation metrics, calibration, statistical analysis, indicator mapping, runtime utilities, and file I/O.
- `scripts/` — command-line scripts for data preparation, training, evaluation, calibration, threshold selection, baseline execution, ablation execution, external-set evaluation, paired bootstrap analysis, seed aggregation, figure generation, repository checks, and related workflow tasks.
- `configs/` — YAML configuration files for the main workflow, baselines, ablations, and external validation.
- `tests/` — deterministic tests for data processing, calibration, statistics, indicator mapping, and evaluation metrics.
- `data/` — raw-data and processed-data placement directories, together with notes describing the expected public-data files and external validation schema.
- `records/manuscript_reported/` — machine-readable tables and metadata associated with the manuscript reporting workflow.
- `logs/verification/` — repository, pipeline, and unit-test verification logs.
- `reproducibility/` — the package manifest, anonymity notes, result-provenance documentation, and JSON schema files.
- `outputs/` — the location for files generated when the workflow is executed; the package includes only the directory placeholder.
- `requirements.txt` — pinned Python dependencies.
- `environment.yml` — conda environment specification.
- `pyproject.toml` — package metadata, build settings, dependency groups, and source-package discovery settings.
- `Dockerfile` — container build specification.
- `Makefile` — project command definitions.
- `.gitignore` — repository ignore rules.
- `LICENSE` — MIT license text.

## Main source modules

The `rou_transqa` package includes modules for dataset access and validation, configuration and runtime handling, model definition, span decoding, metric computation, probability calibration, statistical procedures, D1–D6 indicator mapping, analysis utilities, and serialization helpers.

## Data and schema files

The package does not include raw contract text or confidential enterprise contracts. The `data/` directory contains placement instructions and placeholder directories. The JSON schema under `reproducibility/schema/` describes the expected structure of the de-identified external-validation file.

## Documentation and verification materials

The reproducibility directory documents package structure, anonymity constraints, and provenance conventions. The verification logs record software-check outputs, while the test suite contains the corresponding deterministic checks.

