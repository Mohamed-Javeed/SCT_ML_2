# SCT_ML_2
Repository containing the code for task-2 under Machine Learning domain 
## Mall Customer Segmentation using KMeans Clustering
This project involves the segmentation of mall customers using KMeans clustering. The analysis is performed using a dataset of mall customers which includes attributes such as age, gender, annual income, and spending score.<br> The goal is to identify distinct customer segments based on their shopping behavior.

## Project Overview
### Dataset
The dataset used in this project is Mall_Customers.csv downloaded from [here](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data), which contains the following columns:

**CustomerID**: Unique ID assigned to each customer.<br>
**Gender**: Gender of the customer.<br>
**Age**: Age of the customer.<br>
**Annual Income (k$)**: Annual income of the customer in thousand dollars.<br>
**Spending Score (1-100)**: Score assigned to customers based on their behavior and spending nature.<br>
## Process
### Data Loading and Exploration:
The dataset is loaded using pandas, and basic exploration is performed to understand the data structure and key statistics.
### Data Visualization:
Various plots using seaborn and matplotlib are generated to explore relationships between different features:<br>
**Age Distribution**: A KDE plot shows the age distribution of the customers.<br>
**Gender Distribution**: A count plot shows the distribution of customers by gender.<br>
**Spending Score by Age and Gender**: A line plot shows the spending score based on age and gender.<br>
### Clustering with KMeans:
The KMeans algorithm is used to segment the customers into distinct clusters based on their annual income and spending score.<br>
The number of clusters (k) is determined using the Elbow Method, which involves plotting the within-cluster sum of squares against different values of k.
### Results Visualization:
The final clusters are visualized to understand the customer segments formed based on their age, annual income and spending score.
## Dependencies
pandas<br>
matplotlib<br>
seaborn<br>
scikit-learn<br>
numpy<br>
## How to Run
You can either download the .ipynb file and run in jupyter notebook or simply open the .ipynb file in google colab and run all cells to get the results
