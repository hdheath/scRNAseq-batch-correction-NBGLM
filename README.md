# 🧬 scRNA-seq Batch Effect Correction using NB-GLM

This project implements a Negative Binomial Generalized Linear Model (NB-GLM) for correcting batch effects in single-cell RNA sequencing data. Batch-corrected expression values are then evaluated using clustering quality metrics such as the Average Silhouette Coefficient (ASC).

---

## 📘 Highlights

- Batch-aware modeling using GLMs with a log-link function
- Estimation of gene- and batch-specific coefficients
- Correction of expression counts per gene per cell
- Quantitative assessment using ASC
- Fully implemented in Python

---


## 🛠️ Env Used

- Python 3.12+
- pandas, numpy, scipy
- matplotlib
- silhouette scoring via scikit-learn

