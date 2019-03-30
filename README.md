<h2<b>>Panel_Data_Analysis-Durable-Goods</b></h2>

<h4><b>Objective</b></h4>
This project analyzes past transactions data for a durable goods company and identifies key customer segments using RFM analysis and clustering. It also identifies key predictors influencing customer return behavior using key classification methods.

<h4><b>Data Overview</b></h4>
<ul>
<li>This is a panel data set containing the transactions of 19,936 households made over the period from December 1998 to November 2004 at a major U.S. consumer electronics retailer.</li>
<li>There are a total of 173,262 transactions, including purchases and returns of products as well as extended warranties.</li>
<li>There are 16 product categories and 292 subcategories, ranging from big-ticket items such as televisions to small-ticket items such as CDs and batteries.</li>

<h4><b>Methodology</b></h4>
<ul>
<li>Data Cleaning</li>
<li>RFM Analysis</li>
<li>Clustering</li>
<li>Identification of key Clusters</li>
<li>Classification - Logistic Regression & Random Forest Classifier</li>
<li>Identification of key return predictors</li>
</ul>

<h4><b>Analysis</b></h4>
<u>Customer Segmentation</u>
After analyzing the clustering results, we were able to identify three major customer segments:
<ul>
<li>In cluster 3, customers have bought recently, purchased frequently and also have highest monetary value. These are the loyal high value customers.</li>
<li>In cluster 0, customers havent shopped since a long time, but made frequent high value purchases in the past. These are Infrequent High Value.</li>
<li>In cluster 4, customers havent shopped since a long time, but made high value purchases in the past. These are Churned high value customers.</li>
</ul><br>
<u>Returns can be predicted based on 'Importance Scores' calculated for the Random Forest Classifier:</u><br>
Key Variables of high importance (in order):
<ul>
<li>Unit Price</li>
<li>Gender</li>
<li>Age</li>
<li>Income</li>
<li>Number of Children</li>
</ul>
Product Categories of high importance:
<ul>
<li>P*S*T (Scooter)</li>
<li>Television</li>
<li>Music</li>
</ul>

<h4><b>Limitations</b></h4>
<ul>
<li>Limited covariates to predict returns. For example: Details about return policy, product ratings etc.</li>
<li>Dataset does not contain information on non-price-related promotions(TV advertising, catalogs, store displays, etc.)</li>
<li>Data is from a single retailer. Without information on consumer purchases from other retail outlets, studies on some consumers decisions such as product adoption, upgrade, and replacement could be subject to bias.</li>
<li>Dataset includes maximum transactions for purchases hence, any analysis on data is skewed towards purchases.</li>
</ul>
