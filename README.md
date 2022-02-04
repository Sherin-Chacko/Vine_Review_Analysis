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

<img width="722" alt="Screen Shot 2022-02-03 at 11 11 51 PM" src="https://user-images.githubusercontent.com/91294352/152470534-36426493-4962-42a4-9973-f2dade05949e.png">

**b) Total number of 5-star reviews:**

#### > Vine reviews:

<img width="723" alt="Screen Shot 2022-02-03 at 11 15 00 PM" src="https://user-images.githubusercontent.com/91294352/152470779-36cccee0-3d5d-4e39-9224-9b3ffac6ce2c.png">

#### > Non-Vine reviews:

<img width="678" alt="Screen Shot 2022-02-03 at 11 16 16 PM" src="https://user-images.githubusercontent.com/91294352/152470900-f7d45221-6b66-473d-b879-de196ce0013f.png">

**b) Percentage of 5-star reviews:**

#### > Vine reviews:

<img width="686" alt="Screen Shot 2022-02-03 at 11 21 34 PM" src="https://user-images.githubusercontent.com/91294352/152471330-fce45349-553d-4de9-94d8-8333b4735249.png">

#### > Non-Vine reviews:

<img width="697" alt="Screen Shot 2022-02-03 at 11 21 53 PM" src="https://user-images.githubusercontent.com/91294352/152471389-75c72e57-a0d4-419d-aeea-7c18e2809212.png">

### 3) Summary:

a) 51% of the reviews in the Vine program were 5 stars reviews while the percentage in the non-Vine reviews is only 39%. This indicates that there is a positive bias for reviews in the Vine program.

b) Finally we can also calculate the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
