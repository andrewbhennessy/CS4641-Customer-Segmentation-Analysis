## CS4641 Customer Data Segmentation Analysis Project

### MID-PROJECT REPORT
Please See in our Colab Here: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andrewbhennessy/CS4641-Customer-Segmentation-Analysis/blob/main/Mid_Project_Report.ipynb)

The Timestamped document available in our main branch is here: [![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://github.com/andrewbhennessy/CS4641-Customer-Segmentation-Analysis/blob/main/Mid_Project_Report.ipynb)


### Introduction:

The COVID-19 pandemic has greatly affected the way all companies advertise for their businesses. Now more than ever, online presence and advertising are necessary to attract customers. While each customer is unique, a similar group of customers can be targeted in an advertisement. This is almost always more successful than making a generic advertisement aimed at the entire population. Advertisements aimed at certain subsets can save money and increase company traffic.

### Problem Definition:

Our project will use customer spending datasets to group customers together, allowing advertising to become specialized to each group. With this, companies can target these groups and make advertisements specifically aimed at each of them. This will improve the success rate of advertisements and bring in more revenue from customers(Modukuru n.pag).


### Methods:

We will be using DBScan to specify our groups. DBScan is defined as density based spatial clustering of applications with noise. Points with lower density will be treated as noise or outliers. Core points will represent the customers that a targeted advertisement is most likely to attract, border points will represent customers who may have some interest in a targeted advertisement aimed at their group, and outliers will have minimal to no interest in any targeted advertisement. Because DBScan is very sensitive to parameters, we will need to perform extensive testing to find the most optimal combination of epsilon value and number of minimum points(Hossain n.pag.)


### Potential Results:

Classify customer population into some number of specific groups (clusters). Companies can then create advertisements aiming towards attracting the different categories of customers. 


### Discussion

DBScan is a performative method that can categorize customers based on their spending habits and interests. However, the method is very sensitive to the two parameters: epsilon and minimum number of points. Different values for parameters will partition customers into different clusters, and choosing impractical parameter values lead to severe impact on customers’ experiences. Therefore, deciding the ideal values for each parameter using different analysis such as the elbow effect will be crucial. Another possible difficulty is partitioning a dataset with similar densities. If the dataset contains many groups of customers with a similar size of density, DBScan may struggle separating them. Despite these challenges, DBScan is still a phenomenal method for categorizing customers over other clustering methods such as K-means. Density based clustering is capable of handling outliers and does not require to input the number of clusters. Finding the ideal number of clusters will be extremely hard since there may be tons of people who do not share similar spending patterns and interests in the given dataset. In addition, DBScan is competent in connecting nearby clusters using density reachability and connectivity nature so each customer will not be fully restricted to its own group. Applying this method to partition customers will provide a tremendous benefit to a company and the customers will be able to not only enjoy within their interests but also explore further by being introduced with new topics that other customers with similar interests like(Sekhar & Prasanna n.pag).

### Project Proposal Video

[Project Proposal Video](https://youtu.be/k_Ku24VRbnc)

### References

1. Hossain, Shahadat. “Customer Segmentation Using Centroid Based and Density Based Clustering Algorithms.” Customer Segmentation Using Centroid Based and Density Based Clustering Algorithms - IEEE Conference Publication, 1 Feb. 2018, [ieeexplore.ieee.org/document/8275249.](ieeexplore.ieee.org/document/8275249.)

2. Modukuru, Pranay. “Customer Segmentation and Acquisition Using Machine Learning.” Medium, Towards Data Science, 19 Apr. 2020, [towardsdatascience.com/customer-segmentation-and-acquisition-using-machine-learning-a219ce0ec139.](towardsdatascience.com/customer-segmentation-and-acquisition-using-machine-learning-a219ce0ec139.) 

3. Sekhar, Babu B, and Prasanna P Lakshmi. “Customer Data Clustering Using Density Based Algorithm.” Research Gate, International Journal of Engineering &amp; Technology, May 2018, [www.researchgate.net/publication/325881992_Customer_Data_Clustering_using_Density_based_algorithm.](www.researchgate.net/publication/325881992_Customer_Data_Clustering_using_Density_based_algorithm.)
