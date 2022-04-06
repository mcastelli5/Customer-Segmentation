# Customer-Segmentation

The objective of this project was to create a customer segmentation strategy to assist the e-commerce company (Ecom Co.) with better understanding their customers. This initiative will allow the company to unlock a wide range of cross-functional value to implement into various business lines including marketing, sales, planning, etc. With a more comprehensive understanding of Ecom's consumers, Ecom can now start to provide curated advertisements, products, promotions, sales, and feedback to consumers based on their grouping (segment).

## Process Overview
- ETL
  - Better understand values, duplicates, missing values, etc.
- Preprocessing
  - Create retention table
  - Create RFM values
  - Adjust data to kMeans clustering assumptions (skewness and scaling)
- Clustering
  - Determine amount of clusters
  - Fit/Transform
- Inisghts & Analysis

## Lessons Learned
- The importance of normalization and sclaing for features (especially kMeans clustering since it uses Euclidean distance in the algorithm)
- Business Sense: when and where the "proof-of-concept" can differentiate from vacuum examples (real world usage)

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Datetime
- KMeans
- StandardScaler
- Scipy.Stats
