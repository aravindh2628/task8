# 🧠 AI & ML Internship - Task 8: K-Means Clustering

## 📌 Objective

Perform unsupervised learning using **K-Means Clustering** to segment customers based on their characteristics. This task demonstrates how clustering can be applied to customer segmentation in marketing and analytics.

---

## 🛠 Tools & Libraries

- Python
- `Pandas`, `NumPy` - for data handling
- `Matplotlib`, `Seaborn` - for visualization
- `Scikit-learn` - for machine learning algorithms and metrics

---

## 📂 Dataset

- **Name**: Mall Customers Dataset  
- **Attributes**:
  - `CustomerID`: Unique ID for each customer
  - `Gender`: Male/Female
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Annual income in thousands
  - `Spending Score (1-100)`: Score assigned by the mall based on spending behavior

- **Source**: [Click here to download](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## 📈 Workflow


1. **Load and explore** the dataset.
2. **Select relevant features**: Age, Income, Spending Score.
3. **Standardize the features** using `StandardScaler`.
4. **Find the optimal number of clusters (K)** using the **Elbow Method**.
5. **Train a K-Means model** on the dataset.
6. **Visualize clusters** using **PCA (2D)**.
7. **Evaluate** the clustering using the **Silhouette Score**.

---

## 📊 Results

- **Optimal K (clusters)**: Determined using the Elbow Method.
- **Silhouette Score**: Indicates how well the clusters are separated.
- **Cluster Visualization**: 2D scatter plot showing customer segments.

---

## 📚 What You’ll Learn

- How K-Means clustering works.
- Importance of feature scaling.
- How to evaluate clustering quality.
- Visualization using PCA and cluster labeling.


---

## 🧠 Conclusion

This project demonstrates the practical use of unsupervised learning for segmenting mall customers. The results can help in targeted marketing, loyalty programs, and personalized services.
