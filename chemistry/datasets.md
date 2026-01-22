# Chemistry Datasets

Benchmark datasets for molecular property prediction, reactions, and more.

## Molecular Property Prediction

| Dataset | Task | Size | Link |
|---------|------|------|------|
| **MoleculeNet** | Multiple benchmark tasks | 700K+ molecules | [Paper](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c7sc02664a) |
| **TDC** | Drug discovery benchmarks | Various | [tdcommons.ai](https://tdcommons.ai/) |
| **ZINC** | Virtual screening library | 250M+ | [zinc.docking.org](https://zinc.docking.org/) |

---

## Reactions

| Dataset | Task | Size | Link |
|---------|------|------|------|
| **USPTO** | Reaction prediction | 1M+ reactions | [github](https://github.com/rxn4chemistry/rxnfp) |
| **Open Reaction Database** | Open reactions | Growing | [open-reaction-database.org](https://open-reaction-database.org/) |

---

## Dataset Collections

| Resource | Description |
|----------|-------------|
| [awesome-chemistry-datasets](https://github.com/kjappelbaum/awesome-chemistry-datasets) | Curated list of ML-ready chemistry datasets |
| [TDC](https://tdcommons.ai/) | Therapeutics Data Commons — drug discovery datasets |

---

## Data Formats

Common formats you'll encounter:

| Format | Description | Tool |
|--------|-------------|------|
| **SMILES** | String representation of molecules | RDKit |
| **SDF/MOL** | 3D structure files | RDKit, OpenBabel |
| **InChI** | Unique molecular identifier | RDKit |

## Loading Data with RDKit

```python
from rdkit import Chem
import pandas as pd

# From SMILES
mol = Chem.MolFromSmiles("CCO")

# From SDF file
suppl = Chem.SDMolSupplier("molecules.sdf")
mols = [mol for mol in suppl if mol is not None]

# From CSV with SMILES column
df = pd.read_csv("molecules.csv")
df["mol"] = df["smiles"].apply(Chem.MolFromSmiles)
```
