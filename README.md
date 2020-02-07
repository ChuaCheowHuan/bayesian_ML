# What's in this repository?

This repository contains the implementation of GMM (Gaussian mixture model)
clustering with EM (expectation maximization) algorithm.

---

The following are implemented:

1) Function that avoids computing inverse of matrix when computing
y=(A_inverse)x by solving system of linear equations.

2) Log sum trick to avoid underflow when multiplying small numbers.

3) pdf of the Multivariate normal distribution

4) E-step function of the EM algorithm

5) M-step function of the EM algorithm

6) Variational lower bound function

7) GMM function

8) Training function for GMM

9) Scatter plot of clusters (Plot at the bottom shows 8 clusters from a dataset of 100 points)

---
Data:

![][https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/data.png]

---
Clusters:

![][https://github.com/ChuaCheowHuan/GMM_clustering/blob/master/png/clusters.png]
