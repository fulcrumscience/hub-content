# Chemistry Tutorials

Hands-on notebooks and practical guides for cheminformatics and computational chemistry.

## Featured Tutorials

### Practical Cheminformatics
**[github.com/PatWalters/practical_cheminformatics_tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)**

**Patrick Walters** — Jupyter & Colab notebooks covering clustering, SAR analysis, ML, and active learning.

### TeachOpenCADD Talktorials
**[projects.volkamerlab.org/teachopencadd/talktorials.html](https://projects.volkamerlab.org/teachopencadd/talktorials.html)**

**Volkamer Lab** — Comprehensive "talktorials" (talk + tutorial) covering computer-aided drug design from basics to advanced topics.

### Neural Networks for Chemists
**[github.com/omics101/acs-neural-networks](https://github.com/omics101/acs-neural-networks)**

**ACS In Focus (2024)** — First-step knowledge for applying neural networks in chemistry research.

---

## Tutorial Directory

### Cheminformatics Basics

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Practical Cheminformatics](https://github.com/PatWalters/practical_cheminformatics_tutorials) | Fingerprints, clustering, SAR | Jupyter/Colab |
| [TeachOpenCADD T001-T010](https://projects.volkamerlab.org/teachopencadd/talktorials.html) | Molecular data, fingerprints, similarity | Jupyter |
| [RDKit Cookbook](https://www.rdkit.org/docs/Cookbook.html) | RDKit fundamentals | Documentation |

### Machine Learning for Chemistry

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Neural Networks for Chemists](https://github.com/omics101/acs-neural-networks) | NN fundamentals for chemistry | Jupyter |
| [Transformers for Chemistry](https://github.com/lamalab-org/llm-tutorial) | LLMs, transformers | Jupyter |
| [DeepChem Tutorials](https://deepchem.io/tutorials/) | GNNs, molecular property prediction | Jupyter |

### Reaction Prediction

| Tutorial | Topics | Format |
|----------|--------|--------|
| [AI4Chemistry Course Labs](https://github.com/schwallergroup/ai4chem_course) | Reaction prediction, retrosynthesis | Jupyter |

---

## Running Tutorials

> **Google Colab:** Most tutorials can be run directly in Google Colab without local setup. Look for the "Open in Colab" badge.

### Local Setup

```bash
# Create a conda environment
conda create -n chem python=3.10
conda activate chem

# Install core dependencies
pip install rdkit jupyter pandas numpy scikit-learn

# For deep learning
pip install torch deepchem
```
