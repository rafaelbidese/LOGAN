# LOGAN-automatic-differentiation
This repository implements the latent optimization from the paper LOGAN which does not have an official open-source code to this date (Apr, 2020).

This notebook implements the latent optimization algorithms using automatic differentiation  presented in the paper using PyTorch. 

`Latent Optimised GANs with Automatic Differentiation`

The notebook is based on the Assignment 3 Q5: Generative Adversarial Networks from the CS231n Convolutional Neural Networks for Visual Recognition.

The latent optimization algorithms are tested on 3 different GAN architectures since the novel improvement from the paper is not architecture dependent. Here the LOGAN-GD and LOGAN-NGD are evaluated in the 3 GANs: Vanilla GAN, LS-GAN and DC-GAN performing multi label classification on the MNIST dataset.

The LOGAN-GD latent optmization showed that it can help stabilizing the min-max game for the GANs tested. However, for the LOGAN-NGD it is not clear if the method/implementation/hyperparameters are the ones to blame for not achieving the performance expected from the paper.

These results are not directly comparable with the ones presented in the paper, but suggest that claim from the authors is valid.

Paper reference:
Yan Wu, Jeff Donahue, David Balduzzi, Karen Simonyan, Timothy Lillicrap. LOGAN: LATENT OPTIMISATION FOR GENERATIVE
ADVERSARIAL NETWORKS. Available at https://arxiv.org/pdf/1912.00953.pdf
