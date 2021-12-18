# data_mining_on_divarDataset

## Introduction
This project tries to clean data and check dataset having acceptable values and then shows implementation of some algorithm in frequent pattern, clustering and classification on Divar dataset.

### Implement data cleaning:
This stage of the project was checked all columns and rows to have acceptable values. If it has Null or unacceptable values, it was filled by "unknown" or "mean of data in column".

also Completeness was checked in 3 way:

Measurement Function A/B 


##### 1.	
A: records with no missing attribute

B: Total records in a dataset

##### 2.	
A: number of data required for the particular context in the data file

B: number of data in the specified particular context of intended use

##### 3.	
A: attribute fields containing values 

B: records × attributes

At the end, third method had better result because our missing values were broadcasted.



### Frequent pattern
This stage of project extract pattern 
#### extract pattern of selling products, which are post in Divar in different cities.

#### extract pattern of selling products in Digikala dataset.

#### extract frequent pattern between day of uploading post and platform

#### extract frequent pattern between products and platform

### clustering
make product category based on popularity rate and people's purchase rate. use agglomerative, k-means and DBSCAN algoritms.

#### clustring the cities based on posting products

#### Clustring the cities based on selling products

#### Comparison of clustring in previous phase

#### Clustring products based on price


### classification
predict price for products using LinearRegression algorithm.
