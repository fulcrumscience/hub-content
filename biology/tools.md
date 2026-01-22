# Biology Tools

Software libraries for drug discovery and computational biology.

## Deep Learning for Life Sciences

| Tool | Description | Link |
|------|-------------|------|
| **DeepChem** | Comprehensive ML library for drug discovery | [deepchem.io](https://deepchem.io/) |
| **DGL-LifeSci** | GNN library for life science applications | [github](https://github.com/awslabs/dgl-lifesci) |
| **Chemprop** | Message passing neural networks | [github](https://github.com/chemprop/chemprop) |

---

## Protein Structure

| Tool | Description | Link |
|------|-------------|------|
| **AlphaFold** | Protein structure prediction | [alphafold.ebi.ac.uk](https://alphafold.ebi.ac.uk/) |
| **ESMFold** | Fast protein structure prediction | [github](https://github.com/facebookresearch/esm) |
| **PyMOL** | Molecular visualization | [pymol.org](https://pymol.org/) |

---

## Drug Discovery Platforms

| Tool | Description | Link |
|------|-------------|------|
| **RDKit** | Core cheminformatics (also used in drug discovery) | [rdkit.org](https://www.rdkit.org/) |
| **Open Drug Discovery Toolkit** | ADMET prediction | [github](https://github.com/oddt/oddt) |

---

## Getting Started

```bash
conda create -n bio python=3.10
conda activate bio

# Core tools
pip install deepchem rdkit

# For protein work
pip install biopython
```
