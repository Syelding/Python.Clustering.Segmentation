# Python.Clustering.Segmentation

## Customer Segmentation
What is Cluster Customer Segmentation? It is the use of a mathematical model to discover groups of similar customers based on finding the smallest variations among customers within each group. Hence it assists in better customer modeling and predictive analytics, and are also are used to target customers with offers and incentives personalized to their wants, needs and preference. The KMeans algorithm accuraretly predicts the number of clusters in a dataset.

Problem : Understand the target customers for the market team,
Context of the Problem: Your boss wants you to find the important shopping groups based on income, age, and the mall shopping store
## Objective Market Segmentation
Divide mall target into approachable groups. Create a subset of market based on demographics

1. Import Libraries and KMeans Clustering Algorithm
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
import warnings
warnings.filterwarnings('ignore')
2. Import Dataset
3. Perform Univarriate Analysis by analyzig the Annual Income of customers
4. Perform Bivariate Analysis by analyizing annual income and spending score
5. Perform Multivariate Analysis
6. Create a Varaible for your KMeans algorithm Initiate, fit data into algorithm, create predictions.

##Solutions and Insights
Target Group of Marketing campaign would be cluster 1 ( high income and high spending score)
54% shoppers of cluster one are women
Cluster 2 shows promise for marketing events based on sales for popular items (low income but high spending). 
Hence, you can create a marketing campagin for the low income shoppers around Holiday seasons.


