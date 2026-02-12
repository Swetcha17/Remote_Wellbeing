# rPPG Algorithmic Framework

A streamlined computational framework for **Remote Photoplethysmography (rPPG)** research. This repository provides a clean, modular implementation of state-of-the-art supervised deep learning architectures and unsupervised signal decomposition methods for non-contact physiological monitoring.

---
The codebase is optimized for **algorithmic development**, **comparative benchmarking**, and **reproducibility**, focusing strictly on the mathematical models and training pipelines without the overhead of deployment tools.

## Methodological Scope

This framework implements two primary categories of physiological signal extraction methods:

### 1. Supervised Deep Learning Architectures
Implementations of end-to-end neural networks for extracting Blood Volume Pulse (BVP) signals from video data:
* **Convolutional Networks:** DeepPhys, PhysNet, TS-CAN, EfficientPhys.
* **Transformer & Attention Models:** PhysFormer, RhythmFormer.
* **State Space Models:** PhysMamba.
* **Hybrid Architectures:** iBVPNet, BigSmall.

### 2. Unsupervised Signal Processing
Traditional mathematical approaches for blind source separation and chromatic analysis:
* **Chrominance-based:** CHROM, POS (Plane-Orthogonal-to-Skin).
* **Blind Source Separation:** ICA (Independent Component Analysis), GREEN.
* **Optimization-based:** LGI (Local Group Invariance), PBV, OMIT.

---

## Computational Environment

### Prerequisites
* **Python:** 3.8+
* **Frameworks:** PyTorch, NumPy, SciPy

### Installation
Install the core research dependencies:
```bash
pip install -r requirements.txt
