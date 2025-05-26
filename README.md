# 🍽️ Zomato Restaurant Clustering Project

This project analyzes restaurant data from Zomato and applies clustering algorithms to group restaurants based on cuisine type, cost, and average ratings. The goal is to enable better personalization, recommendation systems, and targeted marketing strategies for food platforms.

---

## 📌 Objective

Segment restaurants into distinct clusters to identify patterns such as:
- Premium vs budget eateries
- Cuisine-based groupings
- Rating-based service quality indicators

---

## 🧩 Dataset

- **Source**: Zomato restaurant data (public dataset)
- **Key Columns**:
  - `Name`
  - `Cuisines`
  - `Cost`
  - `Rating`
  - `Review`

---

## 🧹 Data Preprocessing

- Cleaned `Cuisines` text data
- Handled missing values in `Cost` and `Rating`
- Used `MultiLabelBinarizer` to handle multiple cuisines per restaurant
- Filtered out rare cuisines (appearing less than 8 times)

---

## 🔍 Feature Engineering

- Calculated **average rating per restaurant** using reviews
- Encoded multiple cuisines into binary format
- Scaled features using `StandardScaler`

---

## 🤖 Clustering Techniques

### ✅ K-Means Clustering
- Optimal clusters found using **Elbow Method** and **Silhouette Score**
- Final number of clusters: **07**

### ✅ Hierarchical Clustering
- Used **Dendrogram** to visualize linkage distances
- Applied **Agglomerative Clustering** with `ward` linkage
- Final number of clusters: **7**

---

## 📈 Visualizations

- **Heatmaps**: Cuisine vs cluster distribution
- **Bar Plots**: Cost and rating averages by cluster
- **Scatter Plots**: Cost vs Rating colored by cluster
- **Dendrogram**: For hierarchical cluster structure

---

## 💡 Key Insights

- **Cluster 2**: High-cost Italian/Continental restaurants
- **Cluster 4**: Affordable North Indian spots
- **Cluster 6**: Asian cuisine with high ratings

These insights can help in decision-making for:
- Targeted ads
- Restaurant recommendations
- Location-based expansion

---

## 🧰 Tech Stack

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (KMeans, AgglomerativeClustering, silhouette_score)
- Jupyter Notebook

---

## 🛠️ Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Sparse cuisine data | Filtered cuisines < 8 appearances |
| Missing values | Imputed with mean |
| Choosing number of clusters | Used Elbow + Silhouette + Dendrogram |
| Interpreting results | Visualized clusters with plots |

---

## 🚀 Future Improvements

- Add **location coordinates** for geo-based clustering
- Apply **PCA or t-SNE** for 2D visualization of clusters
- Extend to a **recommendation engine** using cluster similarity

---

## 📎 Project Status

✅ Data Cleaning  
✅ Feature Engineering  
✅ Clustering (KMeans + Hierarchical)  
✅ Visualization & Insights  
🚧 Recommendation System (Next Phase)

---

## 📫 Contact

For questions or collaborations, connect with me on [LinkedIn](linkedin.com/in/shankar-belavatagi-6602b023a)

---

