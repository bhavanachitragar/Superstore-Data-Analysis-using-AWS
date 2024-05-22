# Superstore Data Analysis using AWS
-------------------------------------------------------------

This project builds a pipeline to analyze Superstore sales data using the power of AWS. It transforms the data to make it ready for exploration. Querying the transformed data using SQL queries to uncover trends and patterns. Analyzing results and creates easy-to-understand visualizations, providing clear insights into Superstore sales performance.

#### AWS services used:

1- IAM 
2- S3
3- AWS Glue
4- AWS Athena
5- AWS Quicksight



### 1. IAM (Identity and Access Management): 
Creating an IAM user which defines permissions for users and applications to access and manage data in other services like S3, Glue, Athena, and QuickSight.

### 2. S3 (Simple Storage Service): 
S3 Bucket serves as the data storage repository where raw data is uploaded before processing. 
Created different folders which helps Crawler for Partition.

### 3. AWS Glue: 
Glue helps in extract, transform, and load (ETL) data. 
Running a Crawler to create a Data Catalog.

### 4. AWS Athena: 
Athena enables querying the transformed data stored in S3 by Glue.
It helped in running SQL queries.

### 5. Amazon QuickSight: 
QuickSight helps in creating visualizations and dashboards from data sources.
It used the results from Athena’s analysis of the data for  data visualization.

#### Sanpshots:
 
----------------------------------------------------------------

Kaggle dataset: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
