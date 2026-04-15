---
title: "Bayesian Covariance Decomposition"
excerpt: "Interactive tool for exploring Epistemic and Aleatoric uncertainty in Fourier feature models.<br/><img src='/images/aliasing-thumb.png'>"
collection: portfolio
header:
  teaser: "/images/aliasing-thumb.png"
---

This project visualizes the **Generalized Aliasing Decomposition (GAD)** within a Bayesian framework. Using a Fourier feature model, I decompose the posterior covariance into two distinct components:

1.  **Data Insufficiency (Epistemic):** Uncertainty stemming from the null space of the design matrix (what the model literally cannot see).
2.  **Aliasing (Aleatoric):** Uncertainty arising from unmodeled signals in the data that "alias" into our chosen feature set.

### Interactive Tool
I built a custom tool using **PyScript** to allow real-time manipulation of model parameters ($d$, $n$, and prior variances).

<a href="https://ejsamps.github.io/uncertainty/" style="background-color: #2563eb; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; font-weight: bold;">🚀 Launch Interactive App</a>

---

### Project Documentation
For a deep dive into the linear algebra, the SVD-based nullspace projection, and the connection to the "Double Descent" phenomenon, read my full report below.

[**Download Full Research Report (PDF)**](https://ejsamps.github.io/files/your_report.pdf)
