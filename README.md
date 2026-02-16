# Stock Market Clustering-ML 📈
Analyzing the movement patterns of 60 major companies from 2010–2015 to identify hidden industry relationships using machine learning.

## 🚀 Key Features
- **Scikit-Learn Pipeline**: Automated workflow combining normalization and clustering.
- **Dimensionality Reduction**: Utilized **PCA** for feature extraction and **t-SNE** for high-dimensional visualization.
- **Statistical Correlation**: Heatmap analysis of company movement patterns.
- **Hierarchical Dendrograms**: Visualizing stock "family trees" using Ward’s linkage.

Correlation Heatmap
<p align="center">
  <img src="https://github.com/frankraDIUM/Stock-Market-Clustering-ML/blob/main/correlation%20heatmap.png" />
</p>


Dendrogram
<p align="center">
  <img src="https://github.com/frankraDIUM/Stock-Market-Clustering-ML/blob/main/dendrogram.png" />
</p>

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Scikit-Learn** (KMeans, PCA, Normalizer, Pipeline)
- **Matplotlib/Seaborn** (Data Visualization)
- **SciPy** (Hierarchical Clustering)

## 📊 Methodology
1. **Normalization**: Scaling rows independently to focus on movement patterns rather than price magnitude.
2. **The Elbow Method**: Determining optimal cluster count ($K=4$) via Inertia analysis.
3. **Clustering**: Applying K-Means to group similar equities.
4. **Visualization**: Comparing PCA and t-SNE results for cluster validation.

Inertia (Elbow Method)
<p align="center">
  <img src="https://github.com/frankraDIUM/Stock-Market-Clustering-ML/blob/main/inertia_plot.png" />
</p>

PCA Visualization
<p align="center">
  <img src="https://github.com/frankraDIUM/Stock-Market-Clustering-ML/blob/main/pca.png" />
</p>


t-SNE Visualization
<p align="center">
  <img src="https://github.com/frankraDIUM/Stock-Market-Clustering-ML/blob/main/t-SNE%20visualization.png" />
</p>


## 📈 Results
The model successfully clustered the market into 4 distinct groups:
- **Cluster 0**: Tech & High Growth (Apple, Amazon, Google)
- **Cluster 1**: Consumer Staples/Defensive (Coca-Cola, Pepsi, Walmart)
- **Cluster 2**: Energy & Industrials (Exxon, Chevron, Caterpillar)
- **Cluster 3**: Finance & Banking (JPMorgan, Goldman Sachs)
