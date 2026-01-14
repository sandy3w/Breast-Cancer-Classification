# Breast-Cancer-Classification

This repository contains a small machine learning project that classifies breast cancer tumors as malignant or benign using the Breast Cancer dataset from scikit-learn.

---

## Project Overview

Two models are implemented to classify tumors as **malignant** or **benign**:

1. **Logistic Regression** – Test accuracy: **92.98%**
2. **Neural Network** – Test accuracy: **96.49%**

---

## Repository Structure

```
/Breast-Cancer-Classification/
├─ BreastCancerLogReg.ipynb    # Logistic Regression model
├─ BreastCancerClassNN.ipynb   # Neural Network model
├─ data.csv                    # For display purposes only
└─ README.md                   # This file
```

> Note: The notebooks load the dataset directly from scikit-learn. `data.csv` is included just for reference.

---

## How to Run

1. Clone the repository:

```bash
git clone <repo_url>
cd Breast-Cancer-Classification
```

2. Open either notebook in Jupyter or VSCode and run the cells:

```bash
jupyter notebook BreastCancerLogReg.ipynb
jupyter notebook BreastCancerClassNN.ipynb
```

No additional setup is required.

---

## Notes

* No external datasets or preprocessing are necessary.
