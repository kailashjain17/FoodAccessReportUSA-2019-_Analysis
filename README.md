# FoodAccessReportUSA-2019-_Analysis
Unsupervised Learning on Food Access Report USA(2019)

Data Model: A data about food access research per census tract of each state’s county in USA for the year 2019. It contains information like demographic details, socio economic condition, food access in terms of distance from a supermarket, vehicle access, government program benefits, and more. I have even added latitude and longitude of each state to find spatial patterns within the dataset. 

link to the dataset: https://catalog.data.gov/dataset/food-access-research-atlas

Role: Sociologist/ Urban Planner/ Policy Maker

Why Clustering? What benefits does it have?
It helps for grouping of similar groups which can help policy makers understand a group’s need and plan customized policies for those groups.

What would it look like? What do you expect to find?
I expect the cluster to group the census tract based on the features like Poverty rate in terms of socioeconomic status, Races share in terms of understanding the diversity of a particular region, SNAP share access to understand the assistance provided by the government and more.

Possible Anomaly:
In terms of multivariate outliers there are lots of columns which have a wide range of values. For example, considering ‘MedianFamilyIncome’, ‘PovertyRates’, ‘TractSNAP’, and ‘Pop10’, all these columns differ from different census tract. If I consider them in clustering its very natural for me to find anomalies in the results as all these 4 rows tend to be different and vary across the census tract.

Can we apply collaborative filtering in this dataset?
It's not possible to perform collaborative filtering in this dataset because we are not looking to make a recommendation system. This data is about food access research in the USA in 2019 which contains socioeconomic, demographic and food access related data which is nowhere related to a recommendation. In recommendation systems, we have users data based on which we suggest other similar user things. Hence, performing collaborative filtering doesn't make sense in this dataset.
