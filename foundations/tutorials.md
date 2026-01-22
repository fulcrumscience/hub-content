# Foundational Tutorials

Hands-on notebooks for learning programming and ML fundamentals.

## Machine Learning

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Neural Networks: Zero to Hero](https://github.com/karpathy/nn-zero-to-hero) | NN fundamentals, backprop, transformers | Video + Jupyter |
| [DeepChem Tutorials](https://deepchem.io/tutorials/) | GNNs, molecular property prediction | Jupyter |

## Python & Scientific Computing

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Scientific Computing for Chemists](https://weisscharlesj.github.io/SciCompforChemists/notebooks/introduction/intro.html) | Python basics, NumPy, Pandas | Jupyter |
| [MolSSI Python Scripting](https://github.com/MolSSI-Education/python_scripting_cms) | Python for molecular sciences | Jupyter |

---

## Running Tutorials

> **Google Colab:** Most tutorials can be run directly in Google Colab without local setup. Look for the "Open in Colab" badge.

### Local Setup

```bash
# Create a conda environment
conda create -n ai4science python=3.10
conda activate ai4science

# Install common dependencies
pip install jupyter pandas numpy scikit-learn matplotlib

# For deep learning
pip install torch
```
