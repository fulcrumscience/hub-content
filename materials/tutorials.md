# Materials Tutorials

Hands-on notebooks for materials informatics and ML.

## Featured Tutorials

### Transformers for Materials
**[github.com/lamalab-org/llm-tutorial](https://github.com/lamalab-org/llm-tutorial)**

**LlamaLab** — Tutorials on transformers in chemistry and materials science, from Kevin Jablonka's blog posts.

### matminer Tutorials
**[hackingmaterials.lbl.gov/matminer](https://hackingmaterials.lbl.gov/matminer/)**

Feature engineering for materials science with working examples.

---

## Tutorial Directory

| Tutorial | Topics | Format |
|----------|--------|--------|
| [Transformers for Materials](https://github.com/lamalab-org/llm-tutorial) | LLMs for materials | Jupyter |
| [matminer tutorials](https://hackingmaterials.lbl.gov/matminer/) | Feature engineering | Jupyter |
| [ML for Materials Course](https://aronwalsh.github.io/MLforMaterials/Overview.html) | Regression, NNPs | Jupyter |
| [Materials Informatics](https://github.com/sp8rks/MaterialsInformatics) | ML for discovery | Jupyter |

---

## Running Tutorials

```bash
# Create environment
conda create -n materials python=3.10
conda activate materials

# Install core tools
pip install pymatgen matminer ase jupyter pandas scikit-learn

# For deep learning
pip install torch
```
