[poisson_CNN](https://github.com/aligirayhanozbay/poisson_CNN) is a convolutional neural network model whih estimates the solution of the Poisson equation with four Dirichlet boundary conditions on rectangular grids of variable sizes.

[An article describing the performance of our model](https://arxiv.org/abs/1910.08613) is available on arXiv. This repository contains Jupyter notebooks that can be used to replicate the results used in the paper.

Installation requires CUDA set up to work with tensorflow-gpu version 2.0.0 or newer.
```
pip install poisson_CNN==0.2.0
```
Please note that the '[paper_oct19](https://github.com/aligirayhanozbay/poisson_CNN/tree/paper_oct19)' is the branch of the poisson_CNN repository that contains the code that was used to generate the results in our paper.
