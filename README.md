# 📊 Explainable HR Analytics & Counterfactual AI Dashboard

An end-to-end Machine Learning system and interactive Streamlit web application designed to predict employee promotion eligibility at managerial evaluation checkpoints while providing decision transparency via **SHAP (SHapley Additive exPlanations)** and actionable, goal-oriented career roadmaps via **DiCE Counterfactual Analysis**.

---

## 🌟 Key Features

* **Predictive Performance:** Decision Tree Classification pipeline with **SMOTE class rebalancing** handling imbalanced HR evaluation records.
* **Explainable AI (XAI):** Game-theoretic local and global feature attribution via **SHAP** to reveal exact factors driving promotion predictions.
* **Counterfactual "What-If" Engine:** Generates minimal-change parameter targets via **DiCE (Diverse Counterfactual Explanations)** showing unpromoted employees precisely what metrics they need to improve to earn eligibility.
* **Dynamic Streamlit Web App:** Interactive UI featuring real-time sliders, department filters, confidence metrics, and comparative baseline tables.

---

## 📂 Project Architecture

```text
├── app.py              # Interactive Streamlit Web Dashboard UI
├── pipeline.py         # End-to-End ML Pipeline (Preprocessing, SMOTE, SHAP, DiCE)
├── requirements.txt    # Project Dependencies
├── .gitignore          # Environment & Cache Exclusion Rules
└── README.md           # Project Documentation
