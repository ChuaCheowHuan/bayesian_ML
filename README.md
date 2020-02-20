# What's in this repository?

This repository contains the following Bayesian based machine learning
implementations:

(1) [GMM (Gaussian mixture model) clustering](#gmm)


(2) [Variational Autoencoder (VAE)](#vae) with mnist dataset

---

# GMM

**GMM (Gaussian mixture model) clustering with EM (expectation maximization)
algorithm & using variational lower bound as a stopping criterion.**

The following are implemented:

(1) Function that avoids computing inverse of matrix when computing
<img src="https://render.githubusercontent.com/render/math?math=y = A^{-1}x">
by solving system of linear equations.

(2) Log sum trick to avoid underflow when multiplying small numbers.

(3) pdf of the Multivariate normal distribution

(4) E-step function of the EM algorithm

(5) M-step function of the EM algorithm

(6) Variational lower bound function

(7) GMM function

(8) Training function for GMM

(9) Scatter plot of clusters (Plot at the bottom shows results of 7 clusters from
  a dataset of 100 points)

Data:

![](https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/gmm_data.png)

GMM clusters:

![](https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/gmm_cluster.png)

---

# VAE

**Variational Autoencoders (VAE) with mnist dataset**

VAE graph:

![](https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/vae_mnist_graph.png)

VAE output of train & validation data:

![](https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/vae_mnist_train_val.png)

VAE decoder output with random Gaussian noise, sample from the prior distribution p(t) (Gaussian) and then from the likelihood p(x | t):

![](https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/vae_mnist_N_gen.png)
