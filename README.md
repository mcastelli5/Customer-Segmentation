# Customer-Segmentation

Ecom Co. (fake e-commerce company) wanted to better understand their customers, and uncover any hidden patterns that their consumer transaction data had to offer. This initiative will allow the company to unlock a wide range of cross-functional value to implement into various business lines including marketing, sales, planning, etc.

An unparalleled approach to this business objective is the use of the k-Means clustering algorithm to determine potential customer segments, in addition to cohort analysis which can help answer retention and churn questions. Dependending on that data at hand, customers can be grouped by different aspects such as time, behavior, or size. These groupings can assist in deriving general patterns that consumers align to based on their past actions. With a more comprehensive understanding of Ecom's consumers, Ecom can now start to provide targeted advertisements, products, promotions, sales, and feedback to groups of consumers based on their segment.

## Process Overview
1. Data Discovery (EDA)
  - Scope of data (~1 year)
  - Better understand values, duplicates, missing values, etc.
  - Answer simple questions i.e. repeat buyers? Countries with highest avg. UnitPrice
2. Cohort Analysis
  - Cohort grouping selection (size, time, behavior)
  - Retention table
  - Spend analysis table
3. Preprocessing Data for ML usage
  - Create RFM values
  - Adjust data to kMeans clustering assumptions (skewness and scaling)
4. Perform the Clustering
  - Determine amount of clusters
  - Fit/Transform
5. Insights & Analysis
  - Create and visualize snake chart

## Results
The deliverable for Ecom Co. was a clear time-cohort segmentation of their customers over the past year based on their transaction history. This achieves Ecom's goal to better understand their customers, in addition to finding common purchasing trends across all customers. Depending on Ecom's priorities, this customer segmentation enables them to provide a tailored approach to each segment and attempt to gain value from this more strategic approach.

## Challenges
- Finding complex duplicates
- Normalizing and Scaling features for kMeans modelling

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
