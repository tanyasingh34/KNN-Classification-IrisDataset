# 🌸 K-Nearest Neighbors (KNN) Classification - Iris Dataset

# Objective
To implement and understand the K-Nearest Neighbors (KNN) algorithm for classification problems using the Iris dataset. This task focuses on normalization, K value tuning, evaluation, and visualizing decision boundaries.

---

# Dataset Used
**Iris Dataset**  
Path: `C:\Users\TANYA\OneDrive\Desktop\archive\Iris.csv`  
Contains 150 samples of 3 species of Iris flowers (Setosa, Versicolor, Virginica) with 4 numerical features.

---

# Steps Performed

1. **Data Loading and Cleaning**
   - Removed unnecessary ID column.
   - Separated features and labels.

2. **Feature Normalization**
   - StandardScaler was used to normalize features due to KNN’s reliance on distance metrics.

3. **Model Implementation**
   - Used `KNeighborsClassifier` from scikit-learn.
   - Tried values of K = 1, 3, 5, 7.

4. **Evaluation**
   - Calculated accuracy and plotted confusion matrix.
   - Best performance was observed with `K = 3`.

5. **Visualization**
   - Plotted decision boundary using first two features to show class separation.

---

# Accuracy Results

| K Value | Accuracy |
|--------:|----------|
| 1       | XX%      |
| 3       | XX%      |
| 5       | XX%      |
| 7       | XX%      |

_(Replace XX with your actual output)_


# Key Learnings

- KNN is a lazy learner and doesn’t build a model during training.
- Normalization is crucial since distance metrics are sensitive to scale.
- Choice of `K` impacts bias-variance trade-off.
- Decision boundaries can become complex for lower values of `K`.

#  Output Visuals

# Confusion Matrix (K=3)
![Confusion Matrix](confusion_matrix_k3.png)

# Decision Boundary (K=3)
![Decision Boundary](decision_boundary_k3.png)


# Libraries Used

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
