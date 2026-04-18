# 🛒 Wholesale Customer Segmentation

## 📌 Project Overview
This project applies **unsupervised machine learning** to segment wholesale customers based on their annual spending on six product categories. The goal is to identify distinct customer groups for targeted marketing campaigns.

## 👥 Team Members & Contributions
| Member | Algorithm |
|--------|-----------|
| **Mr. Narith Sopannha** | K‑Means Clustering |
| **Mr. Tha Rotanak** | Hierarchical Clustering |
| **Mr. Lach Brohous** | DBSCAN |

## 📊 Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers) / [Kaggle](https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set)
- **Citation**: Cardoso, M. (2013). *Wholesale customers* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5030X
- **Samples**: 440 customers
- **Features**: Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicassen

## 🧠 Algorithms Compared
| Algorithm | Silhouette Score | Davies‑Bouldin | Calinski‑Harabasz |
|-----------|------------------|----------------|--------------------|
| K‑Means (k=3) | 0.5483 | 0.9279 | 140.14 |
| **Hierarchical (k=2)** | **0.7925** | **0.9086** | **105.44** |
| DBSCAN (eps=1.5, min_samples=3) | 0.4213 | 1.9114 | 43.36 |

> ✅ **Best Model**: Hierarchical Clustering (highest silhouette score)

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/Nha04/G6_wholesale_customer_segmentation.git
2. Install dependencies
   pip install -r requirements.txt
3. Launch Jupyter Notebook and run Group6_project.ipynb

## 📈 Key Visualizations
- Dendrogram for hierarchical clustering
- PCA projections of clusters
- Silhouette score comparison bar chart
- Cluster spending profiles heatmaps

## 💡 Business Insights
- Cluster 1 (High fresh & frozen spenders) → offer fresh produce coupons
- Cluster 2 (High grocery & detergents) → bundle discounts
- Cluster 0 (balanced) → general loyalty rewards

## 📂 Repository Structure
- `Group6_project.ipynb` – Full analysis notebook
- `Wholesale customers data.csv` – Dataset
- `requirements.txt` – Python dependencies
- `README.md` – This file

## 📅 Course
- Machine Learning – Final Project
- Submission date: 18 April 2026
