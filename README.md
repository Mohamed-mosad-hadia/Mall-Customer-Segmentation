



# Mall Customer Segmentation

This project applies machine learning techniques for customer segmentation using clustering algorithms. The goal is to group mall customers into distinct segments based on their purchasing behavior and demographic data, which can help businesses tailor their marketing strategies to different customer profiles.

<br>
<div align="center">
    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</div>
<br>

# Project Overview
Customer segmentation is a crucial task for understanding consumer behavior and providing personalized services. In this project, we use a dataset of mall customers, implementing PCA for dimensionality reduction and clustering techniques to identify different customer segments. We also calculate the silhouette score to evaluate the quality of the clusters.



<br>
<div align="center">
    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</div>
<br>

 **Technologies Used**


  **Python**:  Programming language for analysis and visualization.
  
  **scikit-learn**:  Machine learning library for clustering, PCA, and silhouette score.
  
  **pandas**:  Data manipulation and analysis library.
  
  **matplotlib & seaborn:** Libraries for data visualization.


<br>
<div align="center">
    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</div>
<br>


 **Dataset**
- Customer ID: Unique identifier for each customer.
- Gender: Male or Female.
- Age: Age of the customer.
- Annual Income: The yearly income of the customer in $.
- Spending Score: A score assigned to customers based on their spending behavior.



<br>
<div align="center">
    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</div>
<br>


**Analysis and Methods**
  
1. Data Preprocessing: We perform data cleaning and normalization on the dataset.

2. PCA (Principal Component Analysis): Dimensionality reduction is used to visualize data in a lower-dimensional space.

3. Clustering: We use unsupervised learning algorithms, such as K-Means, to group customers into distinct clusters.

4. Silhouette Score: We calculate the silhouette score to measure the separation between clusters.



<br>
<div align="center">
    <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" />
</div>
<br>


**Results**

The customer segmentation model achieves a 
> [!NOTE] 
> silhouette score of 0.416

indicating that the clustering algorithm performs reasonably well at grouping similar customers while maintaining separation between distinct groups.




![image](https://github.com/user-attachments/assets/d4c80e7d-8c56-49b4-817f-0d51820aaedc)
