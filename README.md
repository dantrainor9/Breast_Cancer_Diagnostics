# Breast_Cancer_Diagnostics

## Goal
This project was created with the intent to 1. Understand which tumor features most likely indicate malignancy in breast cancer cases, as well as 2. Generate a machine learning model to predict which tumors are likely to be malignant based on features to improve diagnostic time and save resources for hospitals.

## Data 
This data was retrieved from the Harvard Dataverse from a 2016 study.
Source paper: https://doi.org/10.7910/DVN/SP6VXJ
Data download page: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/SP6VXJ

## Process

### 1. EDA 
Exploratory data analysis took place in the form of data visualizations, summary statistics, and correlation analyses. This analysis was also supported by data visualization in Tableau. 
Tablueau Public link: https://public.tableau.com/views/BreastCancerDiagnosis_17183082111220/NucleiandClumpThicknessindicatingMalignancy?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link

### 2. Clustering
A clustering analysis was performed to identify what groups may exist in the data. 2 clusters were identified as being likely malignant cases. The cluster column was dropped prior to the next step for classification model development, but may be retained in future iterations.


