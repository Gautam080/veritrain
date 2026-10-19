# VeriTrain

**Investigating whether verified feedback can improve small language models through fine-tuning and execution-based evaluation.**

## Overview

VeriTrain is an experimental project exploring how supervised fine-tuning and verified feedback affect the correctness and reliability of small language models on Python code-generation tasks.

The goal is to establish reproducible baselines, compare training strategies, and measure whether model improvements generalize to unseen problems.

## Research Questions

- Does supervised fine-tuning improve code-generation performance over a pretrained baseline?
- Can execution-based feedback improve performance beyond ordinary supervised fine-tuning?
- Which types of errors benefit most from verified corrections?
- What trade-offs exist between accuracy, inference latency, and computational cost?

## Planned Approach

1. Establish a baseline using a pretrained code language model.
2. Build an evaluation harness using executable test cases.
3. Fine-tune the model using parameter-efficient methods such as LoRA.
4. Investigate training with verified corrections or preference pairs.
5. Compare results using held-out tasks and reproducible experiments.

## Technology Stack

- Python and PyTorch
- Hugging Face Transformers and Datasets
- PEFT and TRL
- Google Colab for initial GPU experiments
- Git and GitHub for version control

## Project Status

Early development. Baseline evaluation, fine-tuning experiments, and verified-feedback methods are planned.

## Reproducibility

Experiments will document model versions, dataset splits, training configurations, evaluation methods, and computational costs.

## Disclaimer

This is an independent research and learning project. No performance improvements or research novelty are claimed until supported by experimental evidence.
