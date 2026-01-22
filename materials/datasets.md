# Materials Datasets

Databases and benchmark datasets for materials science ML.

## Major Databases

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **Materials Project** | DFT calculations, properties | 150K+ materials | [materialsproject.org](https://materialsproject.org/) |
| **AFLOW** | Crystal structures, properties | 3.5M+ entries | [aflowlib.org](http://www.aflowlib.org/) |
| **JARVIS-DFT** | DFT data with ML models | 75K+ materials | [jarvis.nist.gov](https://jarvis.nist.gov/) |
| **OQMD** | Open Quantum Materials Database | 1M+ entries | [oqmd.org](http://oqmd.org/) |
| **Crystallography Open Database** | Open-access crystal structures | 500K+ | [crystallography.net](http://www.crystallography.net/cod/) |

---

## Specialized Datasets

| Dataset | Focus | Link |
|---------|-------|------|
| **NOMAD** | Computational materials data | [nomad-lab.eu](https://nomad-lab.eu/) |
| **2D Materials (C2DB)** | 2D materials properties | [c2db.fysik.dtu.dk](https://c2db.fysik.dtu.dk/) |
| **Hydrogen Storage Materials DB** | Hydrogen capacity and formulas | [hymarc](https://datahub.hymarc.org/dataset/hydrogen-storage-materials-db) |
| **MD Simulated Monomer Properties** | Properties for 410 monomers | [alcf](https://acdc.alcf.anl.gov/mdf/detail/elwood_md_v1.2/) |
| **Porous Materials AI Gym** | ML datasets for porous materials | [github](https://github.com/SimonEnsemble/porous-material-AI-gym) |

---

## Benchmark Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| **MatBench** | Standardized ML benchmarks for materials | [matbench.materialsproject.org](https://matbench.materialsproject.org/) |
| **MatBench-Discovery** | Benchmark for ML-guided discovery | [github](https://github.com/janosh/matbench-discovery) |

---

## Related Resources

| Resource | Description |
|----------|-------------|
| [awesome-materials-informatics](https://github.com/tilde-lab/awesome-materials-informatics) | Overview of materials informatics software and data |

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
