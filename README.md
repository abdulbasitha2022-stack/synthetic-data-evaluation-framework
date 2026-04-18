# Synthetic Data Generation & Evaluation Framework

🚀 Key Insight: There is no single "best" synthetic data method — the optimal choice depends on the application context (privacy vs ML performance).

---

## Overview
This project evaluates synthetic data quality using a multi-dimensional framework based on:
- Statistical Similarity (KS Test)
- Machine Learning Utility (TSTR – Train on Synthetic, Test on Real)
- Privacy Preservation (distance-based metrics)

It also introduces a **use-case sensitivity analysis**, showing how the best method changes across different real-world priorities.

---

## Key Features
- Implemented Gaussian Noise and Gaussian Copula synthetic data generators  
- Evaluated data across 3 pillars: statistics, ML utility, and privacy  
- Designed a composite scoring framework for unified evaluation  
- Introduced a novel use-case sensitivity analysis (Privacy-first, Balanced, ML-first)  

---

## Results
- Gaussian Copula outperforms in statistical similarity and privacy  
- Gaussian Noise performs competitively in ML utility  
- No single best method — optimal choice depends on use-case priorities  

---

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
