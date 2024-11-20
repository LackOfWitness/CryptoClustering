
<div align="center">
  <img src="Crypto_Clustering_Graphic.png" alt="Cryptocurrency Clustering Analysis" style="border: 2px solid #ddd; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); max-width: 800px; margin: 20px 0;">
</div>

# Cryptocurrency Clustering Analysis


## Overview
This project analyzes cryptocurrency market behavior using unsupervised machine learning techniques. 
By applying K-means clustering and Principal Component Analysis (PCA), we examine how cryptocurrencies 
are grouped based on their 24-hour and 7-day price changes.

## Data Analysis Process

### Data Preparation
- Loaded and preprocessed cryptocurrency market data 
- Normalized features using StandardScaler
- Created scaled DataFrame preserving original indices

### Clustering Analysis
- Used elbow method to find optimal k value
- Performed K-means clustering on scaled data
- Visualized cryptocurrency clusters based on price change percentages

### PCA Optimization
- Applied PCA to reduce dimensions to 3 principal components
- Achieved 89.5% explained variance ratio
- Compared clustering results between original and PCA-transformed data

## Key Findings
- Identified 4 distinct cryptocurrency clusters in both original and PCA analyses
- PCA transformation maintained high data integrity while reducing features
- Clustering with PCA showed clearer cluster separation
- Results suggest natural groupings in cryptocurrency price behaviors

## Technologies Used
- Python
- Scikit-learn
- Pandas
- hvPlot
- Jupyter Notebook

## Installation
- Install Python 3.11
- Install Jupyter Notebook
- Install hvPlot
- Install Scikit-learn
- Install Pandas

## Usage
1. Clone this repository
2. Open Jupyter Notebook
3. Run Crypto_Clustering.ipynb
4. View analysis results and visualizations

## Files
- `Crypto_Clustering.ipynb`: Main analysis notebook
- `Resources/crypto_market_data.csv`: Cryptocurrency price data
- `README.md`: Project documentation

## Data Source
Data provided by edX Boot Camps LLC for educational purposes.

## Author
Sergei N. Sergeev
sergei.sergeev.n@gmail.com

## License
MIT License
