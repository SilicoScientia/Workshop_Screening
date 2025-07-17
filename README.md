# High-Throughput Virtual Screening with Machine Learning

> Tip: Right-click the Colab badge and select "Open link in new tab" for best experience.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1y1Ge1AwCrxbmMR0X_rfKWEWM9HnHZBRJ)

A comprehensive workshop on high-throughput virtual screening (HTVS) using a multi-stage funnel approach that combines machine learning, ADMET filtering, and molecular docking.

## Quick Start

### Download the Repository
```bash
# Option 1: Clone the repository
git clone https://github.com/SilicoScientia/Workshop_Screening.git

# Option 2: Download ZIP file
# Visit: https://github.com/SilicoScientia/Workshop_Screening/archive/refs/heads/main.zip
```

### Follow the Workshop
1. **Google Colab (Recommended)**: Open the [Colab Notebook](https://colab.research.google.com/drive/1y1Ge1AwCrxbmMR0X_rfKWEWM9HnHZBRJ)
2. **Local Setup**: Follow the documentation in the repository


## Workshop Overview

This workshop covers:
- Machine learning for compound activity prediction
- ADMET filtering for evaluating drug-likeness
- Automated ligand and protein preparation
- Molecular docking with AutoDock Vina
- Protein-ligand interaction analysis with PLIP
- End-to-end virtual screening pipeline

## Repository Structure

```
Workshop_Screening/
├── protein/                     # Protein target file
│   └── protein.pdbqt            # Pre-prepared protein for docking
├── Screening_training_data.csv  # Dataset for ML model training
├── Prediction_data.csv          # Dataset for screening prediction
├── Workshop_Screening.ipynb     # The main Colab notebook
└── README.md

```

## Documentation

- **Colab Notebook**: The primary source of documentation is the [Workshop_Screening.ipynb](https://colab.research.google.com/drive/1y1Ge1AwCrxbmMR0X_rfKWEWM9HnHZBRJ) notebook itself.
- **In-Notebook Documentation**: Each section of the notebook contains detailed explanations, code comments, and rationale for each step.

## Installation and Setup

All installation instructions and setup procedures are provided in:
- The Colab notebook
- The workshop manual embedded within the notebook

Follow the step-by-step instructions in these resources for complete setup and execution.

## Features

- ML-based activity prediction (Random Forest)
- ADMET property prediction and filtering (`admet-ai`)
- Automated ligand preparation (SMILES to 3D PDBQT with `Open Babel`)
- Batch molecular docking with AutoDock Vina
- Automated protein-ligand interaction analysis with PLIP
- Interactive filtering and result visualization

## Learning Objectives

By completing this workshop, you will learn:
1. To set up and run a complete virtual screening environment.
2. To train and apply a machine learning model for hit identification.
3. To filter and prioritize compounds based on ADMET properties.
4. To perform and analyze automated molecular docking simulations.
5. To visualize and interpret protein-ligand interactions to validate results.

## Contact

For questions or issues:
- GitHub Issues: [Workshop_Screening Issues](https://github.com/SilicoScientia/Workshop_Screening/issues)
- Follow the documentation and Colab notebook for support

---

*A complete, end-to-end pipeline for modern in-silico drug discovery, from large libraries to prioritized leads.*
