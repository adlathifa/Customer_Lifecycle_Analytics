# Mall Customer Segmentation Using KMeans

## **Project Overview**
This project applies K-Means clustering to segment mall customers based on age, income, and spending behavior. The analysis reveals four distinct customer groups, each with unique traits and preferences. These insights support personalized marketing strategies, helping businesses better target high-value customers, understand spending habits, and optimize engagement across different customer segments.

## Dataset
This <a href="https://github.com/adlathifa/Customer_Lifecycle_Analytics/blob/main/Customer%20Segmentation%20K-Means/Mall_Customers.csv">Dataset</a> includes the following columns:
- `Customer_ID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual_Income (k$)`: Annual income of customer in thousands dollar
- `Spending_Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Project Workflow

This project follows the steps below:
1. Importing Libraries: loading all necessary libraries for data manipulation, visualization, and clustering.
2. Data Preparation: loading the dataset and handling missing or inconsistent values to ensure data quality.
3. Data Exploration: analyzing the dataset to understand variable distributions, relationships, and potential outliers.
4. Feature Engineering: creating or transforming relevant features to improve clustering performance.
5. Modeling Clusters with K-Means: applying the K-Means algorithm to segment customers into distinct groups based on selected features.
6. Cluster Identification: interpreting and labeling each cluster based on its characteristics to derive meaningful insights.

## General Observations

* Cluster 0 (Confident Spenders) and Cluster 1 (Moderate Spenders) make up the majority, contributing around 67.5% of the customer base.
* t-SNE visualization confirms clear segmentation, especially for Cluster 2 (Wealthy Minimalists) and Cluster 3 (Young Actives), which are distinctly separate in behavior and preference.
* This differentiation supports targeted marketing strategies and personalized experiences for each segment.

## Insights & Marketing Strategies by Cluster
### Cluster 0 (Confident Spenders)
Profile: Mid to older age (mostly 31–40), varied income, mostly female, high spenders. <br>
Insight: This group contributes significantly to overall revenue, showing high purchasing frequency and value. <br>
Strategy:
  * Launch exclusive loyalty programs or VIP memberships.
  * Provide early access to new products and special offers.
  * Utilize personalized marketing with premium or lifestyle-based campaigns.
  * Highlight status or value-driven messaging to appeal to their confident spending style.

### Cluster 1 (Moderate Spenders)
Profile: Older age (mostly 41+), lower-mid income, mostly female, moderate spenders. <br>
Insight: A stable and loyal customer base with consistent spending patterns over time. <br>
Strategy:
  * Emphasize value-for-money products and practical utility.
  * Offer senior-friendly services like simplified purchasing, loyalty points, or informative newsletters.
  * Encourage referrals or community-based engagement (e.g., group offers, offline events).

### Cluster 2  (Wealthy Minimalists)
Profile: Older (mostly 41+), high income, balanced gender, low spenders. <br>
Insight: Despite their wealth, this segment is selective and spends less, likely valuing quality over quantity. <br>
Strategy:
  * Focus on premium, minimalist, or sustainable products.
  * Leverage brand storytelling to create emotional appeal or status alignment.
  * Use subtle, non-intrusive marketing — e.g., invite-only previews, premium catalogs, or concierge-style services.

### Cluster 3 (Young Actives)
Profile: Younger to mid age (18–30), lower-mid income, mostly female, moderate to high spenders. <br>
Insight: Highly engaged, trend-conscious group with growing potential. <br>
Strategy:
  * Use social media campaigns, influencer collaborations, and gamified promotions.
  * Offer flexible payment options or bundles to suit their budget.
  * Highlight trendy, functional, or eco-conscious products.
