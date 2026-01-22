# Software Ecosystems

Complete software stacks organized by scientific domain.

## Chemistry & Cheminformatics

### Core Stack

| Tool | Purpose | Link |
|------|---------|------|
| **RDKit** | Cheminformatics foundation | [rdkit.org](https://www.rdkit.org/) |
| **OpenBabel** | Format conversion | [openbabel.org](http://openbabel.org/) |
| **Datamol** | RDKit for data science | [datamol.io](https://datamol.io/) |

### Deep Learning

| Tool | Purpose | Link |
|------|---------|------|
| **DeepChem** | ML for chemistry | [deepchem.io](https://deepchem.io/) |
| **Chemprop** | Message passing NNs | [github](https://github.com/chemprop/chemprop) |
| **DGL-LifeSci** | GNNs for life science | [github](https://github.com/awslabs/dgl-lifesci) |

---

## Materials Science

### Core Stack

| Tool | Purpose | Link |
|------|---------|------|
| **pymatgen** | Materials analysis | [pymatgen.org](https://pymatgen.org/) |
| **matminer** | Feature engineering | [hackingmaterials.lbl.gov/matminer](https://hackingmaterials.lbl.gov/matminer/) |
| **ASE** | Atomistic simulations | [wiki.fysik.dtu.dk/ase](https://wiki.fysik.dtu.dk/ase/) |
| **JARVIS** | Integrated workflows | [jarvis.nist.gov](https://jarvis.nist.gov/) |

### Neural Network Potentials

| Tool | Purpose | Link |
|------|---------|------|
| **MACE** | Equivariant NNPs | [github](https://github.com/ACEsuit/mace) |
| **NequIP** | E(3)-equivariant NNPs | [github](https://github.com/mir-group/nequip) |

---

## Biology & Drug Discovery

| Tool | Purpose | Link |
|------|---------|------|
| **DeepChem** | Drug discovery ML | [deepchem.io](https://deepchem.io/) |
| **BioPython** | Sequence analysis | [biopython.org](https://biopython.org/) |
| **PyMOL** | Molecular visualization | [pymol.org](https://pymol.org/) |

---

## Installation Recipes

### Chemistry Environment

```bash
conda create -n chem python=3.10
conda activate chem
conda install -c conda-forge rdkit
pip install datamol deepchem jupyter
```

### Materials Environment

```bash
conda create -n materials python=3.10
conda activate materials
pip install pymatgen matminer ase jupyter
```

### Full Stack

```bash
conda create -n ai4science python=3.10
conda activate ai4science
conda install -c conda-forge rdkit
pip install pymatgen matminer deepchem jupyter pandas scikit-learn torch
```
