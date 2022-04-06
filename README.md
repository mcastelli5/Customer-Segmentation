# Customer-Segmentation

The objective of this project was to create a customer segmentation strategy to assist the e-commerce company (Ecom Co.) with better understanding their customers. This initiative will allow the company to unlock a wide range of cross-functional value to implement into various business lines including marketing, sales, planning, etc. With a more comprehensive understanding of Ecom's consumers, Ecom can now start to provide targeted advertisements, products, promotions, sales, and feedback to groups of consumers based on their segment.

## Process Overview
1. Data Discovery (EDA)
  - Scope of data (~1 year)
  - Better understand values, duplicates, missing values, etc.
  - Answer simple questions i.e. repeat buyers? Countries with highest avg. UnitPrice
2. Preprocessing Data for ML usage
  - Create retention table
  - Create RFM values
  - Adjust data to kMeans clustering assumptions (skewness and scaling)
3. Perform the Clustering
  - Determine amount of clusters
  - Fit/Transform
4. Insights & Analysis
  - Something smart

## Results
The deliverable for Ecom Co. was a clear time-cohort segmentation of their customers over the past year based on their transaction history. This achieves Ecom's goal to better understand their customers, in addition to finding common purchasing trends across all customers. Depending on Ecom's priorities, this customer segmentation enables them to provide a tailored approach to each segment and attempt to gain value from this more strategic approach.

## Lessons Learned
- The importance of normalization and sclaing for features (especially kMeans clustering since it uses Euclidean distance in the algorithm)
- Business Sense: when and where the "proof-of-concept" can differentiate from vacuum examples (real world usage)

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Datetime
- KMeans (sklearn.cluster)
- StandardScaler (sklearn.preprocessing)
- PowerTransformer (sklearn.preprocessing)
- Make_pipeline (sklearn.pipeline)
