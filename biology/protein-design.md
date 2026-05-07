# Protein Design

Generative models and language models for protein sequence and structure design.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#awesome-lists">Awesome Lists</a>
  <a class="hub-page-nav-btn" href="#getting-started">Getting Started</a>
</div>

## Tools

### Generative Design

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/dauparas/ProteinMPNN" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ProteinMPNN</span>
    <span class="hub-tool-desc">Message passing for inverse folding</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/RosettaCommons/RFdiffusion" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">RFDiffusion</span>
    <span class="hub-tool-desc">Diffusion model for backbone generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/sokrypton/ColabDesign" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ColabDesign</span>
    <span class="hub-tool-desc">Notebooks for AfDesign, TrDesign, ProteinMPNN</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/facebookresearch/esm#inverse-folding-" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ESM-IF1</span>
    <span class="hub-tool-desc">Inverse folding with ESM</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/microsoft/evodiff" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">EvoDiff</span>
    <span class="hub-tool-desc">Discrete diffusion for sequences</span>
  </a>
  <a class="hub-tool-card" href="https://huggingface.co/nferruz/ProtGPT2" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ProtGPT2</span>
    <span class="hub-tool-desc">GPT-2 based sequence generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/martinpacesa/BindCraft" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">BindCraft</span>
    <span class="hub-tool-desc">Binder design</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/BytedProtein/ByProt" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">LM-Design / ByProt</span>
    <span class="hub-tool-desc">Language model design</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/ostrokach/proteinsolver" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ProteinSolver</span>
    <span class="hub-tool-desc">Graph neural network for constraint-based design</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/luoyunan/ECNet" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ECNet</span>
    <span class="hub-tool-desc">Fine-tunable fitness/function prediction</span>
  </a>
</div>

### Protein Language Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/facebookresearch/esm" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ESM-2</span>
    <span class="hub-tool-desc">Protein embeddings (8M–15B params)</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/agemagician/ProtTrans" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ProtTrans</span>
    <span class="hub-tool-desc">Transformer embeddings for proteins</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/chandar-lab/AMPLIFY" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AMPLIFY</span>
    <span class="hub-tool-desc">ESM2 reimplementation with open training</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/OpenProteinAI/PoET" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">PoET</span>
    <span class="hub-tool-desc">Variant effect prediction and generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/NREL/EvoProtGrad" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">EvoProtGrad</span>
    <span class="hub-tool-desc">MCMC-based directed evolution</span>
  </a>
</div>

---

## Communities

### [OpenBioML](https://www.openbioml.org/)

Decentralized collaborative research community for open source ML and open science to accelerate biotechnology.

- **Focus:** Biotechnology, drug discovery, protein engineering
- **Platform:** Discord

### Key Research Groups

- **Baker Lab** (UW) — Protein design
- **Coley Group** (MIT) — Synthesis planning, ML for chemistry

---

## Awesome Lists

<div class="hub-awesome-grid">
  <a class="hub-awesome-item" href="https://github.com/johnnytam100/awesome-protein-design" target="_blank" rel="noopener noreferrer">Protein design papers</a>
  <a class="hub-awesome-item" href="https://github.com/pansapiens/awesome-protein-design-software" target="_blank" rel="noopener noreferrer">Protein design tools</a>
  <a class="hub-awesome-item" href="https://github.com/opendilab/awesome-AI-based-protein-design" target="_blank" rel="noopener noreferrer">AI protein design</a>
</div>

---

## Getting Started

```bash
conda create -n protdesign python=3.10
conda activate protdesign

pip install fair-esm biopython
```
