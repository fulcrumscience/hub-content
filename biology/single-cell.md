# Single-Cell & Genomics

Tools and datasets for single-cell RNA sequencing, spatial transcriptomics, and gene expression analysis.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#datasets">Datasets</a>
  <a class="hub-page-nav-btn" href="#awesome-lists">Awesome Lists</a>
  <a class="hub-page-nav-btn" href="#getting-started">Getting Started</a>
</div>

## Tools

### Analysis Frameworks

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://scanpy.readthedocs.io/en/stable/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Scanpy</span>
    <span class="hub-tool-desc">Single-cell analysis in Python</span>
  </a>
  <a class="hub-tool-card" href="https://satijalab.org/seurat/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Seurat</span>
    <span class="hub-tool-desc">Single-cell analysis in R</span>
  </a>
  <a class="hub-tool-card" href="https://squidpy.readthedocs.io/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Squidpy</span>
    <span class="hub-tool-desc">Spatial transcriptomics analysis</span>
  </a>
</div>

### Foundation Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/bowang-lab/scGPT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">scGPT</span>
    <span class="hub-tool-desc">Transformer model for single-cell</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/biomap-research/scFoundation" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">scFoundation</span>
    <span class="hub-tool-desc">Foundation model</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/cantinilab/scPRINT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">scPRINT</span>
    <span class="hub-tool-desc">Cell imputation model</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/microsoft/BioGPT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">BioGPT</span>
    <span class="hub-tool-desc">Biomedical text generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/ncbi/GeneGPT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GeneGPT</span>
    <span class="hub-tool-desc">Biomedical information system</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/yiqunchen/GenePT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GenePT</span>
    <span class="hub-tool-desc">Foundation model</span>
  </a>
</div>

### Benchmarking

| Resource | Description |
|----------|-------------|
| [**Open Problems**](https://openproblems.bio/) | Community benchmarking for single-cell tasks (batch integration, denoising, label projection) |

---

## Datasets

| Dataset | Description |
|---------|-------------|
| [**Gene Expression Omnibus**](https://www.ncbi.nlm.nih.gov/geo/) | Public functional genomics data |
| [**Single Cell Portal**](https://singlecell.broadinstitute.org/single_cell) | Single cell RNA data |
| [**Single Cell Expression Atlas**](https://www.ebi.ac.uk/gxa/sc/home) | scRNA atlas |
| [**10x Genomics Datasets**](https://www.10xgenomics.com/resources/datasets) | Single-cell datasets |
| [**GTEx**](https://gtexportal.org/home/) | Gene expression and regulation |
| [**DepMap**](https://depmap.org/portal/) | CRISPR screens in cancer cells |
| [**Open Problems**](https://openproblems.bio/) | Standardized benchmarks for single-cell tasks |

---

## Awesome Lists

<div class="hub-awesome-grid">
  <a class="hub-awesome-item" href="https://github.com/inoue0426/awesome-computational-biology" target="_blank" rel="noopener noreferrer">Computational biology resources</a>
</div>

---

## Getting Started

```bash
conda create -n singlecell python=3.10
conda activate singlecell

pip install scanpy squidpy jupyter
```
