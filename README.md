# Identify Customer Segments
## Description
In this project, we will apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that we will use has been provided Udacity's partner at Bertelsmann Arvato Analytics, and represents a real-life data science task.

## Software and Libraries
This project uses the following software and Python libraries:

- Python 
- NumPy
- pandas
- scikit-learn 
- Matplotlib
- Sklearn.preprocessing
- PCA
- KMeans

## Summary of results and process:
- Applied Data Preprocessing Techniques on a dataset with 891220 observations in order to identify and solve problems related to missing values, outliers, categorical data, and feature scaling.
- Created a data-pipeline to apply the above mentioned pre-processing operations to the general and customer demographics datasets.
- Principal component analysis has been applied to the data to create transformed features. A variability analysis has been performed to justify a decision on the number of features to retain.
- Using KMeans, multiple cluster counts have been tested on the general demographics data, and the average point-centroid distances have been reported.
- The elbow method is used to decide the number of clusters to be used.
- After the clustering process with K = 20 (20 clusters are choosen), a comparison is made between the general population dataset and customers dataset to identify segments of the population that are central to the sales company's base as well as those that are not, resulting in the identification of five new potential customers segments with a high expected rate of return.


