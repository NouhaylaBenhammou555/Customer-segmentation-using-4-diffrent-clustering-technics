# Customer-segmentation-using-4-diffrent-clustering-technics
Clustering is the task of dividing the population or data points into a number of groups such that data points in the same groups are more similar to other data points in the same group than those in other groups. In simple words, the aim is to segregate groups with similar traits and assign them into clusters. In this project, the objective is to perform segmentation using clustering techniques for a given dataset of customers visiting a mall. 
Four different techniques will be applied and compared - KMeans, DBSCAN, MeanShift, and Agglomerative. 


• Clustering belongs to unsupervised machine learning techniques. 

• The main task of clustering is to discover "natural" groups in an unlabelled dataset. This is an
important task in data analysis as it is used in many scientific, engineering and business applications. The most well-known application of clustering are customers segmentation (for efficient marketing), image segmentation, documents clusterisation. There are many clustering algorithms which can be divided into two main types: hierarchical and partitional.

• Hierarchical algorithms recursively split a dataset into a smaller subset until a subset contains only one item. This can be represented with a dendrogram which looks like a tree. It can be constructed from leaves to the root (agglomerative approach) or from the root down to the leaves (divisive approach). In hierarchical clustering, you don't have to specify the number of clusters but you have to define a termination condition for splitting/merging process.

• Partitional algorithms divide a dataset into several subsets (clusters) based on a given criteria. For some algorithms number of clusters has to be defined a priori(e.g K-Means) and for some not (DBSCAN). Defining the number of clusters before running an algorithm often requires a specific domain knowledge which is often challenging (or even impossible) in many applications. This led to the development of many heuristics and simplified approaches helping analyst without domain knowledge to choose the appropriate number of clusters.


<img width="743" alt="Capture d’écran 2022-07-22 162126" src="https://user-images.githubusercontent.com/77208565/180471430-02ea2986-e3eb-475f-90dd-725e4bec76b1.png">
