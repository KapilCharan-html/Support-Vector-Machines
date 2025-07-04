
🧠 SVM Binary Classification - Breast Cancer Detection

📄 Task 7: Support Vector Machines (SVM)

This project demonstrates the use of Support Vector Machines (SVM) for both linear and non-linear classification using the Breast Cancer Dataset.


---

🎯 Objective

Apply SVMs for binary classification

Explore both Linear and RBF (Non-linear) kernels

Visualize decision boundaries (using 2D data)

Perform hyperparameter tuning (C, gamma)

Evaluate model with cross-validation



---

🛠 Tools & Libraries

Python 3.x

scikit-learn

numpy

matplotlib



---

📊 Dataset

Breast Cancer Wisconsin Dataset

Features: 30 numeric features describing cell nuclei

Target:

0 = Malignant (Cancerous)

1 = Benign (Non-Cancerous)


Dataset is loaded directly from sklearn.datasets



---

🚀 Steps Performed

1. Load and prepare the dataset


2. Standardize features for better model performance


3. Train SVM with:

Linear Kernel

RBF (Radial Basis Function) Kernel



4. Visualize decision boundaries using 2 selected features


5. Perform hyperparameter tuning using GridSearchCV


6. Evaluate model using:

Accuracy Score

Classification Report

5-Fold Cross-Validation





---

📂 Project Structure

SVM_Binary_Classification/
│
├── svm_classification.py      # Complete Python Code
├── README.md                   # Project Description
└── requirements.txt            # Required Libraries


---

📷 Sample Output

✅ Accuracy with Linear Kernel
✅ Accuracy with RBF Kernel
✅ Best Hyperparameters after GridSearchCV
✅ 2D Visualization of Decision Boundary (for selected features)


---

⚡ How to Run

1. Install dependencies:

pip install -r requirements.txt


2. Run the Python script:

python svm_classification.py




---

📌 Notes

For full dataset (30 features), visualization is not possible; 2D plots use first 2 features for demonstration.

Hyperparameter tuning improves model performance.

SVM works well for both linear and complex non-linear boundaries.



---

📚 References

scikit-learn SVM Documentation

Breast Cancer Dataset Info




