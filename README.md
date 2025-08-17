# Uniswap User Profiling via Deep Clustering: Behavioral Patterns and Economic Implications for Decentralized Exchanges
This Google Colab Notebook carries out the data importing, PDA, EDA, clustering algorithm application and intra-cluster analysis for the bear market regime data.

**Data Source:**  All of the data imported through Google Drive into this Notebook were extracted from the Google BigQuery Ethereum Cryptocurrency dataset using the BigQuery Studio platform.

**Objectives:**
1.	To apply feature engineering techniques to aggregate wallet activity data into a format suitable for behavioral clustering and temporal comparison.
2.	To perform clustering analysis to identify distinct user groups based on wallet behavior in each market phase.
3.	To determine the key features influencing wallet cluster formation and differentiation.

**Contents:**
1. Manual K-Means Clustering Application
2. Classical Clustering Algorithms Application
- 2.1 K-Means Clustering
- 2.2 Agglomerative Clustering
- 2.3 GMM Clustering
- 2.4 DBSCAN Clustering
3. PCA Application
- 3.1 K-Means Clustering
- 3.2 Agglomerative Clustering
- 3.3 GMM Clustering
- 3.4 DBSCAN Clustering
4. Deep-Learning Based Clustering
- 4.1 Variation Autoencoder Model
  - VAE + K-Means Clustering
  - VAE + Agglomerative Clustering
  - VAE + GMM Clustering
  - VAE + DBSCAN Clustering
- 4.2 Deep InfoMax Clustering
  - Deep InfoMax + K-Means
  - Intra-Cluster Analysis
- 4.3 Deep Embedded Clustering
- 4.4 Self-Organizing Map Clustering


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
