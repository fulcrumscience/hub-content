# Materials Tools

Software libraries for materials science and atomistic simulations.

## Core Materials Stack

| Tool | Description | Link |
|------|-------------|------|
| **pymatgen** | Python Materials Genomics — analysis and manipulation | [pymatgen.org](https://pymatgen.org/) |
| **matminer** | Data mining and ML for materials | [hackingmaterials.lbl.gov/matminer](https://hackingmaterials.lbl.gov/matminer/) |
| **ASE** | Atomic Simulation Environment | [wiki.fysik.dtu.dk/ase](https://wiki.fysik.dtu.dk/ase/) |
| **JARVIS** | Integrated workflows for materials | [jarvis.nist.gov](https://jarvis.nist.gov/) |

---

## Neural Network Potentials

| Tool | Description | Link |
|------|-------------|------|
| **MACE** | Message passing neural network potentials | [github](https://github.com/ACEsuit/mace) |
| **NequIP** | E(3)-equivariant neural network potentials | [github](https://github.com/mir-group/nequip) |
| **SchNet** | Deep learning for molecules and materials | [github](https://github.com/atomistic-machine-learning/schnetpack) |

---

## Visualization

| Tool | Description | Link |
|------|-------------|------|
| **VESTA** | 3D crystal structure visualization | [jp-minerals.org/vesta](https://jp-minerals.org/vesta/) |
| **py3Dmol** | 3D visualization in Jupyter | [github](https://github.com/3dmol/3Dmol.js) |

---

## Getting Started

```bash
conda create -n materials python=3.10
conda activate materials

# Core stack
pip install pymatgen matminer ase

# For ML
pip install torch scikit-learn
```
