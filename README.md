# 📊 Cryptoclustering

A clustering analysis project that groups cryptocurrencies based on their price change behavior. The results compare full-featured clustering versus dimensionality reduction with PCA.

## 🧪 Project Overview

- Scaled the cryptocurrency dataset using `StandardScaler`
- Identified the optimal number of clusters using the elbow method
- Applied K-Means clustering to both the original and PCA-transformed data
- Reduced features to three principal components using PCA (~89.5% variance retained)
- Compared cluster performance using interactive visualizations

## 💡 Key Insights

- Optimal cluster count: **k = 4** for both methods  
- PCA improved visualization clarity and separation between clusters  
- Dimensionality reduction preserved structure while minimizing complexity  

## 📊 Tools & Libraries

- Python  
- pandas  
- scikit-learn  
- hvPlot  
- Jupyter Notebook  

## 📁 Repository Structure
├── cryptoclustering_starter_data/ │ 
  └── crypto_market_data.csv 
  ├── crypto_clustering.ipynb 
├── README.md

## ⚙️ Use Case

Segmenting cryptocurrencies based on historical price behavior supports data-driven strategies for investment, market categorization, or performance tracking. PCA helps refine the analysis by reducing noise and highlighting essential patterns.
