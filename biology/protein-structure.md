# Protein Structure

Structure prediction tools, multimer prediction, and structural databases.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#datasets">Datasets</a>
  <a class="hub-page-nav-btn" href="#getting-started">Getting Started</a>
</div>

## Tools

### Structure Prediction

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/google-deepmind/alphafold3" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AlphaFold3</span>
    <span class="hub-tool-desc">Advanced modeling with ligands, nucleotides, PTMs</span>
  </a>
  <a class="hub-tool-card" href="https://alphafold.ebi.ac.uk/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AlphaFold2</span>
    <span class="hub-tool-desc">Protein structure prediction</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/facebookresearch/esm" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ESM/ESMFold</span>
    <span class="hub-tool-desc">Protein language models & fast structure prediction</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/sokrypton/ColabFold" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ColabFold</span>
    <span class="hub-tool-desc">Community notebooks for AF2, ESMFold, RoseTTAFold</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/aqlaboratory/openfold" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">OpenFold</span>
    <span class="hub-tool-desc">PyTorch reimplementation of AlphaFold2</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/RosettaCommons/RoseTTAFold" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">RoseTTAFold</span>
    <span class="hub-tool-desc">Three-track neural network for structure</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/HeliXonProtein/OmegaFold" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">OmegaFold</span>
    <span class="hub-tool-desc">Single-sequence structure prediction</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/jwohlwend/boltz" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Boltz-1</span>
    <span class="hub-tool-desc">Unified prediction for proteins, RNA, DNA, ligands</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/chaidiscovery/chai-lab" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Chai-1</span>
    <span class="hub-tool-desc">Proteins, small molecules, DNA, RNA with restraints</span>
  </a>
</div>

### Multimer & Complex Prediction

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/deepmind/alphafold" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AlphaFold2-Multimer</span>
    <span class="hub-tool-desc">Protein complex prediction</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/KosinskiLab/AlphaPulldown" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AlphaPulldown</span>
    <span class="hub-tool-desc">Protein-protein interaction screening</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/FreshAirTonight/af2complex" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AF2Complex</span>
    <span class="hub-tool-desc">Complex assembly</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/LBM-EPFL/PeSTo" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">PeSTo</span>
    <span class="hub-tool-desc">Interface residue prediction</span>
  </a>
</div>

### Visualization & Analysis

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://pymol.org/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">PyMOL</span>
    <span class="hub-tool-desc">Molecular visualization</span>
  </a>
  <a class="hub-tool-card" href="https://www.rbvi.ucsf.edu/chimerax/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ChimeraX</span>
    <span class="hub-tool-desc">Molecular visualization for structural biology</span>
  </a>
  <a class="hub-tool-card" href="https://biopython.org/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">BioPython</span>
    <span class="hub-tool-desc">Python tools for biological computation</span>
  </a>
  <a class="hub-tool-card" href="http://prody.csb.pitt.edu/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ProDy</span>
    <span class="hub-tool-desc">Protein dynamics analysis</span>
  </a>
</div>

---

## Datasets

| Dataset | Description | Size |
|---------|-------------|------|
| [**AlphaFold DB**](https://alphafold.ebi.ac.uk/) | Predicted protein structures | 200M+ structures |
| [**PDB**](https://www.rcsb.org/) | Experimental structures | 200K+ |
| [**UniProt**](https://www.uniprot.org/) | Protein sequences & functions | 250M+ |
| [**CATH**](https://www.cathdb.info/) | Protein domain classification | — |
| [**Human Protein Atlas**](https://www.proteinatlas.org/) | Protein expression data | — |
| [**Uniclust**](https://uniclust.mmseqs.com/) | Clustered protein sequences | — |

---

## Getting Started

```bash
conda create -n proteins python=3.10
conda activate proteins

pip install biopython fair-esm
```
