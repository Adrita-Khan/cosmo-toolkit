# Cosmo-Toolkit 🌌

A comprehensive Python toolkit for observational cosmology, combining theoretical foundations with modern data analysis techniques, machine learning, and statistical methods.

## 🔭 Overview

This repository provides tools and resources for:
- **Observational Cosmology**: Data analysis pipelines for cosmic surveys
- **Machine Learning**: ML applications in cosmological parameter estimation
- **Statistical Methods**: Bayesian inference, MCMC, and statistical modeling
- **Mathematical Foundations**: Core equations and numerical methods
- **Theory & Models**: Implementation of cosmological theories and models

## 📋 Table of Contents

- [Installation](#installation)
- [Quick Start](#quick-start)
- [Repository Structure](#repository-structure)
- [Features](#features)
- [Documentation](#documentation)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- NumPy, SciPy, Matplotlib
- Astropy
- scikit-learn, TensorFlow/PyTorch (for ML modules)

### Install from source
```bash
git clone https://github.com/yourusername/cosmo-toolkit.git
cd cosmo-toolkit
pip install -r requirements.txt
pip install -e .
```

### Using conda (recommended)
```bash
conda create -n cosmo python=3.9
conda activate cosmo
pip install -r requirements.txt
```

## 🚀 Quick Start

```python
import cosmo_toolkit as ct

# Load observational data
data = ct.data.load_supernova_data("jla")

# Fit cosmological parameters
fitter = ct.models.LambdaCDM()
results = fitter.fit(data, method="mcmc")

# Visualize results
ct.plotting.corner_plot(results.samples)
```

## 📁 Repository Structure

```
cosmo-toolkit/
├── cosmo_toolkit/
│   ├── data/              # Data loading and processing
│   ├── models/            # Cosmological models
│   ├── inference/         # Statistical inference tools
│   ├── ml/               # Machine learning modules
│   ├── theory/           # Theoretical calculations
│   ├── observations/     # Observational analysis tools
│   ├── plotting/         # Visualization utilities
│   └── utils/            # Helper functions
├── notebooks/            # Jupyter notebooks with examples
├── scripts/              # Standalone analysis scripts
├── docs/                # Documentation
├── tests/               # Unit tests
├── data/                # Sample datasets
└── papers/              # Reference papers and notes
```

## ✨ Features

### 🔍 Observational Analysis
- **Supernova Analysis**: Type Ia SNe distance measurements
- **CMB Analysis**: Cosmic microwave background data processing
- **BAO Analysis**: Baryon acoustic oscillation measurements
- **Weak Lensing**: Shear correlation functions and mass mapping
- **Galaxy Clustering**: Two-point correlation functions

### 🧠 Machine Learning
- **Parameter Estimation**: Neural networks for cosmological parameters
- **Anomaly Detection**: Identifying unusual cosmic objects
- **Classification**: Galaxy/star separation, supernova typing
- **Dimensionality Reduction**: PCA, t-SNE for high-dimensional data
- **Deep Learning**: CNNs for image analysis, RNNs for time series

### 📊 Statistical Methods
- **MCMC Sampling**: Metropolis-Hastings, Hamiltonian Monte Carlo
- **Nested Sampling**: Evidence calculation and model comparison
- **Bayesian Inference**: Parameter estimation with proper uncertainties
- **Frequentist Methods**: χ² fitting, profile likelihoods
- **Model Selection**: Information criteria (AIC, BIC, DIC)

### 🧮 Mathematical Foundations
- **Distance Calculations**: Luminosity, angular diameter, comoving distances
- **Growth Functions**: Structure formation and perturbation theory
- **Power Spectra**: Matter and CMB power spectrum calculations
- **Numerical Integration**: Cosmological integrals and differential equations
- **Special Functions**: Spherical harmonics, Bessel functions

### 🌐 Cosmological Models
- **Standard Model**: ΛCDM with varying parameters
- **Dark Energy Models**: w(z), quintessence, phantom energy
- **Modified Gravity**: f(R), DGP, scalar-tensor theories
- **Early Universe**: Inflation models, primordial perturbations
- **Alternative Models**: MOND, emergent gravity


----

### Key Resources:

**GitHub Repositories:**
- [Taotie - Cosmology Tools](https://github.com/dr-guangtou/taotie/blob/master/astro/topics/cosmology_tools.md)
- [MPK Compilation](https://github.com/marius311/mpk_compilation)
- [Machine Learning in Cosmology](https://github.com/georgestein/ml-in-cosmology)
- [Cosmology Model Independent Tests](https://github.com/astrobengaly/cosmo_model_independent_tests)
- [IFCA Cosmology Group](https://github.com/IFCA-Cosmology-Group)
- [CosmoStat Tutorials](https://github.com/CosmoStat/Tutorials)
- [Cosmology Resource Materials](https://github.com/jrdmb/cosmology-resource-materials)
- [HEP-ASTRO-COSMO](https://github.com/nikosarcevic/HEP-ASTRO-COSMO)

**Educational Resources:**
- [Ned Wright's Cosmology Tutorial](https://www.astro.ucla.edu/~wright/cosmolog.html)
- [Daniel Baumann's Cosmology Lecture Notes (PDF)](https://cmb.wintherscoming.no/pdfs/baumann.pdf)
- [Moritz Münchmeyer's Lecture Notes](https://munchmeyer.physics.wisc.edu/lecture-notes/)
- [Observable Cosmology Slides - University of Bonn (PDF)](https://astro.uni-bonn.de/~kbasu/ObsCosmo/Slides/OC1.pdf)
- [Power Spectrum Review](https://universe-review.ca/R05-04-powerspectrum.htm)
- [Modern Cosmology Course](https://hoangducthuong.github.io/modern_cosmology/)

**Video Content:**
- [TASI Cosmology Lecture](https://www.youtube.com/watch?v=PWx-S2COTZQ&ab_channel=TASIvideos)

**Academic Papers (arXiv):**
- [arXiv:1701.01467](https://arxiv.org/pdf/1701.01467)
- [arXiv:1205.2064](https://arxiv.org/pdf/1205.2064)
- [arXiv:1712.04512](https://arxiv.org/pdf/1712.04512)


