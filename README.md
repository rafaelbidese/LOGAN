# LOGAN-automatic-differentiation
This repository implements the latent optimization using automatic differentiation from the paper LOGAN.

This notebook implements the first latent optimization algorithm mentioned in the paper using PyTorch. 

`Algorithm 1: Latent Optimised GANs with Automatic Differentiation`

The algorithm is tested on 3 different GAN architectures since the novel improvement from the paper is not architecture dependant. Here the algorithm is evaluated in the 3 GANs on the Stanford CS231n assignment: Vanilla GAN, LS-GAN and DC-GAN.

Paper reference:
Yan Wu, Jeff Donahue, David Balduzzi, Karen Simonyan, Timothy Lillicrap. LOGAN: LATENT OPTIMISATION FOR GENERATIVE
ADVERSARIAL NETWORKS. Available at https://arxiv.org/pdf/1912.00953.pdf