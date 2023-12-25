# Olist Data Analysis: 
### 1. Exploratory Data Analysis
### 2. Customer Analysis (cohort analysis / RFM model / KMeans clustering)
### 3. Machine Learning models (time to delivery estimation, freight value estimation, rating prediction, TBU)
### 4. Recommendation systems (TBU)

---
## Approach

1. We started with EDA and Trend Analysis of Products and Customers to get insights for a business Analyst. 
2. Then we Segmented customers into specific clusters based on Cohort Analysis, RFM Modeling using their purchasing behavior. Measure MOCP/MICP (Marketing Influenced Customer Percentage)
4. Predict Customer Lifetime value (LTV)
5. Personalized Recommendations using Implicit feedback in the form of customer’s past purchases and Explicit feedback in the form of their Product Reviews. We have used Alternative Least Squares(ALS) and Doc2Vec for creating 2 different control groups to which Recommendations will be provided. A new user will see the popular recommendations, and using Segmentation, we will identify who are Big Spenders and will Upsell them using Highest rated product recommendations. 
6. We have created 3 different personas for front end and presented the outcomes as a Marketing dashboard as well as a fully deployed Webapp.

## Personas 
1. Higher Management Executives - Marketing Dashboard
• To get insights on a high level cohorts and Metrics for Revenue by Products, day of week and month. 
• To look at overall Customer Segments to see the health of marketing.  
Image

2. Marketing Data Scientist & Automated System:
• To form promotion strategies based on Marketing Insights and Uplift
• Recommend products to customers based on their liking along with any Upselling and Cross Selling opportunities
• Optimize the Marketing Funnel to boost Revenue, offer Targeted Recommendations
Image

3. End Users or Potential Customers:
• Explore products recommended by the system
• Receive promotions based on their loyalty, demography
• Explore Products which are similar to what they are about to buy or have purchased previously
Image

## Customer Segmentation and RFM Modeling 

Using RFM anaylsis and K-means Clustering, we created the below Clusters or segments of customers to further give targetted recommendation to them. 

1. Potential Loyalists —
High potential to enter our loyal customer segments, why not throw in some freebies on their next purchase to show that you value them!

2. Needs Attention —
Showing promising signs with quantity and value of their purchase but it has been a while since they last bought sometime from you. Let's target them with their wishlist items and a limited time offer discount.

3. Hibernating Almost Lost —
Made some initial purchases but have not seen them since. Was it a bad customer experience? Or product-market fit? Let's spend some resources building our brand awareness with them.

4. Lost Customers —
Poorest performers of our RFM model. They might have gone with our competitors for now and will require a different activation strategy to

Image

## Recommendation Systems (TBU)
