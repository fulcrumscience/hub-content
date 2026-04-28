# Neural Network Potentials

Machine learning interatomic potentials — training, evaluation, and deployment for atomistic simulations.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#datasets">Datasets</a>
  <a class="hub-page-nav-btn" href="#tutorials">Tutorials</a>
  <a class="hub-page-nav-btn" href="#awesome-lists">Awesome Lists</a>
</div>

## Tools

### Frameworks

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/ACEsuit/mace" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">MACE</span>
    <span class="hub-tool-desc">Message passing, equivariant architecture</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/mir-group/nequip" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">NequIP</span>
    <span class="hub-tool-desc">E(3)-equivariant interatomic potentials</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/CederGroupHub/chgnet" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">CHGNet</span>
    <span class="hub-tool-desc">Universal potential for atomistic modeling</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/atomistic-machine-learning/schnetpack" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">SchNetPack</span>
    <span class="hub-tool-desc">Deep learning for molecules and materials</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/mir-group/flare" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">FLARE</span>
    <span class="hub-tool-desc">Fast and accurate interatomic potentials</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/FitSNAP/FitSNAP" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">FitSNAP</span>
    <span class="hub-tool-desc">Training SNAP interatomic potentials</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/learningmatter-mit/NeuralForceField" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">NeuralForceField</span>
    <span class="hub-tool-desc">PyTorch-based force field</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/MDIL-SNU/SevenNet" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">SevenNet</span>
    <span class="hub-tool-desc">Scalable equivariant interatomic network</span>
  </a>
</div>

### Simulation & Analysis

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://wiki.fysik.dtu.dk/ase/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">ASE</span>
    <span class="hub-tool-desc">Atomic Simulation Environment — interfaces to many codes</span>
  </a>
  <a class="hub-tool-card" href="https://wiki.fysik.dtu.dk/gpaw/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">GPAW</span>
    <span class="hub-tool-desc">Density-functional theory Python code</span>
  </a>
  <a class="hub-tool-card" href="http://libatoms.github.io/QUIP/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">QUIP</span>
    <span class="hub-tool-desc">Software tools for molecular dynamics simulations</span>
  </a>
  <a class="hub-tool-card" href="http://atztogo.github.io/phonopy/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">phonopy</span>
    <span class="hub-tool-desc">Phonon calculations at harmonic levels</span>
  </a>
  <a class="hub-tool-card" href="https://pymatgen.org/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">pymatgen</span>
    <span class="hub-tool-desc">Python Materials Genomics — analysis and manipulation</span>
  </a>
</div>

### Cloud Platforms

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://matlantis.com/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Matlantis</span>
    <span class="hub-tool-desc">Accelerated materials discovery platform</span>
  </a>
  <a class="hub-tool-card" href="https://www.mat3ra.com/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Mat3ra</span>
    <span class="hub-tool-desc">Materials modeling cloud engine</span>
  </a>
</div>

---

## Datasets

### Large-Scale Computational Datasets

| Dataset | Description | Size |
|---------|-------------|------|
| [**OMat24**](https://huggingface.co/datasets/fairchem/OMAT24) | DFT for inorganic crystals (Meta) | 110M entries |
| [**LeMat-Bulk**](https://huggingface.co/datasets/LeMaterial/LeMat-Bulk) | Inorganic material structures | 6.7M structures |
| [**LeMat-Traj**](https://huggingface.co/datasets/LeMaterial/LeMat-Traj) | Inorganic material trajectories | 113M trajectories |
| [**MatPES**](https://matpes.ai/) | Structures from 300K MD simulations | ~400K structures |
| [**MP-ALOE**](https://figshare.com/) | r2SCAN DFT for universal MLIPs | ~1M calculations |
| [**Open Catalyst 2020**](https://opencatalystproject.org/) | Surface relaxations for catalysis | 1.2M relaxations |

### Molecular QM Datasets

| Dataset | Description | Size |
|---------|-------------|------|
| [**OMol25**](https://huggingface.co/facebook/OMol25) | Molecular chemistry DFT (Meta) | 100M+ calculations |
| [**ANI-1x/1ccx**](https://qcawebapps.molssi.org/ml_datasets/) | DFT + CCSD calculations | 5M + 0.5M |
| [**PubChemQCR**](https://huggingface.co/datasets/divelab/PubChemQCR) | Relaxation trajectories | 3.5M trajectories |
| [**Carbon Data**](https://github.com/jla-gardner/carbon-data) | Carbon trajectories | 22.9M atoms |

---

## Tutorials

| Tutorial | Topics | Format |
|----------|--------|--------|
| [**ML for Materials Course**](https://aronwalsh.github.io/MLforMaterials/Overview.html) | Neural network potentials, uncertainty | Jupyter |
| [**Transformers for Materials**](https://github.com/lamalab-org/llm-tutorial) | LLMs for materials science | Jupyter |

---

## Awesome Lists

<div class="hub-awesome-grid">
  <a class="hub-awesome-item" href="https://github.com/JuDFTteam/best-of-atomistic-machine-learning" target="_blank" rel="noopener noreferrer">510+ atomistic ML projects</a>
  <a class="hub-awesome-item" href="https://github.com/tilde-lab/awesome-materials-informatics" target="_blank" rel="noopener noreferrer">Materials informatics software</a>
  <a class="hub-awesome-item" href="https://atomistic.software/" target="_blank" rel="noopener noreferrer">Major atomistic simulation engines</a>
</div>
