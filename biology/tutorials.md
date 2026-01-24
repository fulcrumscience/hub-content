# Biology Tutorials

Hands-on notebooks for drug discovery and computational biology.

## Drug Discovery

### TeachOpenCADD — Drug Discovery Track
**[projects.volkamerlab.org/teachopencadd/talktorials.html](https://projects.volkamerlab.org/teachopencadd/talktorials.html)**

Talktorials T011-T022 cover advanced drug discovery topics:

| Talktorial | Topic |
|------------|-------|
| T011-T014 | Binding site detection, docking |
| T015-T018 | ADMET prediction |
| T019-T022 | Advanced ML for drug discovery |

### Practical Cheminformatics — Drug Discovery
**[github.com/PatWalters/practical_cheminformatics_tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)**

Notebooks covering QSAR, active learning, and practical drug discovery workflows.

---

## Tutorial Directory

| Tutorial | Topics | Format |
|----------|--------|--------|
| [TeachOpenCADD T011-T022](https://projects.volkamerlab.org/teachopencadd/talktorials.html) | Docking, binding sites, ADMET | Jupyter |
| [Practical Cheminformatics](https://github.com/PatWalters/practical_cheminformatics_tutorials) | QSAR, active learning | Jupyter |
| [DeepChem Tutorials](https://deepchem.io/tutorials/) | Molecular property prediction | Jupyter |
| [AI in Drug Discovery Course](https://srijitseal.com/AIDDCourse) | Toxicity, QSAR | Jupyter |

---

## Running Tutorials

```bash
# Create environment
conda create -n drugdiscovery python=3.10
conda activate drugdiscovery

# Install dependencies
pip install rdkit deepchem jupyter pandas scikit-learn
```
