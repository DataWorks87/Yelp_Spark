Analyzing 10Gb of Yelp Reviews Data

The project is based on Yelp Reviews data available on Kaggle. In order to perfom this analysis I provisioned a Spark Cluster on AWS EMR and uploaded the data set in a AWS S3 bucket. The data set used from analysis is the business, review and user files. The analysis was done in Jupyter Notebook using PySpark Data Frame. 

The project includes several sections such as: 

- Importing necessary dependencies and data upload from AWS S3 bucket
- Splitting business data in categories 
- Analyzing the skewness of Yelp Reviews 
- Analyzing the skewness of reviews completed by elite Yelp users


![cluster_configuration](https://user-images.githubusercontent.com/64224466/120900772-bb54d580-c604-11eb-88dc-8ea82f3904ba.png)



![notebook_configuration](https://user-images.githubusercontent.com/64224466/120900776-d0c9ff80-c604-11eb-8115-e848e3048e78.png)


