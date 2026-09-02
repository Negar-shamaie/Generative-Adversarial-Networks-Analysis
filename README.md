# Generative Adversarial Networks Analysis

A comprehensive exploration and implementation of Naive GAN, WGAN-GP, and BEGAN architectures using PyTorch, applied to the MNIST dataset with FID evaluation.

This project investigates and implements three foundational Generative Adversarial Network (GAN) architectures: Naive GAN, Wasserstein GAN with Gradient Penalty (WGAN-GP), and Boundary Equilibrium GAN (BEGAN). Developed for the Neural Networks and Deep Learning course, it focuses on theoretical comparison, practical implementation on the MNIST dataset, and quantitative evaluation using the Fréchet Inception Distance (FID) score.

## Key Features
* **Multiple GAN Architectures:** Includes implementations of Naive GAN, WGAN-GP (addressing mode collapse and training instability), and BEGAN (featuring an autoencoder-based discriminator and a convergence measure).
* **MNIST Dataset Application:** Models are trained and evaluated on the standard MNIST dataset for handwritten digit generation.
* **FID Score Evaluation:** Implements the Fréchet Inception Distance to quantitatively assess the quality and diversity of the generated images for each model.
* **Comprehensive Loss Analysis:** Tracks and visualizes the distinct loss functions for each architecture, including the Minimax game for Naive GAN, the Wasserstein distance with gradient penalty for WGAN-GP, and the global convergence measure for BEGAN.

## Author
**Negar Shamaie** – University of Tehran, School of Electrical and Computer Engineering
