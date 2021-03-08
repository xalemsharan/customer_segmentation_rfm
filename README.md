# Customer Segmentation Using RFM Analysis

Today, we have a UK based Online Retailer, who is facing decline in sales and customer engagement. While their UI/UX team is working on revamping the website to enhance the user experience, the marketing team had approached us, data scientists (the unicorns who can make 2 + 2 = 8 possible, JK!), to help them manage their promotions and tailor them as close as possible to the customer behavior.

Well, this is a problem which can be solved using RFM analysis for segmenting the customers. Let's understand more about RFM analysis.

RFM stands for Recency, Frequency, and Monetary value, each corresponding to some key customer trait. These RFM metrics are important indicators of a customer’s behavior because frequency and monetary value affects a customer’s lifetime value, and recency affects retention, a measure of engagement. RFM factors illustrate these facts:
* the more recent the purchase, the more responsive the customer is to promotions
* the more frequently the customer buys, the more engaged and satisfied they are
* monetary value differentiates heavy spenders from low-value purchasers

Well, instead of taking the classic approach of segmenting customers based on quantiles, today we will take a new route of identifying the number of segments using unsupervised learning techniques (clustering). Once we have identified the number of segments and reviewed the characteristics of these segements based on RFM values, we can define them and hence devise marketing campaigns around them accordingly.
