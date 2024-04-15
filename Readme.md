# Autoencoder and Variational Autoencoder (VAE) Implementation

This repository contains implementations of standard autoencoder (AE) and variational autoencoder (VAE) architectures along with training procedures and evaluations.

## Part 1: AE and VAE
### Autoencoder Architecture
Implemented a standard autoencoder architecture comprising encoder and decoder components.

### Variational Autoencoder Architecture
Developed a variational autoencoder architecture, incorporating a reparameterization trick for the latent space.

### Training
Trained both models on the MNIST dataset, experimenting with various hyperparameters to optimize performance.

## Part 2: Generative Adversarial Networks (GANs)
### GAN Architecture
Defined the Generator and Discriminator networks for the GAN model.

### Training Setup
Configured the training process, including setting up data loaders, initializing optimizers, and enabling GPU training.

### Evaluation
Evaluated the GAN model by monitoring loss and other relevant metrics for both the Generator and Discriminator.

### Data Generation
Generated new data samples using the trained Generator and compared their quality with the original dataset.

