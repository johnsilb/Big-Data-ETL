# Big-Data-ETL

The first step in the ETL of this file was to import the environment that will be needed to process the data, including SPARK and to create a SparkSession in Google Colab

The second step was to identifyl two datasets to work with from the the Amazon reviews link we were supplied with and to down load the data and identify the number of reveiws in the file. 

Next we created various dataframes that are subsets of the larger spark dataframe. 

We then needed to create a connection to postgres and create the schema for each of the tables and to load the files into an AWS S3 bucket.
