# Methods Tutorials

Hands-on tutorials for ML methods used in science.

## Graph Neural Networks

| Tutorial | Topics | Format |
|----------|--------|--------|
| [DeepChem Tutorials](https://deepchem.io/tutorials/) | GNNs, molecular graphs | Jupyter |
| [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/get_started/colabs.html) | General GNN tutorials | Colab |

---

## Transformers & LLMs

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Transformers for Chemistry](https://github.com/lamalab-org/llm-tutorial) | LLMs in chemistry/materials | Jupyter |
| [Neural Networks for Chemists](https://github.com/omics101/acs-neural-networks) | NN fundamentals | Jupyter |

---

## Active Learning

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Practical Cheminformatics](https://github.com/PatWalters/practical_cheminformatics_tutorials) | Active learning for drug discovery | Jupyter |

---

## Running Tutorials

```bash
conda create -n methods python=3.10
conda activate methods

# Core ML
pip install torch scikit-learn jupyter

# For GNNs
pip install torch-geometric

# For chemistry/materials
pip install deepchem rdkit
```
