# Mall Customer Segmentation

This project focuses on customer segmentation using **K-Means** and **Hierarchical Clustering** algorithms on the *Mall Customer Segmentation* dataset from Kaggle.

## 📌 Objective
The main goal is to segment customers based on their **annual income** and **spending behavior** in order to better understand customer groups and support business decision-making.

## 📊 Dataset
- Source: Kaggle – Mall Customer Segmentation Data
- Features used:
  - Annual Income (k$)
  - Spending Score (1–100)
- Additional feature:
  - Gender (used only for post-cluster analysis)

## ⚙️ Methodology
1. Data preprocessing and feature selection
2. Standardization using `StandardScaler`
3. Determination of optimal number of clusters using:
   - Dendrogram (Hierarchical Clustering)
4. Customer segmentation using:
   - K-Means (k = 3)
   - Hierarchical Clustering (Ward linkage)
5. Cluster profiling and interpretation
6. Gender distribution analysis across clusters

## 🧩 Customer Segments
Based on the analysis, customers are grouped into three meaningful segments:
- **Price-Sensitive Main Segment**
- **Potential Premium Customers**
- **Premium Customers**

## 📈 Visualization
- Scatter plots for cluster visualization
- Dendrogram for hierarchical clustering
- Cluster-wise statistical summaries

## 🛠️ Technologies Used
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- scipy

## 📝 Conclusion
Both K-Means and Hierarchical Clustering methods produced consistent and interpretable customer segments. The results can be used to develop targeted marketing strategies for different customer groups.

---

*This project is intended for educational and portfolio purposes.*
