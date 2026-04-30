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

### Single-Cell Foundation Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/bowang-lab/scGPT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">scGPT</span>
    <span class="hub-tool-desc">Transformer model for single-cell</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/biomap-research/scFoundation" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">scFoundation</span>
    <span class="hub-tool-desc">Foundation model for single-cell data</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/cantinilab/scPRINT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">scPRINT</span>
    <span class="hub-tool-desc">Cell imputation model</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/yiqunchen/GenePT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GenePT</span>
    <span class="hub-tool-desc">GPT-based gene embeddings</span>
  </a>
</div>

### Biomedical Language Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/microsoft/BioGPT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">BioGPT</span>
    <span class="hub-tool-desc">Biomedical text generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/ncbi/GeneGPT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GeneGPT</span>
    <span class="hub-tool-desc">Biomedical information system</span>
  </a>
</div>

### Benchmarking

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://openproblems.bio/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Open Problems</span>
    <span class="hub-tool-desc">Community benchmarking for single-cell tasks (batch integration, denoising, label projection)</span>
  </a>
</div>

---

## Datasets

### Atlases & Repositories

<div class="hub-dataset-grid">
  <a class="hub-dataset-card" href="https://www.ncbi.nlm.nih.gov/geo/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">Gene Expression Omnibus</span>
    <span class="hub-dataset-desc">Public functional genomics data</span>
  </a>
  <a class="hub-dataset-card" href="https://www.ebi.ac.uk/gxa/sc/home" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">Single Cell Expression Atlas</span>
    <span class="hub-dataset-desc">scRNA atlas (EBI)</span>
  </a>
  <a class="hub-dataset-card" href="https://singlecell.broadinstitute.org/single_cell" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">Single Cell Portal</span>
    <span class="hub-dataset-desc">Single cell RNA data (Broad)</span>
  </a>
  <a class="hub-dataset-card" href="https://www.10xgenomics.com/resources/datasets" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">10x Genomics Datasets</span>
    <span class="hub-dataset-desc">Single-cell datasets</span>
  </a>
</div>

### Functional Genomics

<div class="hub-dataset-grid">
  <a class="hub-dataset-card" href="https://gtexportal.org/home/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">GTEx</span>
    <span class="hub-dataset-desc">Gene expression and regulation across human tissues</span>
  </a>
  <a class="hub-dataset-card" href="https://depmap.org/portal/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">DepMap</span>
    <span class="hub-dataset-desc">CRISPR screens in cancer cells</span>
  </a>
</div>

### Benchmarks

<div class="hub-dataset-grid">
  <a class="hub-dataset-card" href="https://openproblems.bio/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">Open Problems</span>
    <span class="hub-dataset-desc">Standardized benchmarks for single-cell tasks</span>
  </a>
</div>

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
