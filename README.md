# Wholesale Customer Dimensionality Reduction

An unsupervised machine learning project that analyzes wholesale customer spending behavior using PCA and UMAP to reveal hidden structure and key purchasing patterns for business insight.

## Dataset
- **Source:** Wholesale Customers Dataset  
- **Format:** CSV  
- **Records:** 440 customers  
- **Features:** 6 numerical spending attributes  
  - Fresh  
  - Milk  
  - Grocery  
  - Frozen  
  - Detergents_Paper  
  - Delicassen  
- **Target:** None (Fully Unsupervised)

## Models Used
- **Algorithm 1:** Principal Component Analysis (PCA)  
- **Algorithm 2:** UMAP (Uniform Manifold Approximation and Projection)  
- **Scaler:** StandardScaler for feature normalization  

## Model Performance (Unsupervised Evaluation)
| Metric                          | Value     |
|----------------------------------|-----------|
| Variance Preserved (PC1 + PC2)  | 72.46%    |
| Total PCA Components            | 6         |
| Visualization Dimensions       | 2D        |


## Key Findings
- PCA identified two dominant behavioral patterns:
  - **PC1:** Household & staple goods spending (Milk, Grocery, Detergents_Paper)
  - **PC2:** Fresh & specialty food spending (Fresh, Frozen, Delicassen)
- UMAP revealed additional non-linear structure and clearer behavioral separation.
- Customer behavior exists on a continuous spectrum rather than in rigid clusters.

## Business Value
- Understand real customer purchasing behavior  
- Support marketing and customer profiling strategies  
- Improve inventory planning and demand forecasting  
- Assist in retail and wholesale decision-making  

## Visualizations Included
- Histogram & Box Plots for EDA  
- Correlation Heatmap  
- PCA Scree & Cumulative Variance Plot  
- PCA 2D Projection  
- UMAP 2D Projection  

## Dependencies
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- umap-learn  
