# 🌍 Density-Based Clustering using DBSCAN on the Country Socioeconomic Dataset

## 📌 Project Overview

This project applies the **Density-Based Spatial Clustering of Applications with Noise (DBSCAN)** algorithm to analyze socioeconomic and health indicators of 167 countries. Unlike centroid-based clustering methods, DBSCAN automatically discovers clusters based on data density and identifies outlier countries as noise without requiring a predefined number of clusters.

The project demonstrates a complete unsupervised machine learning workflow, including data preprocessing, feature scaling, hyperparameter tuning, clustering, visualization, and interpretation of the resulting clusters.

---

## 🎯 Objectives

- Explore and preprocess the Country Socioeconomic Dataset.
- Apply feature scaling using StandardScaler.
- Determine suitable DBSCAN parameters using the k-distance graph.
- Perform density-based clustering using DBSCAN.
- Identify clusters and noise (outlier) countries.
- Visualize clusters using Principal Component Analysis (PCA).
- Interpret socioeconomic patterns among different country groups.
- Compare DBSCAN with K-Means clustering (Bonus).

---

## 📂 Dataset

**Dataset:** Country-data.csv

The dataset contains socioeconomic and health-related indicators for **167 countries**, including:

- Child Mortality
- Exports
- Health Expenditure
- Imports
- Income
- Inflation
- Life Expectancy
- Total Fertility
- GDP per Capita

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📊 Project Workflow

1. Data Loading & Exploration
2. Data Cleaning and Preprocessing
3. Feature Standardization
4. Hyperparameter Tuning (eps & min_samples)
5. DBSCAN Clustering
6. Cluster Evaluation
7. PCA-based Visualization
8. Cluster Interpretation
9. Comparison with K-Means (Bonus)

---

## 📈 Results

- Successfully grouped countries based on socioeconomic indicators.
- Detected outlier countries automatically using DBSCAN.
- Visualized clusters using PCA.
- Identified meaningful development patterns across different country groups.

---

## 📁 Repository Structure

```
├── Country_data_assignment.ipynb
├── Country-data.csv
├── README.md
└── images/
```

---

## 🚀 How to Run

1. Clone this repository.
2. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 📚 Learning Outcomes

This project strengthened my understanding of:

- Unsupervised Machine Learning
- Density-Based Clustering (DBSCAN)
- Data Preprocessing
- Hyperparameter Tuning
- Principal Component Analysis (PCA)
- Cluster Evaluation
- Data Visualization

---

## 👨‍💻 Author

**Muhammad Miswan**

Data Science Student | Machine Learning Enthusiast | Python Developer

---

### ⭐ If you found this project helpful, consider giving it a star.
