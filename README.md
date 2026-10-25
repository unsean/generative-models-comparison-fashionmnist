# generative-models-comparison-fashionmnist

Studi komparatif enam model generatif pada Fashion-MNIST (Vanilla Autoencoder,
Sparse Autoencoder, VAE, Vanilla GAN, DCGAN, DDPM) disertai eksperimen pembuktian
keterbatasan bobot dan latent feature MLP classifier untuk image generation
(Tahap 1–5).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fdnlJJLfMjOiLq_nfMOtGH44yP4D4Wio?usp=sharing)

## Isi

- `generative_models_comparison.ipynb` — notebook utama: setup, definisi model,
  training, eksperimen MLP Tahap 1–5, evaluasi metrik, dan figure.
- `results/` — `metrics.csv`/`metrics.json`, log loss per epoch, dan 5 figure.
- `checkpoints/` — bobot terlatih seluruh model.

## Menjalankan

Buka notebook di
[Google Colab](https://colab.research.google.com/drive/1fdnlJJLfMjOiLq_nfMOtGH44yP4D4Wio?usp=sharing)
dengan runtime GPU, lalu Run all. Dataset Fashion-MNIST diunduh otomatis oleh
torchvision; hasil disimpan ke `results/` dan `checkpoints/`.
