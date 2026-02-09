# Distance-Based Classification Algorithm

A supervised machine learning project implementing a distance-based classification approach to categorize data points based on similarity in feature space. The model predicts the class of a sample by measuring its distance from labeled training instances.

This project demonstrates fundamental concepts in instance-based learning, distance metrics, and non-parametric classification.

---

## 📌 Overview

Distance-based classifiers belong to the family of lazy learning algorithms, meaning they do not build an explicit model during training. Instead, they store training data and perform computation at prediction time.

This implementation focuses on:

* Measuring similarity using mathematical distance functions
* Assigning class labels based on nearest neighbors
* Understanding the impact of feature scaling and dimensionality

---

## 🧠 Algorithm Concept

The classifier works using the following principle:

1. Store all labeled training samples
2. For a new input sample:

   * Compute its distance from every training point
   * Identify the closest sample(s)
   * Assign the class based on the nearest neighbor(s)

This is conceptually similar to the **K-Nearest Neighbors (KNN)** algorithm, depending on how many neighbors are considered.

---

## 🗂 Project Structure

distance-based-classification-algorithm/

│
├── knn.ipynb        # Jupyter notebook containing implementation

├── report.txt       # Project explanation and observations

└── README.md        # Project documentation


---

## 🚀 How to Run

### 1️⃣ Clone the Repository

git clone https://github.com/Subhajeetbal69/distance-based-classification-algorithm.git

cd distance-based-classification-algorithm


### 2️⃣ Install Required Libraries

pip install numpy pandas matplotlib scikit-learn

### 3️⃣ Open the Notebook

jupyter notebook knn.ipynb

Run the cells step by step to:

* Load dataset
* Preprocess data
* Apply distance-based classification
* Evaluate results

---

## 🧪 Workflow

1. **Data Loading** – Import dataset
2. **Preprocessing** – Feature scaling (important for distance calculations)
3. **Distance Computation** – Measure similarity between points
4. **Classification** – Assign labels using nearest neighbors
5. **Evaluation** – Check accuracy and performance

---

## 📚 Learning Outcomes

This project helps in understanding:

* How similarity measures drive classification
* Why feature scaling affects distance-based models
* The difference between **parametric** and **non-parametric** learning
* Trade-offs between model simplicity and prediction cost

---

## 👤 Author

Subhajeet Bal
Distance-Based Classification Algorithm Project

---
