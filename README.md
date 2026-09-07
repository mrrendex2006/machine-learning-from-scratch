# Machine Learning From Scratch 🧠

A step-by-step, beginner-friendly walkthrough of core machine learning algorithms — built while learning them myself, so every notebook keeps the explanations a first-time learner actually needs.

If you're a student trying to *actually* understand ML instead of just copy-pasting `model.fit()`, this repo is for you.

## Why this repo exists

Most ML tutorials skip straight to `sklearn.fit()` without explaining what's happening underneath, or why one algorithm was chosen over another. This repo tries to close that gap — each algorithm is implemented and explained with real datasets, so the logic (and the "why") is visible, not just the code.

## What's inside

| Folder | Algorithm | Datasets used |
|---|---|---|
| `01_linear_regression` | Linear Regression | California housing, diamonds, house pricing, MPG, tips |
| `02_logistic_regression` | Logistic Regression | Breast cancer, AI impact |
| `03_support_vector_mechine` | Support Vector Machine | Breast cancer |
| `04_KNN` | K-Nearest Neighbors | Breast cancer, AI impact |
| `05_Decission_tree` | Decision Tree | Iris dataset (with visual diagram) |
| `06_Random_forest` | Random Forest | AI impact |
| `practice datasets` | Iris dataset | Practice notebooks | telescope, AI_impact, general ML practice |

Each algorithm folder includes its own short README explaining the concept before you dive into the notebooks.

## Concepts covered

- Train/test splits & cross-validation
- Feature scaling (StandardScaler) & encoding (LabelEncoder)
- Regularization (Ridge, Lasso)
- Model evaluation: R², MAE, confusion matrix
- Algorithm selection based on dataset characteristics
- PCA & dimensionality reduction

## Getting started

```bash
git clone https://github.com/mrrendex2006/machine-learning-from-scratch.git
cd machine-learning-from-scratch
pip install -r requirements.txt   # see note below
jupyter notebook
```

> **Note:** a `requirements.txt` see the improvement list below.

Open any numbered folder and start with its notebook + README in order — they're built to be followed sequentially, from linear regression through random forests.

## Roadmap / what I'm adding next

- [ ] Naive Bayes
- [ ] K-Means clustering
- [ ] Neural networks from scratch (NumPy only)
- [ ] Model comparison notebook across all algorithms on one dataset

## About me

🎓 first-year B.Tech student, AI/ML track
💻 Learning in public — Python, C++, and core ML fundamentals
🚀 Follow along as this repo grows with each new concept

---

*Found this useful or spot something to improve? Issues and stars are welcome — this is a learning project and feedback helps.*
