# 🏢 Shopping Mall Segmentation using K-Means Clustering

A data-driven approach to segment shopping malls based on key infrastructure features such as area and store count. This project uses unsupervised learning (K-Means) to uncover meaningful clusters that can inform business decisions like marketing focus, expansion strategy, and leasing optimization.

---

## 📌 Project Objective

Segment malls into distinct groups based on:

- **Total area (sqm)** — reflects mall size and capacity
- **Store count** — indicates commercial density

The goal is to identify different mall types such as:
- Large, high-store-count malls (ideal for flagship stores)
- Compact, urban malls (optimized for footfall)
- Mid-sized malls (balanced format)

---

## 📂 Dataset

- **Source**: [Istanbul Mall Dataset – Kaggle](https://www.kaggle.com/datasets/captaindatasets/istanbul-mall)
- **Format**: Excel (.xlsx)
- **Key Features Used**:  
  - `area (sqm)`  
  - `store_count`  

---

## 🔧 Tools & Technologies

| Category             | Tools Used                          |
|----------------------|-------------------------------------|
| Programming          | Python 3                            |
| Data Manipulation    | Pandas, NumPy                       |
| Visualization        | Matplotlib, Seaborn                 |
| Machine Learning     | Scikit-learn (KMeans Clustering)    |
| Environment          | Google Colab / Jupyter Notebook     |

---

## 📊 Methodology

1. **Data Cleaning**  
   Loaded and verified Excel data, selected relevant numerical features.

2. **Feature Scaling**  
   Standardized features to normalize units and range.

3. **Elbow Method**  
   Identified optimal number of clusters (k) using inertia scores.

4. **K-Means Clustering**  
   Applied clustering to segment malls into distinct groups.

5. **Visualization & Interpretation**  
   Plotted clusters using scatterplots and interpreted cluster profiles.

---

## 📈 Visual Output

> 📌 Sample cluster visualization:  
Clusters segmented by area and store count with distinct labels and color coding.

> 📌 Cluster breakdown:
| Cluster | Description                               |
|---------|-------------------------------------------|
| 0       | Large malls with high store count         |
| 1       | Small, compact malls with fewer stores    |
| 2       | Mid-sized malls with moderate store count |

---

## 💡 Business Insights

- **Cluster 0**: Best suited for luxury or department stores due to their size and variety.
- **Cluster 1**: Great for quick-stop retail, cafes, and dense city areas.
- **Cluster 2**: Standard format malls; good for regional planning and expansion.

---

## 📝 Conclusion

Clustering malls based on their physical and commercial scale provides actionable insights for:
- Strategic mall development
- Customized leasing strategies
- Investment risk assessment

---

## 🧠 Future Improvements

- Add geographic data to segment by location
- Include construction year to factor in mall age
- Explore customer footfall (if available) for deeper segmentation

---

## 📁 Output

Final dataset with assigned cluster labels:  
🔗 `Segmented_Malls.csv`

---

## 🤝 Acknowledgements

- Dataset by [captaindatasets on Kaggle](https://www.kaggle.com/datasets/captaindatasets/istanbul-mall)
- Inspired by real-world use cases in real estate analytics

---

## 🔗 Author

**Shyamal Narayan Patil**  
[GitHub](https://github.com/Patil-data) | [LinkedIn](https://linkedin.com/in/patil-shyamal-narayan)
