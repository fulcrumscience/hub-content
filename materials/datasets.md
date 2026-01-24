# Materials Datasets

Databases and benchmark datasets for materials science ML.

## Major Databases

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **Materials Project** | DFT calculations, properties | 500K+ materials | [materialsproject.org](https://materialsproject.org/) |
| **AFLOW** | Crystal structures, properties | 3.5M+ entries | [aflowlib.org](http://www.aflowlib.org/) |
| **JARVIS-DFT** | DFT data with ML models | 40K+ materials | [jarvis.nist.gov](https://jarvis.nist.gov/) |
| **OQMD** | Open Quantum Materials Database | 1M+ entries | [oqmd.org](http://oqmd.org/) |
| **NOMAD** | Computational materials data | 19M+ calculations | [nomad-lab.eu](https://nomad-lab.eu/) |
| **Crystallography Open Database** | Open-access crystal structures | 525K+ | [crystallography.net](http://www.crystallography.net/cod/) |

---

## Large-Scale Computational Datasets

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **OMat24** | DFT for inorganic crystals (Meta) | 110M entries | [huggingface](https://huggingface.co/datasets/fairchem/OMAT24) |
| **Open Catalyst 2020** | Surface relaxations for catalysis | 1.2M relaxations | [opencatalystproject.org](https://opencatalystproject.org/) |
| **LeMat-Bulk** | Inorganic material structures | 6.7M structures | [huggingface](https://huggingface.co/datasets/LeMaterial/LeMat-Bulk) |
| **LeMat-Traj** | Inorganic material trajectories | 113M trajectories | [huggingface](https://huggingface.co/datasets/LeMaterial/LeMat-Traj) |
| **MatPES** | Structures from 300K MD simulations | ~400K structures | [matpes.ai](https://matpes.ai/) |
| **MP-ALOE** | r2SCAN DFT for universal MLIPs | ~1M calculations | [figshare](https://figshare.com/) |

---

## Molecular & QM Datasets

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **OMol25** | Molecular chemistry DFT (Meta) | 100M+ calculations | [huggingface](https://huggingface.co/facebook/OMol25) |
| **OMC25** | Molecular crystal structures | 27M+ structures | [huggingface](https://huggingface.co/facebook/OMC25) |
| **QM9** | Organic molecules with quantum properties | 134K molecules | [quantum-machine.org](http://quantum-machine.org/datasets/) |
| **ANI-1x/1ccx** | DFT + CCSD calculations | 5M + 0.5M | [MolSSI](https://qcawebapps.molssi.org/ml_datasets/) |
| **PubChemQCR** | Relaxation trajectories | 3.5M trajectories | [huggingface](https://huggingface.co/datasets/divelab/PubChemQCR) |
| **MSR-ACC/TAE25** | CCSD(T)/CBS atomization energies | 77K energies | [zenodo](https://zenodo.org/records/15387279) |

---

## Specialized Datasets

| Dataset | Focus | Link |
|---------|-------|------|
| **2D Materials (C2DB)** | 2D materials properties | [c2db.fysik.dtu.dk](https://c2db.fysik.dtu.dk/) |
| **Carbon Data** | Carbon trajectories (22.9M atoms) | [github](https://github.com/jla-gardner/carbon-data) |
| **CoRE MOF 2024** | Metal-organic frameworks | [ccdc](https://www.ccdc.cam.ac.uk/) |
| **Polymer Genome** | Polymers with properties | [khazana.gatech.edu](https://khazana.gatech.edu/) |
| **Hydrogen Storage Materials DB** | Hydrogen capacity data | [hymarc](https://datahub.hymarc.org/dataset/hydrogen-storage-materials-db) |
| **Porous Materials AI Gym** | ML for porous materials | [github](https://github.com/SimonEnsemble/porous-material-AI-gym) |

---

## Experimental Structures

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **ICSD** | Inorganic experimental structures | ~290K structures | [fiz-karlsruhe.de](https://icsd.products.fiz-karlsruhe.de/) |
| **CSD** | Organic crystal structures (Cambridge) | ~1.3M structures | [ccdc.cam.ac.uk](https://www.ccdc.cam.ac.uk/) |

---

## Benchmark Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| **MatBench** | Standardized ML benchmarks | [matbench.materialsproject.org](https://matbench.materialsproject.org/) |
| **MatBench-Discovery** | ML-guided discovery benchmark | [github](https://github.com/janosh/matbench-discovery) |
| **BOOM** | Out-of-distribution molecules (10+ tasks) | [github](https://github.com/FLASK-LLNL/BOOM) |

---

## Awesome Lists

| Resource | Description |
|----------|-------------|
| [awesome-matchem-datasets](https://github.com/blaiszik/awesome-matchem-datasets) | Materials & chemistry datasets (Blaiszik) |
| [awesome-materials-informatics](https://github.com/tilde-lab/awesome-materials-informatics) | Materials informatics software and data |

---

## Accessing Data

### Materials Project API

```python
from mp_api.client import MPRester

with MPRester("YOUR_API_KEY") as mpr:
    # Get structure by ID
    structure = mpr.get_structure_by_material_id("mp-149")

    # Search for materials
    docs = mpr.summary.search(
        elements=["Li", "Fe", "O"],
        num_elements=(3, 3)
    )
```

### pymatgen + matminer

```python
from matminer.datasets import load_dataset

# Load benchmark dataset
df = load_dataset("matbench_expt_gap")
```

### JARVIS

```python
from jarvis.db.figshare import data

# Get DFT dataset
dft_3d = data("dft_3d")
```
