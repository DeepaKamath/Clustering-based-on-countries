Problem Satement:

HELP International is an international humanitarian NGO that is committed tofighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities.
After the recent funding programs, they have been able to raise around $10million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid.

So need to categorize the countries using some socioeconomic and health factors that determine the overall development of thecountry. Then need to suggest the countries which the CEO needs to focus on the most.

Approach used in analysis:

1. Reading, understanding and cleaning the data
2. Visualizing the data by performing EDA
3. Outlier Treatment
4. Hopkins test to see if the data is good for clustering
5. Preparing the data for modelling by Scaling
6. Clustering with K Means Clustering technique
7. Performed Hierarchical Clustering
8. Cluster Profiling
9. Conclusion

Outlier treatment is performed by keeping boundaries for quantiles as 1 & 99 th Percentile and not in a extreme way as it could remove many countries and that is not right for the analysis. Outliers from Gdpp and income gets removed. IQR method is used here for the same.

Hopkins Test gave the score of above 95% which ensures that data is good for clustering.

Elbow Curve and Silhouette Score gives an idea of number of clusters required for the analysis in K Means Clustering.

Hierarchical Clustering is performed using Single and Complete Linkage.

For the cluster Profiling 3 variables Gdpp , Child Mortality, Income are analysed to determine how much they vary for each cluster of countries to recognize and differentiate the clusters of developed countries from the clusters of under developed countries

Plotting boxplots to visualize the same.

Cluster with low gdpp , high child mortality, low income will consist of the countries that are in dire need of financial help. It is found that cluster 2 is that cluster.

Cluster with Id 2 is sorted based on low gdpp , high child mortality rates,low income and 5 deserving countries are chosen.

As per my analysis, countries which are in dire need of finance are as follows:

1. Burundi

2. Liberia

3. Congo

4. Niger

5. Sierra Leone
