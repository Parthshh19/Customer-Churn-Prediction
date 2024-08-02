# Customer Churn Prediction Project Overview

**Introduction**
Myer, a leading Australian department store chain, operates 56 stores nationwide and offers a wide array of products. With a two-level loyalty scheme (silver and gold memberships), Myer collects substantial customer data to personalize offers and retain customers. This case study focuses on predicting customer churn using logistic regression, complemented by RFM (Recency, Frequency, and Monetary) analysis, to assess and enhance customer retention strategies.

**Literature Review**
Logistic regression, a preferred method for predicting binary outcomes, evaluates the influence of various features on customer churn. It is chosen for its interpretability and reliable performance in classification tasks. The RFM model, a behavior-oriented approach, segments customers based on recent purchase behavior, frequency, and monetary value, offering valuable insights for retention efforts.

**Methodology**
A dataset of 30,000 Myer customers was split into training (21,000) and test (9,000) sets. The logistic regression model was trained on the training set and evaluated on the test set, incorporating all available features to predict customer churn. RFM analysis scored customers on recency, frequency, and monetary value, segmenting them into five categories. A lift chart compared the performance of logistic regression, RFM, and random models in identifying churners.

**Results**
**Logistic Regression Model:**
- Loyalty (-0.5301), total profit (0.0734), purchase frequency (-0.0444), spending on cosmetics and fragrance (-0.0259), and recency of purchases (-0.1113) were key predictors.
- Performance metrics: Accuracy (80.12%), sensitivity (74.49%), and specificity (84.43%).

**RFM Model:**
- Top 10% of customers contributed significantly to total spending.
- RFM segments provided insights into customer behavior and loyalty.

**Lift Analysis:**
- Logistic regression and RFM models concentrated churners effectively in top deciles.
- Both models outperformed the random model in identifying churners.

**Conclusion and Recommendations**
Both logistic regression and RFM models effectively predict customer churn, with logistic regression offering slightly better performance. Key predictors identified include loyalty level, total profit, purchase frequency, spending on cosmetics and fragrance, and recency of purchases.

Recommendations for Myer include:
1. **Targeted Marketing Campaigns:** Focus on high-risk customers identified by the logistic regression model.
2. **Loyalty Program Enhancement:** Invest in enhancing benefits for loyalty members, especially gold members.
3. **Retention Messaging:** Develop personalized retention campaigns for at-risk customers.
4. **Customer Segmentation:** Use RFM analysis to tailor retention strategies for high-value segments.
5. **Monitoring Churn Risk:** Implement real-time monitoring to identify and retain potential churners early.
6. **Feedback Mechanisms:** Gather feedback from churned customers to address underlying issues.
7. **Data Analytics and AI:** Explore advanced analytics to refine churn prediction and customer insights.

These strategies aim to enhance Myer's customer retention efforts and maintain long-term customer loyalty.
