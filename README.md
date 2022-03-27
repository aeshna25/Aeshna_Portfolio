# Aeshna_Portfolio
Data science Portfolio

# [Project 1: Employees Attrition Predictive Modeling :Project overview](https://github.com/aeshna25/Employees-Attrition-Predictive-Modeling-)
- Created a predictive model using **ANN, Logistic Regression and Random forest**
- Aim is to help organization understand the reasons behind employees who are leaving the company
- The dataset has more the 1400+ employees records across 35 different features
- Compared 3 different models to understand which predictive model gives the best accuracy, for this dataset Logistic regression passed with the best performance.

![Kernel Density Estimate](https://github.com/aeshna25/Aeshna_Portfolio/blob/main/images/hrkde.png)
![Boxplot to compare Job Role and Income](https://github.com/aeshna25/Aeshna_Portfolio/blob/main/images/hrboxplot.png)



# [Project 2: Customer Segmentation using KMeans and PCA :Project overview]
- Marketing is essential for brands to attract customers. One of the dwelling pain points of companies is to segment customers in a way so that marketers can lauch campagines targeting to particular segments
- Using machine learning **clustering models like Kmeans and dimensionality reduction processes like PCA, with this project segmented bank customers into 4 types**.
    1. First Customers cluster (Transactors): Those are customers who pay least amount of intrerest charges and careful with their money, Cluster with lowest balance ($104) and cash advance ($303), Percentage of full payment = 23%
    2. Second customers cluster (revolvers) who use credit card as a loan (most lucrative sector): highest balance ($5000) and cash advance (~$5000), low purchase frequency, high cash advance frequency (0.5), high cash advance transactions (16) and low percentage of full payment (3%)
    3. Third customer cluster (VIP/Prime): high credit limit $16K and highest percentage of full payment, target for increase credit limit and increase spending habits
    4. Fourth customer cluster (low tenure): these are customers with low tenure (7 years), low balance 
- EDA helped in observing the trends and certain correlations between customer features.
- Also tested **Auto encoder for dimentionality reductions** and compared the results to that of PCA

![Elbow method to get the best no of clusters](https://github.com/aeshna25/Aeshna_Portfolio/blob/main/images/mrelbow.png)
![PCA for KMEANS clusters](https://github.com/aeshna25/Aeshna_Portfolio/blob/main/images/mrpca.png)

