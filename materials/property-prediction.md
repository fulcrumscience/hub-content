# Property Prediction

ML models for predicting material properties from structure — bandgap, formation energy, stability, and more.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#datasets">Datasets</a>
  <a class="hub-page-nav-btn" href="#tutorials">Tutorials</a>
  <a class="hub-page-nav-btn" href="#blogs">Blogs</a>
</div>

## Tools

### Core Stack

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://pymatgen.org/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">pymatgen</span>
    <span class="hub-tool-desc">Python Materials Genomics — analysis and manipulation</span>
  </a>
  <a class="hub-tool-card" href="https://hackingmaterials.lbl.gov/matminer/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">matminer</span>
    <span class="hub-tool-desc">Data mining and ML for materials</span>
  </a>
  <a class="hub-tool-card" href="https://wiki.fysik.dtu.dk/ase/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ASE</span>
    <span class="hub-tool-desc">Atomic Simulation Environment</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/usnistgov/jarvis" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">JARVIS-tools</span>
    <span class="hub-tool-desc">Integrated workflows for materials</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/materialsproject/emmet" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">emmet</span>
    <span class="hub-tool-desc">Build collections of materials properties</span>
  </a>
</div>

### ML Models

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/materialsvirtuallab/maml" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">MAML</span>
    <span class="hub-tool-desc">High-level interfaces for materials science ML</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/materialsvirtuallab/megnet" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">MEGNet</span>
    <span class="hub-tool-desc">Graph networks for molecules and crystals</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/txie-93/cgcnn" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">CGCNN</span>
    <span class="hub-tool-desc">Crystal graph networks for material properties</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/usnistgov/alignn" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ALIGNN</span>
    <span class="hub-tool-desc">Atomistic Line Graph Neural Network</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/SINGROUP/dscribe" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">DScribe</span>
    <span class="hub-tool-desc">Descriptor library with various fingerprinting techniques</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/yoshida-lab/XenonPy" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">XenonPy</span>
    <span class="hub-tool-desc">Material descriptors and neural network models</span>
  </a>
  <a class="hub-tool-card" href="http://amp.readthedocs.io/en/latest/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">amp</span>
    <span class="hub-tool-desc">Machine-learning for atomistic calculations</span>
  </a>
</div>

### High-Throughput Frameworks

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="http://materials.duke.edu/AFLOW/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AFLOW</span>
    <span class="hub-tool-desc">Ab-initio computing, high-throughput</span>
  </a>
  <a class="hub-tool-card" href="http://aiida.net/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">AiiDA</span>
    <span class="hub-tool-desc">Automated infrastructure for ab-initio design</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/materialsproject/atomate2" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">atomate2</span>
    <span class="hub-tool-desc">Materials science workflow library</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/arosen93/quacc" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">quacc</span>
    <span class="hub-tool-desc">High-throughput computational materials science</span>
  </a>
</div>

---

## Datasets

### Major Databases

| Dataset | Description | Size |
|---------|-------------|------|
| [**Materials Project**](https://materialsproject.org/) | DFT calculations, properties | 500K+ materials |
| [**AFLOW**](http://www.aflowlib.org/) | Crystal structures, properties | 3.5M+ entries |
| [**JARVIS-DFT**](https://jarvis.nist.gov/) | DFT data with ML models | 40K+ materials |
| [**OQMD**](http://oqmd.org/) | Open Quantum Materials Database | 1M+ entries |
| [**NOMAD**](https://nomad-lab.eu/) | Computational materials data | 19M+ calculations |

### Benchmark Datasets

| Dataset | Description |
|---------|-------------|
| [**MatBench**](https://matbench.materialsproject.org/) | Standardized ML benchmarks |
| [**MatBench-Discovery**](https://github.com/janosh/matbench-discovery) | ML-guided discovery benchmark |
| [**matbench-discovery (tool)**](https://github.com/janosh/matbench-discovery) | Benchmark for ML-guided materials discovery |

### Specialized

| Dataset | Focus |
|---------|-------|
| [**2D Materials (C2DB)**](https://c2db.fysik.dtu.dk/) | 2D materials properties |
| [**Polymer Genome**](https://khazana.gatech.edu/) | Polymers with properties |
| [**Porous Materials AI Gym**](https://github.com/SimonEnsemble/porous-material-AI-gym) | ML datasets for porous materials |

---

## Tutorials

| Tutorial | Topics | Format |
|----------|--------|--------|
| [**matminer tutorials**](https://hackingmaterials.lbl.gov/matminer/) | Feature engineering for materials | Jupyter |
| [**ML for Materials Course**](https://aronwalsh.github.io/MLforMaterials/Overview.html) | Regression, feature engineering | Jupyter |
| [**Materials Informatics**](https://github.com/sp8rks/MaterialsInformatics) | ML for discovery | Jupyter |

### Courses

**[Machine Learning for Materials (ICL)](https://aronwalsh.github.io/MLforMaterials/Overview.html)** — Aron Walsh (Imperial College London). Covers regression, classification, feature engineering for materials, and uncertainty quantification.

**[Materials Informatics](https://github.com/sp8rks/MaterialsInformatics)** — Taylor Sparks (Utah). ML for materials discovery course materials.

---

## Blogs

<div class="hub-awesome-grid">
  <a class="hub-awesome-item" href="https://kjablonka.com/index.html" target="_blank" rel="noopener noreferrer">
    <span class="hub-awesome-title">Kevin Jablonka's Blog</span>
    <span class="hub-awesome-desc">LLMs, materials science</span>
  </a>
</div>
