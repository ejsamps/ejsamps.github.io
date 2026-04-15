---
title: "Bayesian Covariance Decomposition"
excerpt: "Interactive tool for exploring Epistemic and Aleatoric uncertainty in Fourier feature models.<br/><img src='/images/bayes-thumbnail.png'>"
collection: portfolio
header:
  teaser: "/images/bayes-thumbnail.png"
---

This project, developed for CS 677 (Bayesian Methods), derives a decomposition of the posterior covariance for the weights of L2 regularized linear regression. Inspired by Generalized Aliasing (Transtrum et al. 2025), I demonstrate how the posterior covariance is the sum of two distinct components: Data Insufficiency (Epistemic) and Aliasing (Aleatoric) covariance. I explore how these quantities follow proven theoretical behaviors and discuss their potential to improve uncertainty quantification in models like Gaussian Processes and Bayesian Optimization.

### Interactive Tool
I built a custom tool using **PyScript** to allow real-time manipulation of model parameters (d, n, and prior variances). Feel free to play around with it and see how the different covariance quantities behavior depending on the parameterization regime and the priors we put on our weights.

<a href="https://ejsamps.github.io/uncertainty/" style="background-color: #2563eb; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; font-weight: bold;"> Launch Interactive App</a>

---

### Project Documentation
For a deep dive into the linear algebra, and the connection to the Double Descent phenomenon, read my full report below.

[**Download Project Report (PDF)**](https://ejsamps.github.io/files/your_report.pdf)
