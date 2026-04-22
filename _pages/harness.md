---
title: "Harness"
layout: single
permalink: /harness/
classes: wide
---

## NeuroBench harness

The NeuroBench harness is an open-source Python package for standardized benchmark execution across neuromorphic tasks.

- GitHub: [NeuroBench/neurobench](https://github.com/NeuroBench/neurobench)
- Documentation: [Read the Docs](https://neurobench.readthedocs.io/en/latest/)
- PyPI: [neurobench](https://pypi.org/project/neurobench/)

## Evaluation pipeline

A benchmark run follows a modular flow:

`Data -> Preprocess -> Model -> Postprocess -> Metrics -> Results`

This structure keeps benchmark definitions readable and enables consistent reporting.

## Core components

- `neurobench.benchmarks`: benchmark orchestration
- `neurobench.datasets`: benchmark datasets
- `neurobench.models`: wrappers for Torch and SNNTorch models
- `neurobench.preprocessing`: preprocessing interfaces
- `neurobench.postprocessing`: postprocessing interfaces
- `neurobench.metrics`: static and workload metrics

## Quick start

```bash
pip install neurobench
```

Then follow the API and tutorial docs:

- [API overview](https://neurobench.readthedocs.io/en/latest/api.html)
- [Tutorial index](https://neurobench.readthedocs.io/en/latest/tutorial/index.html)
- [Contributing guide](https://neurobench.readthedocs.io/en/latest/contributing.html)

## Citation

Use the project citation from the paper page:

- [NeuroBench paper (Nature Communications)](https://www.nature.com/articles/s41467-025-56739-4)
- [Project DOI](https://doi.org/10.5281/zenodo.14477064)
