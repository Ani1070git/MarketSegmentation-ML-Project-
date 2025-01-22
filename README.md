# Market Segmentation In Insurance

### Objective  :
This case requires to develop a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.
<img align="center" src="https://github.com/user-attachments/assets/14e3d303-8915-45a6-bdc7-e1e1ad407eaa" alt="image">
### Data Description : 
The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.
### Data :  
Use the below link to download the Data Set: [here](https://github.com/pik1989/MarketSegmentation/blob/main/Clustered_Customer_Data.csv) 
### Algorithms used :  
In this dataset i've used five clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [Spectral Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)
- [GaussianMixture Model based clustering](https://en.wikipedia.org/wiki/Mixture_model)
### Final Model  :
I have created a Streamlit Application based on this clustering technique, where we are taking the customer details & identifying which cluster the custoemr belongs to.
