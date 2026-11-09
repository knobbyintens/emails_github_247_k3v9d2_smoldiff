# SmolDiff: Distilled Diffusion for Real-Time Image Editing

**Status: code released.**

This repository contains the implementation for the paper:

> **SmolDiff: Distilled Diffusion for Real-Time Image Editing**  
> Victoria Ramos, Wei Zhang, Priya Raman  
> CVPR 2025

The released implementation covers the model, the data pipeline and the training/evaluation scripts used in the experiments.

## Repository layout

- `src/` - model, data pipeline, training and evaluation code
- `data/` - dataset preparation helpers and manifests
- `experiments/` - experiment configs and analysis notebooks

## Getting started

```bash
pip install -r requirements.txt
python -m src.train --config configs/default.yaml
```

## Citation

If you use this code, please cite the paper above.
