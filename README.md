# Exoplanet Characterization Overview

**GSoC 2025 | Machine Learning for Science (ML4Sci) – High-Level Overview Notebook**  

---

## Project Summary

This project explores the use of **machine learning foundation models** to characterize exoplanets and their formation environments using **multi-modal astronomical data**. The notebook provides a **high-level overview** of the approach I will take during GSoC 2025 under the ML4Sci initiative.

We work with **simulated image and spectral data**, visualize dimensionality reductions, and introduce model architectures tailored to different astrophysical data modalities including:

- Protoplanetary disk images (e.g., ALMA)
- Spectral time-series (e.g., JWST, Hubble)
- Atmospheric simulation data

---

## What's Inside

| Section | Description |
|--------|-------------|
| `Step 1` | Environment Setup & Imports |
| `Step 2` | Simulated Disk Image + Spectral Observation Generation |
| `Step 3` | Preprocessing with PCA Visualization |
| `Step 4` | CNN Baseline for Disk Classification |
| `Step 5` | Vision Transformer (ViT) Setup |
| `Step 6` | Spectral Transformer for Atmospheric Modeling |
| `Step 7` | Evaluation using F1 Score & RMSE |

---

## Key Technologies

- **Python**, **PyTorch**, **TensorFlow**
- **scikit-learn**, **Transformers**, **timm**
- **matplotlib**, **seaborn**, **PCA**
- (Conceptual use of Vision Transformers and Spectral Transformers)

---

## Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/KhushiRajurkar/Exoplanet-Characterization-GSoC.git
cd Exoplanet-Characterization-GSoC
```

### 2. Install Requirements
```bash
pip install torch torchvision timm transformers scikit-learn matplotlib seaborn
```
### 3. Run the Notebook
```bash
Exoplanet_Characterization_Overview.ipynb
```
