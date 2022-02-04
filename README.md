## Vine_Review_Analysis
PySpark

### 1) Analysis Overview: 
This project analyzes Amazon Vine program and determines if there is a bias towards favorable reviews from Vine members. Our analysis is based on the US reviews for video games.

The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

### 2) Resources:

**Data Source**: Amazon Review datasets, Video Games Review dataset

**Software**: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

### 3) Results:

**a) Total number of reviews:**

#### > Vine reviews:

<img width="707" alt="Screen Shot 2022-02-03 at 11 07 39 PM" src="https://user-images.githubusercontent.com/91294352/152470232-42fa99f3-50ce-408f-b919-d657ceebd570.png">

#### > Non-Vine reviews:

