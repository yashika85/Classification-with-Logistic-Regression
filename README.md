# Classification with Logistic Regression

## 📌 Project Overview

This project demonstrates the implementation of Logistic Regression, a supervised machine learning algorithm used for binary classification.

The project uses the Breast Cancer Wisconsin Dataset from Scikit-learn to classify tumors as either malignant or benign based on cell nucleus measurements.

The objective is to understand the classification workflow, train a Logistic Regression model, and evaluate its performance using different classification metrics.

## 🎯 Project Objectives

- Understand the fundamentals of Logistic Regression.
- Explore and prepare a real-world classification dataset.
- Separate input features and target variables.
- Perform feature scaling using StandardScaler.
- Train and test a Logistic Regression model.
- Evaluate model performance using classification metrics.
- Visualize classification performance using a ROC curve.

## 📂 Dataset Information

**Dataset:** Breast Cancer Wisconsin Dataset

**Source:** `sklearn.datasets.load_breast_cancer()`

| Dataset Property | Details |
|---|---|
| Total Records | 569 |
| Total Features | 30 |
| Problem Type | Binary Classification |
| Target Classes | Malignant and Benign |

**Target Labels:**
- `0` – Malignant
- `1` – Benign

The dataset contains numerical measurements of cell nuclei used to distinguish between the two classes.

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## ⚙️ Project Workflow

### 1. Data Loading and Exploration
- Loaded the Breast Cancer dataset using Scikit-learn.
- Explored the dataset structure and features.
- Separated independent variables and target labels.

### 2. Data Preprocessing
- Divided the dataset into training and testing sets.
- Used an 80:20 train-test split.
- Applied StandardScaler for feature scaling.

### 3. Model Building
- Imported Logistic Regression from Scikit-learn.
- Trained the model using the training dataset.
- Generated predictions on the test dataset.

### 4. Model Evaluation
Evaluated the model using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve

## 📊 Model Performance

The model achieved approximately **98% accuracy** on the test dataset.

### Confusion Matrix

```text
[[41  1]
 [ 1 71]]
```

The ROC curve was also plotted to visualize the model's classification performance.

*Note: These are the results documented in the current project README.*

## 📁 Project Structure

```text
Classification-with-Logistic-Regression/
│
├── Classification with Logistic Regression.ipynb
├── README.md
└── breast_cancer.csv
```

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/yashika85/Classification-with-Logistic-Regression.git
```

**2. Navigate to the project folder**

```bash
cd Classification-with-Logistic-Regression
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

**4. Start Jupyter Notebook**

```bash
jupyter notebook
```

**5.** Open the Logistic Regression notebook and run all cells.

*Note: The dataset is loaded from Scikit-learn. If you use the exported CSV file instead, make sure its path is correct.*

## 📚 Key Learnings

- Understanding supervised machine learning.
- Learning binary classification using Logistic Regression.
- Performing train-test splitting and feature scaling.
- Evaluating classification models.
- Understanding confusion matrices and ROC curves.
- Working with Scikit-learn.

## 🔮 Future Improvements

- Compare Logistic Regression with other classification algorithms.
- Perform cross-validation.
- Add a classification report.
- Experiment with hyperparameter tuning.
- Improve model interpretation and visualization.

## 👩‍💻 Author

**Yashika Khan**

- GitHub: https://github.com/yashika85
- LinkedIn: https://www.linkedin.com/in/yashika-khan-43609832b/

---

⭐ If you find this project useful, feel free to explore the repository.
