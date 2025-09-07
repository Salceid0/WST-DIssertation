# WST Dissertation

**Dissertation Project** for the University of Bath on Wavelet Scattering Transforms (WST) applied to MRI denoising.

---

## Project Overview

This repository contains the code and notebooks for the implementation, training, and evaluation of three deep learning models applied to diffusion MRI denoising using wavelet scattering transforms.

---

## Notebooks Summary

- `CNNDMRI.ipynb`: Implementation and training of the CNN model for diffusion MRI.
- `Unet.ipynb`: Implementation and training of the U-Net model.
- `WaveletAutoencoder.ipynb`: Implementation and training of the Wavelet Scattering Autoencoder model.
- `ModelComparison.ipynb`: Evaluation and comparison of the trained models.
- `noisetest1.ipynb` & `noisetest2.ipynb`: Scripts to generate noisy images and validate the image corruption process.

---

## Installation

Instructions to set up the required environment:

```bash
pip install -r requirements.txt
```
---

## Usage

1. Run the individual model notebooks to train the models.
2. Use `ModelComparison.ipynb` to compare model performance.
3. Use the noise test notebooks to generate corrupted data for experiments.

---

## Project Structure

```
.
├── CNNDMRI.ipynb
├── Unet.ipynb
├── WaveletAutoencoder.ipynb
├── ModelComparison.ipynb
├── noisetest1.ipynb
├── noisetest2.ipynb
└── requirements.txt
```

---


