# Support Vector Machines (SVM)

This project demonstrates how to use Support Vector Machines for binary classification using the Breast Cancer Dataset (provided in the task instructions). It includes Linear SVM, RBF SVM, Hyperparameter Tuning, and 2D Decision Boundary Visualization.

**📌 Objective**

Use SVMs to perform:

Linear Classification

Non-linear Classification (using RBF kernel)

Margin maximization

Hyperparameter tuning (C & gamma)

Visualization using PCA (2D plot)

**🛠 Tools Used**

Python

NumPy

Pandas

Scikit-learn

Matplotlib

**📂 Project Workflow**
**1️⃣ Load & Prepare Dataset**

Loaded the breast-cancer dataset

Split into features (X) and target (y)

Standardized the data using StandardScaler

Train-test split (80/20)

**2️⃣ Train SVM Models**
🔷 Linear SVM

Kernel = linear

Works best for linearly separable data

Achieved high accuracy

🔶 RBF Kernel SVM

Kernel = rbf

Handles non-linear patterns

Performs better in most real-world datasets

**3️⃣ Hyperparameter Tuning**

Used GridSearchCV to find best:

C (Regularization)

gamma (Kernel coefficient)

This improved model accuracy further.

**4️⃣ 2D Decision Boundary**

Reduced dataset to 2 principal components using PCA

Plotted data + decision boundary of SVM

Colors represent class 0 (Benign) and 1 (Malignant)
