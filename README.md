# clustering-analysis
# 🌸 Clustering Analysis on the Iris Dataset

## 📚 Dataset Overview

The **Iris dataset** is one of the most well-known datasets in machine learning and statistics. It contains **150 instances** of iris flowers categorized into **three species**:  
- *Iris setosa*  
- *Iris versicolor*  
- *Iris virginica*  

Each sample includes the following features:
- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)

🔗 [Dataset Source - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

## 🎯 Objective

To conduct a **comparative performance study** of different clustering algorithms with various **preprocessing techniques** and different **cluster counts**, and evaluate performance using clustering metrics.

---

## ⚙️ Clustering Algorithms Used

- **K-Means Clustering**  
- **Agglomerative (Hierarchical) Clustering**  
- **MeanShift Clustering**

---

## 🧪 Preprocessing Techniques Applied

- No preprocessing (`none`)
- Standard Scaling (`normalize`)
- Power Transformation (`transform`)
- PCA after scaling (`pca`)
- Power Transform + Normalize (`t+n`)
- Power Transform + Normalize + PCA (`t+n+pca`)

---

## 🔢 Cluster Counts Evaluated

- 2 Clusters  
- 3 Clusters  
- 4 Clusters  

---

## 📏 Evaluation Metrics

| Metric | Description |
|--------|-------------|
| **Silhouette Score** | Measures cohesion and separation of clusters |
| **Calinski-Harabasz Index** | Ratio of between-cluster dispersion to within-cluster dispersion |
| **Davies-Bouldin Score** | Lower values indicate better separation between clusters |

---

## 📈 Visualizations

Line plots comparing metric performance:
- 📊 `silhouette_score_plot.png`
- 📊 `calinski_harabasz_plot.png`
- 📊 `davies_bouldin_plot.png`

These plots illustrate how each algorithm and preprocessing combo performs at different cluster counts.

---


## ✅ Conclusion

- Clustering performance varies depending on the **algorithm**, **preprocessing method**, and **number of clusters**.
- The **best combinations** of techniques produce high **silhouette** and **Calinski-Harabasz** scores, and low **Davies-Bouldin** scores.
- This analysis helps in understanding how preprocessing impacts clustering quality and which methods work best for this dataset.

---

## 👨‍💻 Author

**Kunal**  
`B.Tech CSE - Data Science | Thapar Institute of Engineering and Technology`

---

