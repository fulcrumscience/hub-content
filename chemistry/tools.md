# Chemistry Tools

Software libraries and frameworks for cheminformatics and computational chemistry.

## Cheminformatics Stack

| Tool | Description | Link |
|------|-------------|------|
| **RDKit** | Core cheminformatics toolkit — the foundation of most chemistry ML | [rdkit.org](https://www.rdkit.org/) |
| **OpenBabel** | Format conversion, 3D generation | [openbabel.org](http://openbabel.org/) |
| **CDK** | Java-based cheminformatics toolkit | [cdk.github.io](https://cdk.github.io/) |
| **Datamol** | RDKit wrapper optimized for data science workflows | [datamol.io](https://datamol.io/) |

---

## Deep Learning for Molecules

| Tool | Description | Link |
|------|-------------|------|
| **DeepChem** | Comprehensive ML library for chemistry and life sciences | [deepchem.io](https://deepchem.io/) |
| **PyTorch Geometric** | Graph neural networks framework | [pyg.org](https://pyg.org/) |
| **DGL-LifeSci** | GNN library for life science applications | [github](https://github.com/awslabs/dgl-lifesci) |
| **Chemprop** | Message passing neural networks for molecular property prediction | [github](https://github.com/chemprop/chemprop) |

---

## Specialized Tools

### Reaction Prediction
- **RXNMapper** — Atom mapping for reactions
- **rxnfp** — Reaction fingerprints

### Molecular Generation
- **REINVENT** — Reinforcement learning for molecular design
- **GuacaMol** — Benchmarks for generative models

### Visualization
- **py3Dmol** — 3D molecular visualization in Jupyter
- **mols2grid** — Interactive molecule grids

---

## Getting Started

```bash
# Install core chemistry stack
conda create -n chem python=3.10
conda activate chem

# RDKit (via conda-forge)
conda install -c conda-forge rdkit

# Additional tools
pip install datamol deepchem
```
