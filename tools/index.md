# Tools & Software

Software ecosystems for AI in science — organized by domain.

## Overview

The AI4Science ecosystem includes tools for:

- **Data Processing** — Reading, manipulating, and featurizing scientific data
- **Machine Learning** — Training and deploying models
- **Visualization** — Exploring and presenting results
- **Workflows** — Reproducible research pipelines

## Tools by Domain

| Domain | Key Tools |
|--------|-----------|
| [Chemistry](/chemistry/tools) | RDKit, DeepChem, Chemprop |
| [Biology](/biology/tools) | DeepChem, DGL-LifeSci |
| [Materials](/materials/tools) | pymatgen, matminer, ASE |

---

## Cross-Domain Tools

### Deep Learning Frameworks

| Tool | Description | Link |
|------|-------------|------|
| **PyTorch** | Primary DL framework for science | [pytorch.org](https://pytorch.org/) |
| **PyTorch Geometric** | Graph neural networks | [pyg.org](https://pyg.org/) |
| **DeepChem** | ML for chemistry and life sciences | [deepchem.io](https://deepchem.io/) |

### Data Science

| Tool | Description | Link |
|------|-------------|------|
| **Jupyter** | Interactive notebooks | [jupyter.org](https://jupyter.org/) |
| **pandas** | Data manipulation | [pandas.pydata.org](https://pandas.pydata.org/) |
| **scikit-learn** | Classical ML | [scikit-learn.org](https://scikit-learn.org/) |

---

## Environment Setup

### Recommended: Conda

```bash
# Install miniconda
# https://docs.conda.io/en/latest/miniconda.html

# Create environment
conda create -n ai4science python=3.10
conda activate ai4science

# Install core tools
pip install jupyter pandas numpy scikit-learn matplotlib
pip install torch
```

### Google Colab

For quick experiments without local setup, use [Google Colab](https://colab.research.google.com/). Most tutorials include "Open in Colab" badges.
