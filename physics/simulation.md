# Simulation & Surrogates

ML-accelerated physics simulations — surrogate models for PDEs, CFD, turbulence, and weather.

<div class="hub-page-nav">
  <a class="hub-page-nav-btn" href="#tools">Tools</a>
  <a class="hub-page-nav-btn" href="#datasets">Datasets</a>
  <a class="hub-page-nav-btn" href="#resources">Resources</a>
</div>

## Tools

### Physics-Informed Neural Networks

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://www.sciencedirect.com/science/article/pii/S0021999118307125" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">PINNs</span>
    <span class="hub-tool-desc">Physics-informed neural networks</span>
  </a>
  <a class="hub-tool-card" href="https://arxiv.org/abs/1910.03193" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">DeepONet</span>
    <span class="hub-tool-desc">Deep operator networks</span>
  </a>
  <a class="hub-tool-card" href="https://arxiv.org/abs/2010.08895" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Fourier Neural Operator</span>
    <span class="hub-tool-desc">Learning in Fourier space</span>
  </a>
  <a class="hub-tool-card" href="https://arxiv.org/abs/1509.03580" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">SINDy</span>
    <span class="hub-tool-desc">Sparse identification of dynamical systems</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/NVIDIA/physicsnemo" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">NVIDIA PhysicsNeMo</span>
    <span class="hub-tool-desc">Framework for physics-ML models</span>
  </a>
</div>

### Neural Differential Equations

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://arxiv.org/abs/1806.07366" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Neural ODEs</span>
    <span class="hub-tool-desc">Continuous-depth neural networks</span>
  </a>
  <a class="hub-tool-card" href="https://arxiv.org/abs/1906.01563" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Hamiltonian NNs</span>
    <span class="hub-tool-desc">Physics-preserving neural networks</span>
  </a>
  <a class="hub-tool-card" href="https://arxiv.org/abs/2001.04385" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Universal Differential Equations</span>
    <span class="hub-tool-desc">Combining DEs with ML</span>
  </a>
</div>

### SciML Software

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://github.com/rtqichen/torchdiffeq" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">torchdiffeq</span>
    <span class="hub-tool-desc">PyTorch neural ODEs</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/lululxvi/deepxde" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">DeepXDE</span>
    <span class="hub-tool-desc">Deep learning for scientific computing</span>
  </a>
  <a class="hub-tool-card" href="https://github.com/dynamicslab/pysindy" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">pysindy</span>
    <span class="hub-tool-desc">Sparse identification</span>
  </a>
  <a class="hub-tool-card" href="https://diffeq.sciml.ai/stable/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">DifferentialEquations.jl</span>
    <span class="hub-tool-desc">Comprehensive DE solving (Julia)</span>
  </a>
  <a class="hub-tool-card" href="https://docs.sciml.ai/NeuralPDE/stable/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">NeuralPDE.jl</span>
    <span class="hub-tool-desc">Physics-informed neural networks (Julia)</span>
  </a>
</div>

### Books & Courses

<div class="hub-tool-grid">
  <a class="hub-tool-card" href="https://book.sciml.ai/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Parallel Computing and SciML</span>
    <span class="hub-tool-desc">Chris Rackauckas</span>
  </a>
  <a class="hub-tool-card" href="https://www.cambridge.org/core/books/datadriven-science-and-engineering/" target="_blank" rel="noopener noreferrer">
    <span class="hub-tool-name">Data-Driven Science and Engineering</span>
    <span class="hub-tool-desc">Brunton & Kutz</span>
  </a>
</div>

---

## Datasets

### CFD & PDE Benchmarks

| Dataset | Description |
|---------|-------------|
| [**PDEBench**](https://github.com/pdebench/PDEBench) | Comprehensive benchmark for PDE solving with ML |
| [**PDEArena**](https://microsoft.github.io/pdearena/) | PDE modeling benchmark suite |
| [**BLASTNet**](https://github.com/blastnet/blastnet) | 744 full-domain samples of 3D turbulent flows |
| [**JHTDB**](http://turbulence.pha.jhu.edu/) | Johns Hopkins Turbulence Database |
| [**Airfoil CFD**](https://zenodo.org/records/7044183) | 2D compressible flow simulations (6K samples) |
| [**DrivAerNet**](https://github.com/Mohamedelrefaie/DrivAerNet) | 4,000 car meshes with aerodynamic data |

### Simulation Datasets

| Dataset | Description |
|---------|-------------|
| [**MeshGraphNets Data**](https://github.com/deepmind/deepmind-research/tree/master/meshgraphnets) | DeepMind simulation datasets |
| [**PhiFlow Examples**](https://github.com/tum-pbs/PhiFlow) | Physics simulation framework with data |

### Particle & High-Energy Physics

| Dataset | Description |
|---------|-------------|
| [**CERN Open Data**](https://opendata.cern.ch/) | LHC collision data and simulations |
| [**CaloGAN**](https://ml4sci.lbl.gov/calogan) | Deep generative models for calorimeter simulations |
| [**LHC Olympics**](https://ml4sci.lbl.gov/lhcolympics) | Anomaly detection challenge dataset |
| [**Inference with DCTR**](https://ml4sci.lbl.gov/dctr) | Direct comparison to reference for inference |
| [**Unfolding with OmniFold**](https://ml4sci.lbl.gov/omnifold) | ML-based unfolding for particle physics |

### Cosmology & Astrophysics

| Dataset | Description |
|---------|-------------|
| [**CosmoFlow**](https://ml4sci.lbl.gov/cosmoflow) | ~10,000 cosmological N-body dark matter simulations |
| [**SDSS**](https://www.sdss.org/dr18/) | Sloan Digital Sky Survey imaging and spectra |
| [**NASA Exoplanet Archive**](https://exoplanetarchive.ipac.caltech.edu/) | Confirmed exoplanets and candidates |

---

## Resources

<div class="hub-awesome-grid">
  <a class="hub-awesome-item" href="https://github.com/MartinuzziFrancesco/awesome-scientific-machine-learning" target="_blank" rel="noopener noreferrer">SciML resources</a>
  <a class="hub-awesome-item" href="https://github.com/idrl-lab/awesome-pinn" target="_blank" rel="noopener noreferrer">Physics-informed neural networks</a>
  <a class="hub-awesome-item" href="https://ml4sci.lbl.gov/datasets" target="_blank" rel="noopener noreferrer">Berkeley Lab's curated scientific ML datasets</a>
</div>
