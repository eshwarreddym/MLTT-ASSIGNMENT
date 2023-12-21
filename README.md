# MLTT-ASSIGNMENT
**Housing Dataset Analysis**

This repository comprises an analysis of the housing dataset utilizing scikit-learn. The primary objective involves replacing GridSearchCV with RandomizedSearchCV within a unified pipeline for both data preparation and the final prediction. Additionally, a transformer has been introduced to select the most crucial attributes.

**Dataset Description**

The housing dataset encompasses features related to Boston housing, aiming to predict the median value of owner-occupied homes. Various attributes, such as crime rate and pupil-teacher ratio, are included.

**Task Overview**

1. **Replacing GridSearchCV with RandomizedSearchCV:**
   - Implementation of RandomizedSearchCV in a single pipeline for data preparation and prediction.
   - Loading and preprocessing the housing dataset.
   - Constructing a pipeline for data preparation and model prediction.
   - Using RandomizedSearchCV for efficient hyperparameter tuning.

2. **Feature Selection Transformer:**
   - Integration of a transformer into the pipeline to select the most important attributes.
   - Enhancing model performance and reducing computational overhead.

**Conclusion**

The incorporation of RandomizedSearchCV in the pipeline, coupled with the feature selection transformer, enhances the efficiency of model tuning and data preparation for predicting housing prices.

**References:**
- Scikit-learn Documentation
- Housing Dataset Source

---

**Customer Churn Cluster Analysis**

**Overview**

Customer churn, denoting the percentage of customers discontinuing a company's product or service within a specified timeframe, is the focus of this analysis. The objective is to understand and mitigate customer churn for improved business retention.

**Importance of Customer Churn**

Managing churn is critical, given that acquiring new customers is more costly than retaining existing ones. By reducing churn, a company can enhance revenue and stability.

**Methodology**

**Data Collection:**
Describe the source of the customer churn dataset, including details on the dataset's attributes and features.

**Data Exploration:**
Explore the dataset to understand its structure, missing values, and statistical summaries. Identify key variables influencing churn, such as tenure, subscribed services, and customer satisfaction.

**Data Preprocessing:**
Handle missing values, encode categorical variables, and scale features if necessary. Split the dataset into training and testing sets.

**Cluster Analysis:**
Utilize clustering algorithms (e.g., K-means, hierarchical clustering) to segment customers based on behavior. Determine the optimal number of clusters using methods like the elbow method or silhouette score.

**Profiling Clusters:**
Describe each cluster's characteristics and behaviors, identifying patterns or traits differentiating one cluster from another.

**Churn Prediction:**
Train a predictive model to forecast customer churn using classification algorithms (e.g., logistic regression, random forest). Evaluate the model's performance using metrics like accuracy.

**Insights and Recommendations:**
Summarize findings and insights from the analysis. Provide actionable recommendations to reduce churn based on cluster profiles and predictive model results.

**How to Reduce Churn:**
Discuss strategies to mitigate customer churn based on the analysis. Highlight actionable steps and potential areas for improvement.

**Conclusion:**
Sum up key takeaways and emphasize the significance of addressing customer churn. Stress the importance of continuous monitoring and adaptation to retain customers effectively.
#### Submitted by Eshwar Reddy M (USN - ENG21DS0053)
