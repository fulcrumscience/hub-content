# Molecular Generation

Generative models for drug and material design — VAEs, RL-based, diffusion, and graph-based approaches.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#datasets">Datasets</a>
  <a class="hub-page-nav-btn" href="#awesome-lists">Awesome Lists</a>
</div>

## Tools

### Generative Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/MolecularAI/REINVENT4" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">REINVENT</span>
    <span class="hub-tool-desc">Reinforcement learning for molecular design</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/MolecularAI/GraphINVENT" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GraphINVENT</span>
    <span class="hub-tool-desc">Graph-based molecular generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/wengong-jin/hgraph2graph" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">hgraph2graph</span>
    <span class="hub-tool-desc">Hierarchical molecular graph generation</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/lukasturcani/stk" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">stk</span>
    <span class="hub-tool-desc">Building, manipulating, and analyzing molecules</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/choderalab/perses" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">perses</span>
    <span class="hub-tool-desc">Expanded ensembles for chemical space exploration</span>
  </a>
</div>

### Diffusion Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://arxiv.org/abs/2203.02923" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GeoDiff</span>
    <span class="hub-tool-desc">Geometric diffusion for molecular conformation</span>
  </a>
  <a class="hub-tool-card" href="https://arxiv.org/abs/2203.17003" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">EDM</span>
    <span class="hub-tool-desc">Equivariant diffusion for 3D molecules</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/arneschneuing/DiffSBDD" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">DiffSBDD</span>
    <span class="hub-tool-desc">Structure-based design via diffusion</span>
  </a>
</div>

### Benchmarks

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/BenevolentAI/guacamol" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GuacaMol</span>
    <span class="hub-tool-desc">Benchmarking for de novo molecular design</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/molecularsets/moses" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">MOSES</span>
    <span class="hub-tool-desc">Benchmarking platform for molecular generation</span>
  </a>
</div>

### Virtual Screening & Docking

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/gcorso/DiffDock" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">DiffDock</span>
    <span class="hub-tool-desc">Deep learning-based docking</span>
  </a>
  <a class="hub-tool-card" href="https://vina.scripps.edu/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AutoDock Vina</span>
    <span class="hub-tool-desc">Popular open-source docking software</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/ccsb-scripps/AutoDock-GPU" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AutoDock-GPU</span>
    <span class="hub-tool-desc">GPU-accelerated docking</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/gnina/gnina" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Gnina</span>
    <span class="hub-tool-desc">CNN-scoring molecular docking</span>
  </a>
</div>

---

## Datasets

### Chemical Libraries

<div class="hub-dataset-grid">
  <a class="hub-dataset-card" href="https://files.docking.org/zinc20-ML/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">ZINC20</span>
    <span class="hub-dataset-desc">Chemical library for deep docking virtual screening</span>
  </a>
  <a class="hub-dataset-card" href="https://cartblanche22.docking.org/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">ZINC22</span>
    <span class="hub-dataset-desc">Commercially-available compounds for virtual screening</span>
  </a>
  <a class="hub-dataset-card" href="https://gdb.unibe.ch/downloads/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">GDB</span>
    <span class="hub-dataset-desc">Enumerated molecules following chemical feasibility rules</span>
  </a>
  <a class="hub-dataset-card" href="https://enamine.net/compound-collections/screening-collection/hts-collection" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">Enamine HTS</span>
    <span class="hub-dataset-desc">1.93 million diverse screening compounds</span>
  </a>
</div>

### LLM & Generation Datasets

<div class="hub-dataset-grid">
  <a class="hub-dataset-card" href="https://files.docking.org/zinc20-ML/" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">ZINC20-ML</span>
    <span class="hub-dataset-desc">Deep-learning-ready ZINC20 formats</span>
    <span class="hub-dataset-size">300M+</span>
  </a>
  <a class="hub-dataset-card" href="https://huggingface.co/datasets/EMBL/chempile" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">ChemPile</span>
    <span class="hub-dataset-desc">Mixture-of-expert chemical corpus</span>
    <span class="hub-dataset-size">75B+ tokens</span>
  </a>
  <a class="hub-dataset-card" href="https://huggingface.co/datasets/osunlp/SMolInstruct" target="_blank" rel="noopener noreferrer">
    <span class="hub-dataset-name">SmolInstruct</span>
    <span class="hub-dataset-desc">Instruction dataset from 15 chemistry tasks</span>
    <span class="hub-dataset-size">3.3M pairs</span>
  </a>
</div>

---

## Awesome Lists

<div class="hub-awesome-grid">
  <a class="hub-awesome-item" href="https://github.com/amorehead/awesome-molecular-generation" target="_blank" rel="noopener noreferrer">Molecular generation papers</a>
  <a class="hub-awesome-item" href="https://github.com/benb111/awesome-small-molecule-ml" target="_blank" rel="noopener noreferrer">Drug discovery papers</a>
  <a class="hub-awesome-item" href="https://github.com/yangnianzu0515/awesome-molecular-docking" target="_blank" rel="noopener noreferrer">Molecular docking resources</a>
</div>
