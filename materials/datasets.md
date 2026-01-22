# Materials Datasets

Databases and benchmark datasets for materials science ML.

## Major Databases

| Dataset | Description | Size | Link |
|---------|-------------|------|------|
| **Materials Project** | DFT calculations, properties | 150K+ materials | [materialsproject.org](https://materialsproject.org/) |
| **AFLOW** | Crystal structures, properties | 3.5M+ entries | [aflowlib.org](http://www.aflowlib.org/) |
| **JARVIS-DFT** | DFT data with ML models | 75K+ materials | [jarvis.nist.gov](https://jarvis.nist.gov/) |
| **OQMD** | Open Quantum Materials Database | 1M+ entries | [oqmd.org](http://oqmd.org/) |

---

## Specialized Datasets

| Dataset | Focus | Link |
|---------|-------|------|
| **NOMAD** | Computational materials data | [nomad-lab.eu](https://nomad-lab.eu/) |
| **2D Materials** | 2D materials properties | [c2db.fysik.dtu.dk](https://c2db.fysik.dtu.dk/) |

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
