# Clustering-with-K-Means
Task 8: Clustering with K-Means
# 🌀 Clustering with K-Means

This project implements **K-Means clustering** on the **Mall Customers dataset**, focusing on customer segmentation based on their annual income and spending score.

## 📂 Dataset

- **Dataset used:** Mall_Customers.csv  
- **Features:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## 🚀 Steps Implemented

1️⃣ **Import Libraries:**  
- `pandas`, `matplotlib`, `sklearn (KMeans, StandardScaler, silhouette_score)`, `PCA`.

2️⃣ **Load Dataset:**  
- The dataset is loaded using `pandas.read_csv()`.

3️⃣ **Preprocess Data:**  
- Selected `Annual Income (k$)` and `Spending Score (1-100)` as features.  
- Scaled the data using `StandardScaler`.

4️⃣ **Visualize (Optional PCA):**  
- Applied `PCA` to reduce data to 2D and visualized using a scatter plot.

5️⃣ **Elbow Method:**  
- Used the **Elbow Method** to find the optimal number of clusters (K), plotting inertia for K = 1 to 10.

6️⃣ **K-Means Clustering:**  
- Fitted `KMeans` with the optimal K (chosen as 5).  
- Added cluster labels to the dataset.

7️⃣ **Visualize Clusters:**  
- Plotted the clustered data with color coding using `matplotlib`.

8️⃣ **Evaluate Clustering:**  
- Calculated and printed the **Silhouette Score** to assess cluster quality.


---

## 💬 Interview Questions 

1️⃣ **What is K-Means Clustering?**  
K-Means is an unsupervised algorithm that partitions data into K distinct clusters based on distance to the centroid of a cluster.

2️⃣ **How does the Elbow Method work?**  
The Elbow Method finds the optimal K by plotting inertia vs. K and identifying the 'elbow' point where inertia decreases more slowly.

3️⃣ **What is Inertia?**  
Inertia is the sum of squared distances between each point and its cluster centroid (within-cluster variance).

4️⃣ **What is the Silhouette Score?**  
It measures how similar a point is to its own cluster vs. others. A value close to +1 indicates good clustering.

---

## 🛠️ How to Run

# Open the notebook
jupyter notebook Clustering_with_K_Means.ipynb

