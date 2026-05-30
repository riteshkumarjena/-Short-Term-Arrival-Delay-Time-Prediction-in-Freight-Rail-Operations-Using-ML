# Short-Term Arrival Delay Time Prediction in Freight Rail Operations Using Data-Driven Models

[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/framework-Jupyter-orange.svg)](https://jupyter.org/)
[![Model-Accuracy](https://img.shields.io/badge/Peak%20Accuracy-91.4%25%20R2-green.svg)]()
[![XAI-Integrated](https://img.shields.io/badge/Explainable%20AI-SHAP-purple.svg)]()

An enterprise-grade predictive intelligence pipeline designed to optimize supply chain visibility by estimating localized short-term arrival delays in freight rail transit systems.

---

## 👥 Project Engineering Team
* **Ritesh Kumar Jena** — Lead Backend Architecture & Git Management
* **Pensa Saroj** — Data Engineering & Anaylsis
* **Subham Pradhan** — Model Architecture & Optimization
* **Nikan Kumar Sahu** — Explainable AI (XAI) & Core Visualization Systems

---

## 📝 Executive Summary & Core Intent
Operational volatility in freight rail networks costs logistics ecosystems millions annually due to compounding arrival uncertainty. Traditional baseline calculations rely on static distance-over-time metrics, which fail to absorb real-time delays across intermediate junctions.

Developed as a collaborative engineering capstone, this software suite introduces an **incremental data-driven prediction framework** that isolates and estimates delays locally at each junction. By checking variance at individual station thresholds, the system provides downstream logistics operators with dynamic, high-fidelity scheduling insights.

### System Pipeline Architecture
```text
[Raw Spatio-Temporal Dataset]
             │
             ▼
[Automated Cleaning & Null Imputation]
             │
             ▼
[Correlation Filter Matrix (>95% Drop Threshold)]
             │
             ▼
[Feature Importance Analysis via LightGBM Baseline]
             │
             ▼
[Hyperparameter-Optimized Ensemble Architecture] ──► [Inference Engine Validation]
             │
             ▼
[SHAP (Shapley Additive exPlanations) Interpretability Layer]
