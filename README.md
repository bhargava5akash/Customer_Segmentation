# Customer_Segmentation
This project implements Machine Learning-based Customer Segmentation using the K-Means clustering algorithm. It helps businesses group customers based on their purchasing behavior, income, age, and spending score to improve targeted marketing strategies.

Google Colab Notebook
View and run the complete project here: Open in Google Colab

Objectives
Perform Exploratory Data Analysis (EDA)
Understand customer behavior and spending patterns
Apply K-Means clustering for segmentation
Visualize different customer groups
Help in targeted marketing strategies

Dataset Description
Typical dataset contains:
Feature
Description
CustomerID
Unique ID for each customer
Gender
Male/Female
Age
Customer age
Annual Income
Annual income (in $)
Spending Score
Customer spending score (1-100)

Goal: Group customers based on Age, Income, and Spending Score.

Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-Learn (KMeans)
Jupyter/Colab

Data Preprocessing
Handling missing values
Feature selection: Age, Income, Spending Score
Scaling data using StandardScaler

Model Training: K-Means Clustering
Used Elbow Method to determine optimal clusters
Trained K-Means model on selected features

Visualization
Used graphical visualizations:
Scatter plot of customer clusters
Distribution plots
Heatmap of correlations

Insights from Clusters
Cluster
Description
0
High income, low spending — Careful Spenders
1
Low income, high spending — Impulsive Buyers
2
High income, high spending — Potential Loyal Customers
3
Low income, low spending — Budget Customers


Conclusion
Customer segmentation helps businesses tailor products, marketing strategies, and improve customer satisfaction. K-Means is an effective tool for identifying distinct groups.
