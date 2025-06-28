# Classification-with-Logistic-Regression

Logistic Regression Project – Breast Cancer Dataset

Is project me maine logistic regression ka use karke ek binary classifier banaya hai jo breast cancer ke data par train hua hai. Ye model predict karta hai ki tumor malignant hai ya benign, based on different features of cell nuclei.

📄 Dataset Details

Dataset source: sklearn.datasets.load_breast_cancer()

Total records: 569

Features: 30 numeric columns (mean, standard error, worst)

Target: 0 = malignant, 1 = benign

Maine data ko breast_cancer.csv me export bhi kiya hai taaki csv ke format me bhi use kar sakein.

🔧 Tools/Libraries Used

Python

Pandas

Scikit-learn

Matplotlib

Numpy

🧪 Steps Followed

Dataset load kiya aur basic explore kiya

Features aur target variable ko alag kiya

Data ko training aur testing set me divide kiya (80/20 split)

Features ko scale kiya using StandardScaler

Logistic Regression model train kiya

Model predictions aur evaluation metrics nikale

ROC curve plot kiya

✅ Evaluation Results

Accuracy: ~98%

Precision, Recall, F1-score: sabhi kaafi high aaye (around 98%)

Confusion Matrix:

[[41  1]
 [ 1 71]]

ROC Curve se model ka performance visually verify kiya
