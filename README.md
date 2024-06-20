# Olist Data Analysis
### 1. Exploratory Data Analysis
* Order
* Sale
* Product category
* Payment
* Rating
### 2. Customer Analysis
* Cohort Analysis
* RFM modelling
* K-Means clustering
### 3. Machine Learning models
* Time to delivery estimation
* Freight value estimation
### 4. Recommendation systems
* New customers
* Repeat customers

---
## Approach

- Starting with EDA to learn about Trend of Orders, Sales, Products and Customers to get general insights. 
- I then segmented customers into specific clusters based on Cohort Analysis, RFM Modeling (and also K-Means clustering) using their purchasing behavior.
- Descriptive analysis results were summarized in a [Marketing dashboard](https://lookerstudio.google.com/reporting/b864d7af-63a1-4050-9036-42897371510d).
- Doing some predictive analysis via applying Machine Learning to improve delivery time estimation and predict freight value of each order.
- Personalized Recommendations

## Customer Segmentation and RFM Modeling 

Using RFM anaylsis and K-means Clustering, we created the below Clusters or segments of customers to further give targetted recommendation to them. 

* We can Upsell high end products to Big Spenders and Cross Sell complimentary products to Loyal and Best Customer (VVIP).

* Potential Loyalists: They are highly potential to enter our loyal customer segments, discounts for future purchases are very suitable for this audience.

* Lagging Customers: They are showing promising signs with quantity and value of their purchase but it has been a while since their last purchases. Let’s target them with their wishlist items, a limited time offer discount and/or a free delivery.

* Hibernating Almost Lost: They made some initial purchase but have not seen them since. Let’s spend some resource to build our brand awareness with them.

* Churned Customers: Poorest performers of our RFM model. They might have went with our competitors for now and will require a different activation strategy to win them back. We can see many things to improve our business through surveying this customer group.

![customer segments](https://github.com/manhitv/olist-data-analysis/blob/master/notebooks/images/customer_segments.PNG)

## Personalized Recommendations
* For new customers: products will be recommended based on Popularity by Month (and/or by Location) or based on Highly Rated Categories
* For repeat customers: we will investigate multiple approaches to create an effective recommender system. These approaches will be evaluated by `top-K-accuracy` score.