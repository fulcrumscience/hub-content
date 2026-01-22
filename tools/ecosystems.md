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

---

## Awesome Lists

Curated resource collections for finding more tools and papers.

### General

| List | Focus |
|------|-------|
| [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) | AI tools for scientific research |

### Chemistry & Drug Discovery

| List | Focus |
|------|-------|
| [awesome-cheminformatics](https://github.com/hsiaoyi0504/awesome-cheminformatics) | Cheminformatics tools |
| [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) | Python chemistry tools |
| [awesome-chemistry-datasets](https://github.com/kjappelbaum/awesome-chemistry-datasets) | ML datasets |
| [awesome-drug-discovery](https://github.com/yboulaamane/awesome-drug-discovery) | Drug discovery |
| [awesome-molecular-generation](https://github.com/amorehead/awesome-molecular-generation) | Molecular generation |

### Biology & Proteins

| List | Focus |
|------|-------|
| [awesome-protein-design](https://github.com/johnnytam100/awesome-protein-design) | Protein design papers |
| [awesome-protein-design-software](https://github.com/pansapiens/awesome-protein-design-software) | Protein design tools |
| [awesome-computational-biology](https://github.com/inoue0426/awesome-computational-biology) | Computational biology |

### Materials Science

| List | Focus |
|------|-------|
| [awesome-materials-informatics](https://github.com/tilde-lab/awesome-materials-informatics) | Materials informatics |
| [Best of Atomistic ML](https://github.com/JuDFTteam/best-of-atomistic-machine-learning) | Atomistic ML |

### Methods & ML

| List | Focus |
|------|-------|
| [awesome-scientific-language-models](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models) | Scientific LLMs |
| [awesome-scientific-machine-learning](https://github.com/MartinuzziFrancesco/awesome-scientific-machine-learning) | SciML resources |
| [awesome-pinn](https://github.com/idrl-lab/awesome-pinn) | Physics-informed NNs |
