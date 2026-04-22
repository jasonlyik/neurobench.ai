---
title: "Benchmarks"
layout: single
permalink: /benchmarks/
classes: wide
---

## Dual-track benchmark design

NeuroBench organizes evaluations in two complementary tracks:

- **Algorithm track:** hardware-independent benchmarking for correctness and complexity.
- **System track:** deployment-aware timing and efficiency benchmarking.

## Algorithm track

<ul class="nb-benchmark-columns">
	<li>Keyword FSCIL</li>
	<li>Event Camera Object Detection</li>
	<li>NHP Motor Prediction</li>
	<li>Chaotic Function Prediction</li>
	<li>GSC</li>
	<li>DVS Gesture</li>
	<li>NeHAR</li>
</ul>

Algorithm benchmarks: [github.com/NeuroBench/neurobench](https://github.com/NeuroBench/neurobench)

## System track

<ul>
	<li>Acoustic Scene Classification</li>
	<li>Quadratic Unconstrained Binary Optimization (QUBO)</li>
</ul>
System benchmarks: [github.com/NeuroBench/system_benchmarks](https://github.com/NeuroBench/system_benchmarks)

## Metrics coverage

Each benchmark run can report metrics across correctness and efficiency dimensions.

- **Static metrics:** Model Footprint, Parameter Count, Connection Sparsity, Model Execution Rate
- **Workload metrics:** Classification Accuracy, COCO mAP, R2, sMAPE, MSE, Activation Sparsity, Synaptic Operations, Membrane Updates, Neuron Operations

See full metric documentation in the harness docs:
[Static metrics](https://neurobench.readthedocs.io/en/latest/metrics/static_metrics/index.html) and [Workload metrics](https://neurobench.readthedocs.io/en/latest/metrics/workload_metrics/index.html).

## Learn more

- [Harness overview](/harness/)
- [Get involved](/get-involved/)
- [NeuroBench paper (Nature Communications)](https://www.nature.com/articles/s41467-025-56739-4)
