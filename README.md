# SDC-ACTIVITY

```md
# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The model is trained on a real-world dataset containing anonymized transaction features and predicts whether a transaction is legitimate or fraudulent.

---

## 📌 Project Overview

Credit card fraud detection is an important problem in financial security. This project builds a classification model that analyzes transaction data and identifies suspicious activity with high accuracy.

**Target Classes**
- **0** → Legitimate transaction  
- **1** → Fraudulent transaction  

---

## 📂 Project Structure

```

├── ML_SDC3.ipynb        # Main notebook containing ML implementation
├── output.jpg           # Model output & evaluation result image
└── README.md            # Project documentation

````

---

## 📊 Dataset Information

- **Total Records:** 284,807  
- **Total Features:** 31  

**Columns**
- `Time`
- `V1` to `V28` (PCA-transformed / anonymized features)
- `Amount`
- `Class` (Target variable)

---

## 🧠 Model Performance (from your output)

- **Accuracy:** ~99.95%  
- Evaluation used:
  - Confusion Matrix
  - Precision / Recall
  - F1-Score
  - Classification Report

> Note: Since the dataset is highly imbalanced, focus more on **Recall/F1 for Class 1 (fraud)** than only accuracy.

---

## 🖼 Output Preview

Add this image file in your repo to display results:

```md
![Model Output](output.jpg)
````

---

## 🛠 Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn
* Matplotlib (if used)

---

## 🚀 How to Run the Project

### 1) Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2) Install dependencies

```bash
pip install numpy pandas scikit-learn matplotlib
```

### 3) Run the notebook

```bash
jupyter notebook ML_SDC3.ipynb
```

---

## 📈 Machine Learning Workflow

1. Load dataset
2. Preprocess / split data
3. Train classification model
4. Predict on test set
5. Evaluate using metrics & confusion matrix

---

## 🎯 Objective

To build an accurate fraud detection model that helps identify suspicious financial transactions and reduces potential losses.

---

## 👨‍💻 Author

B.Tech AIML — 6th Semester
Academic Machine Learning Project
