# PCA & K-Means Clustering - Customer Segmentation for B2B AI Services

A classical unsupervised learning project :D Im using Principal Component Analysis (PCA) and K-means clustering to identify customer segments and recommend target markets for a company, none of the data is confidential. 

## Methods
- Data standardization
- Principal Component Analysis (PCA) for dimensionality reduction
- K-means clustering with elbow method for cluster selection
- Business interpretation of principal components and customer segments

## Results

| Metric | Value |
|---|---:|
| Observations | 200 |
| Original Variables | 13 |
| Principal Components Retained | 4 |
| Variance Explained (PCA) | 65.3% |
| Number of Clusters | 4 |
| Between-Cluster Variance Explained | 41.3% |

### Customer Segments identified
- Large, traditional organizations with low AI readiness, best suited for conventional equipment sales.
- Organizations preferring service contracts and external expertise, strong candidates for AI service offerings.
- AI ready companies with high innovation potential but cautious about data sharing.
- Digitally mature organizations with strong internal capabilities. Selective opportunities for advanced AI solutions.

## Full Analysis
See [PCA_KMK.pdf](PCA_KMK.pdf) for complete code, visualizations and model discussion.

## Tools
R · tidyverse · princomp · factoextra · ggplot2 · dplyr · flextable · Quarto
