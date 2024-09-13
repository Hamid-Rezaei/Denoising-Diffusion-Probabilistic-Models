# Diffusion Models Seminar Report

This repository contains the seminar report titled "Probabilistic Diffusion Models for Denoising", written by me Rezaei for the course Foundations of Statistical Learning as part of the Master's program at Amirkabir University of Technology.

## Introduction
The report compares diffusion models with other popular generative models like GANs, VAEs, and Flow-based models. It highlights how diffusion models overcome certain limitations of these models, such as unstable training in GANs and low image diversity.

## Diffusion Process
Detailed explanation of:

- Forward Diffusion: Adding noise to the data in a controlled manner.
- Reverse Diffusion: Reversing the noise addition to reconstruct data.
- Markov Chain: How the diffusion process works through a Markov chain framework.

## Evaluation and Experiments
The report includes extensive testing of diffusion models using the following metrics:

- Inception Score (IS)
- FID Score (Frechet Inception Distance)
- Negative Log Likelihood (NLL)
It also compares the performance of these models on datasets like CelebA-HQ and CIFAR10.

## U-Net Architecture
The U-Net architecture is utilized to handle the forward and reverse diffusion processes. This section covers how the model is structured to improve image quality and handle image segmentation effectively.

## Conclusion
The report concludes that diffusion models are not only capable of producing high-quality images, but they also provide a stable and interpretable framework for generative modeling. Future potential applications include generating other types of data such as sound and text.

## Abstract
This report explores probabilistic diffusion models, which use noise to generate high-quality artificial images. The training process is based on variational bounds and denoising score matching techniques. The report covers the theoretical foundation, training methods, and evaluation of these models, as well as their superiority over other generative models.

## References
1. [Ho, J., Jain, A., & Abbeel, P. (2020). Denoising Diffusion Probabilistic Models.](https://arxiv.org/abs/2006.11239)
2. [Nichol, A., & Dhariwal, P. (2021). Improved Denoising Diffusion Probabilistic Models.](https://arxiv.org/abs/2102.09672)
3. [Ronneberger, O., Fischer, P., & Brox, T. (2015). U-Net: Convolutional Networks for Biomedical Image Segmentation.](https://arxiv.org/abs/1505.04597)
