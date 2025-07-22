# 🍃 LEAF LOGIC  
### From Transparent Trees to Explainable Forests  
#### Interpretable AI for Real-World Decisions

> 🌿 Where prediction meets explanation.  
> Leaf Logic turns decision trees and boosted forests into **trustable, transparent AI** for real-world use.

---

## 🧩 Problem Statement

How do we not only **predict** customer behavior — but also **explain it**?

This project solves a **binary classification** task (term deposit subscription) using interpretable machine learning models. It combines the **intuitiveness of decision trees** with the **power of XGBoost**, layered with **SHAP explainability** for fairness, trust, and transparency.

---

## 🧠 Architecture Overview

### 🌱 Phase 1: Decision Tree (Root Level Logic)
- Built a baseline Decision Tree using Gini/Entropy splits.
- Transparent paths from root to leaf.
- Visual interpretation of how features influence decisions.

### 🌳 Phase 2: XGBoost + SHAP (Explainable Forest)
- Boosted performance using XGBoost.
- Added SHAP (SHapley Additive Explanations) for:
  - **Global insights** (most influential features)
  - **Local reasoning** (why this customer was predicted “yes” or “no”)
  - **Force plots** for individual explanations.

---

## 📊 Dataset

**UCI Bank Marketing Dataset**  
- 41,188 records, 16 features  
- Key features: age, job, marital status, education, balance, duration, etc.  
- Target: `y` → Did the client subscribe to a term deposit?

---

## 🧰 Tech Stack

| Tool/Library      | Purpose                         |
|-------------------|----------------------------------|
| Python            | Core programming language        |
| pandas, numpy     | Data manipulation                |
| scikit-learn      | ML pipeline + Decision Tree      |
| XGBoost           | Ensemble boosting model          |
| SHAP              | Model explanation / fairness     |
| matplotlib, seaborn | Data and SHAP visualizations    |

---

## 🌟 Key Wins

- 🔍 **Interpretability-first approach** from the ground up
- 🌐 **Global & Local Explainability** with SHAP
- 🎯 **Business-aligned predictions** — no black boxes
- 🧠 **Trustworthy ML decisions** aligned with ethical AI

---

## 📸 Visual Highlights (see `/visuals`)

- Decision Tree Diagram  
- SHAP Summary Plot  
- SHAP Force Plot (per instance)  
- Feature Importance Bar Charts  

---

## 🚀 Run Locally

1. Clone this repo:
```bash
git clone https://github.com/your-username/leaf-logic.git
cd leaf-logic
```
Install dependencies:

```bash
pip install -r requirements.txt
```
Launch Jupyter:

```bash

jupyter notebook decision_tree_customer_prediction.ipynb
```

👤 Author
Mrityunjya Sankar
AI/ML Engineer | Ethical Intelligence Architect
