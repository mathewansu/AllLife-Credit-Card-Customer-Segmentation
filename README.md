# AllLife-Credit-Card-Customer-Segmentation
Unsupervised learning: To identify different segments in the existing customer based on their spending patterns as well as past interaction with the bank
## Background:
AllLife Bank wants to focus on its credit card customer base in the next financial year. They have been advised by their marketing research team, that the penetration in the market can be improved. Based on this input, the Marketing team proposes to run personalised campaigns to target new customers as well as upsell to existing customers. Another insight from the market research was that the customers perceive the support services of the back poorly. Based on this, the Operations team wants to upgrade the service delivery model, to ensure that customers queries are resolved faster. Head of Marketing and Head of Delivery both decide to reach out to the Data Science team for help

## Objective:
To identify different segments in the existing customer based on their spending patterns as well as past interaction with the bank.

## Key Questions:
How many different segments of customers are there?
How are these segments different from each other?
What are your recommendations to the bank on how to better market to and service these customers?

## Key Insights
- We had Data of various customers of a bank with their credit limit, the total number of credit cards the customer has, and different channels through which customer has contacted the bank for any queries, different channels include visiting the bank, online and through a call centre.
- When we clustered with kmeans and hierarchical clustering, we got similiar clusters
- We have observed 3 clusters of customers. Cluster formd by the customers who have online visits(high credit card numbe) is very much differntiated from other 2 clusters
- The cluster(first) with more number of credit cards made less calls and less bank visits. whereas they have more online visits. Their average credit limit and bank visits are high
- Total calls made by another cluster is very high. But they have less credit limits and less credit cards. One reason could be the issues raised by the customer through call are not resolved properly. Their total visits to bank and Total visits online are comparitively low
- Another customer has more bank visits. They visit online less. Their avg credit limit and total credit cards are low while comparing with customers who make online visits but greater while comparing with customers who make more phone calls
- We should educate about the online servicees of bank to customers(especially who use phone call and online services), so that their issues will be resolved quickly and they get served quickly. that gives more customer satisfaction and encourages customers for taking more credit cards and to use credit card effectively
- We should attend the customers who use phone calls to approach bank for queries in a better manner. Because they are the customers with less credit cards and credit card limit. - We should improvise this cluster. Their problems may not be resolved in phone calls. Maybe because of that their credit card usage is less. Therefore we should improve the service at phone calls. Also we should help them to use online services.
- Even though the customers whop vist bak online has better credit card usage than customers use phone calls; their credit card usage is less compared to online users. Therfore it will be really great, if we can educate them whiele they visit bank. They may not how to use internet. If we give them a demo/leaflet for helping them to use online services, that will encourage customes
