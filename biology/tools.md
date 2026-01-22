# Biology Tools

Software libraries for drug discovery and computational biology.

## Deep Learning for Life Sciences

| Tool | Description | Link |
|------|-------------|------|
| **DeepChem** | Comprehensive ML library for drug discovery | [deepchem.io](https://deepchem.io/) |
| **DGL-LifeSci** | GNN library for life science applications | [github](https://github.com/awslabs/dgl-lifesci) |
| **Chemprop** | Message passing neural networks | [github](https://github.com/chemprop/chemprop) |
| **TorchDrug** | GNN-based drug discovery library | [torchdrug.ai](https://torchdrug.ai/) |
| **DeepPurpose** | Deep learning for drug-target interaction | [github](https://github.com/kexinhuang12345/DeepPurpose) |

---

## Protein Structure & Analysis

| Tool | Description | Link |
|------|-------------|------|
| **AlphaFold** | Protein structure prediction | [alphafold.ebi.ac.uk](https://alphafold.ebi.ac.uk/) |
| **ESM/ESMFold** | Protein language models & structure prediction | [github](https://github.com/facebookresearch/esm) |
| **PyMOL** | Molecular visualization | [pymol.org](https://pymol.org/) |
| **ChimeraX** | Molecular visualization for structural biology | [rbvi.ucsf.edu](https://www.rbvi.ucsf.edu/chimerax/) |
| **BioPython** | Python tools for biological computation | [biopython.org](https://biopython.org/) |

---

## Single-Cell Analysis

| Tool | Description | Link |
|------|-------------|------|
| **Scanpy** | Single-cell analysis in Python | [scanpy.readthedocs.io](https://scanpy.readthedocs.io/en/stable/) |
| **Seurat** | Single-cell analysis in R | [satijalab.org/seurat](https://satijalab.org/seurat/) |
| **Squidpy** | Spatial transcriptomics analysis | [squidpy.readthedocs.io](https://squidpy.readthedocs.io/) |
| **scGPT** | Transformer model for single-cell | [github](https://github.com/bowang-lab/scGPT) |
| **scFoundation** | Single-cell foundation model | [github](https://github.com/biomap-research/scFoundation) |
| **scPRINT** | Cell imputation model | [github](https://github.com/cantinilab/scPRINT) |

---

## Drug Discovery Platforms

| Tool | Description | Link |
|------|-------------|------|
| **RDKit** | Core cheminformatics toolkit | [rdkit.org](https://www.rdkit.org/) |
| **Open Drug Discovery Toolkit** | ADMET prediction | [github](https://github.com/oddt/oddt) |
| **TDC** | Therapeutics Data Commons | [tdcommons.ai](https://tdcommons.ai/) |

---

## Drug-Target Interaction

| Tool | Description | Link |
|------|-------------|------|
| **NeoDTI** | Drug-target interaction prediction | [github](https://github.com/FangpingWan/NeoDTI) |
| **TransformerCPI** | Transformer for compound-protein interaction | [github](https://github.com/lifanchen-simm/transformerCPI) |
| **drGAT** | Attention-based drug response predictor | [github](https://github.com/inoue0426/drGAT) |

---

## Biological Language Models

| Model | Description | Link |
|-------|-------------|------|
| **ESM-2** | Protein embedding models | [github](https://github.com/facebookresearch/esm) |
| **ChemBERTa-2** | Chemical SMILES embeddings | [github](https://github.com/seyonechithrananda/bert-loves-chemistry) |
| **BioGPT** | Biomedical text generation | [github](https://github.com/microsoft/BioGPT) |
| **GeneGPT** | Biomedical information system | [github](https://github.com/ncbi/GeneGPT) |
| **GenePT** | Single-cell foundation model | [github](https://github.com/yiqunchen/GenePT) |

---

## Network & Pathway Analysis

| Tool | Description | Link |
|------|-------------|------|
| **STRING** | Protein-protein interaction networks | [string-db.org](https://string-db.org/) |
| **Cytoscape** | Network visualization and analysis | [cytoscape.org](https://cytoscape.org/) |
| **PathwayCommons** | Biological pathway data | [pathwaycommons.org](https://www.pathwaycommons.org/) |

---

## Awesome Lists

| List | Focus |
|------|-------|
| [awesome-computational-biology](https://github.com/inoue0426/awesome-computational-biology) | Computational biology resources |
| [awesome-small-molecule-ml](https://github.com/benb111/awesome-small-molecule-ml) | Drug discovery ML |
| [awesome-drug-discovery](https://github.com/yboulaamane/awesome-drug-discovery) | Drug discovery tools |

---

## Getting Started

```bash
conda create -n bio python=3.10
conda activate bio

# Core tools
pip install deepchem rdkit

# For protein work
pip install biopython fair-esm

# For single-cell
pip install scanpy squidpy
```
