# EM-Gaussian-Mixture-Model
This project demonstrates the implementation of the Expectation-Maximization (EM) Algorithm to fit Gaussian Mixture Models (GMM) on real-world datasets. It highlights parameter estimation, log-likelihood monitoring, and convergence analysis for effective unsupervised learning.

# Expectation Maximization for Gaussian Mixture Model

This project demonstrates the implementation of the Expectation Maximization (EM) algorithm to estimate parameters of a Gaussian Mixture Model (GMM) with two components. The project involves applying the algorithm to two datasets, `quake` and `faithful`, from R's base library. Additionally, a custom dataset is explored for fitting a finite mixture model.

---

## **Key Objectives and Methodology**

### 1. **Parameter Estimation using EM Algorithm**
- Estimated parameters for a Gaussian mixture distribution with two components:
  - Means: \( \mu_1, \mu_2 \)
  - Variances: \( \sigma_1^2, \sigma_2^2 \)
  - Weights: \( p_1 \) and \( p_2 \)
  
- Initial parameter values were set based on the data's mean and standard deviation:
  \[
  \theta^{(0)} = (\mu_1^{(0)}, \mu_2^{(0)}, \sigma_1^{(0)}, \sigma_2^{(0)}, p^{(0)})
  \]
  
- Updated the parameters iteratively using EM's Expectation and Maximization steps until convergence.

---

### 2. **Evaluating Model Fit**
- Examined the likelihood progression during training, confirming that the log-likelihood increases monotonically as expected with the EM algorithm.
- Determined stopping criteria based on negligible changes in log-likelihood values between successive iterations.

---

### 3. **Data Exploration and Realism Check**
- Evaluated the assumption of a Gaussian mixture for both datasets:
  - **Quake Dataset:** The distribution exhibited multimodal characteristics, supporting the Gaussian mixture assumption.
  - **Faithful Dataset:** While reasonably fitting, the assumption showed limitations due to outliers and asymmetry in the data.

---

### 4. **Custom Data Application**
- Applied the EM algorithm to a third dataset from an external source.
- Successfully fitted a finite mixture model, demonstrating the algorithm's versatility and robustness.

---

## **Achievements**
- Developed a robust EM algorithm implementation from scratch.
- Derived explicit update formulas for parameter estimation.
- Demonstrated the convergence behavior of the log-likelihood function.
- Evaluated the effectiveness of Gaussian mixture assumptions on real-world data.
- Extended the application to a custom dataset, enhancing the project's generalizability.

---

This project highlights the EM algorithm's powerful iterative approach for parameter estimation in GMMs, showcasing its convergence properties, practical applications, and potential limitations.



