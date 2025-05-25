# Blockchain Wallet Segmentation of a Decentralized Exchange (UniSwap)

## Overview

This repository contains a comprehensive analysis and clustering of blockchain wallet addresses based on their historical trading behavior on the UniSwap decentralized exchange (DEX). The primary objective is to identify meaningful behavioral patterns among wallet addresses through classical and deep learning-based clustering approaches.

## Dataset

The dataset was constructed by collecting and merging:
- Wallet addresses from UniSwap Sub-Graph
- Transaction history from Etherscan API
- Token balances from Covalent API

This resulted in 2539 unique wallet addresses with complete transaction logs.

## Methodology

The analysis pipeline includes the following major steps:

1. Data Preprocessing and Feature Engineering  
   Transaction logs are aggregated per wallet address to extract behavioral features such as frequency, volume, and timing.

2. Exploratory Data Analysis (EDA)  
   Preliminary statistical summaries and correlation heatmaps are used to understand feature relationships and distributions.

3. Classical Clustering Techniques  
   - K-Means Clustering
   - Agglomerative Hierarchical Clustering
   - DBSCAN
   - Gaussian Mixture Models (GMM)

   Optimal cluster numbers are selected using the Elbow Method, Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Score.

4. Deep Learning-Based Clustering  
   - Autoencoders
   - Variational Autoencoders
   - Deep Embedded Clustering (DEC)
   - Deep InfoMax Clustering

   These methods are implemented to capture non-linear patterns and high-dimensional embeddings of wallet behavior.

5. Performance Comparison and Evaluation  
   All models are evaluated and compared based on consistency, separability of clusters, and interpretability of outputs.

## Key Dependencies

- Python 3.8+
- NumPy, Pandas
- Scikit-learn
- PyTorch
- TensorFlow/Keras (for autoencoders)
- Matplotlib, Seaborn
- UMAP, HDBSCAN

## How to Use

Clone the repository and run the notebook sequentially:

```bash
git clone https://github.com/yourusername/UniswapWalletSegmentation.git
cd UniswapWalletSegmentation
jupyter notebook DatasetAnalysisMScThesis.ipynb
```

Make sure all dependencies listed above are installed in your Python environment.

## Applications

- Wallet user classification
- Risk segmentation in DeFi ecosystems
- Behavioral finance analysis
- De-anonymization research

## License

This project is licensed under the MIT License.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
