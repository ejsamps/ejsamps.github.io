---
title: "Interactive Bayesian Covariance Decomposition"
excerpt: "An interactive exploration of Generalized Aliasing, showing how uncertainty shifts from aleatoric to epistemic as model capacity crosses the interpolation threshold."
collection: portfolio
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
