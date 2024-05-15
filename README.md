# Social-Network-Analysis-PySpark
## Problem Defination
Using Spark and a suite of relevant big data tools to analyze social media data for gaining insights into user behavior, trends, and sentiment. Data can be collected from Twitter. The dataset will be analyzed to find out which topics are of interest or popular, what people are talking about a particular brand or product, and how users are engaging with the social media content. 

## Dataset
This is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .

It contains the following 6 fields:

- `target`: the polarity of the tweet (0 = negative, 4 = positive)
- `ids`: The id of the tweet ( 2087)
- `date`: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- `flag`: The query (lyx). If there is no query, then this value is NO_QUERY.
- `user`: the user that tweeted (robotickilldozr)
- `text`: the text of the tweet (Lyx is cool)

## Tools
- Jupyter notebook(connected with Apache Spark)
In order to use PySpark in Jupyter Notebook, you should either configure PySpark driver or use a package called Findspark to make a Spark Context available in Jupyter Notebook.
- Python 3.9 
In order to use PySpark on the local machine we should use Python 3.9 
-	PySpark
PySpark is the framework we use to work with Apache Spark and Python to perform distribution among a number of cluster nodes.
-	PySpark SQL 
pyspark.sql is a Spark module for structured data processing in Python. It provides a programming abstraction called DataFrames and also plays the role of a distributed SQL query engine. Compared to the RDD, the PySpark DataFrame is faster.
-	PySpark MLib
Apache Spark makes the MLlib Machine Learning API available. For feature extraction, clustering, regression, and classification, it offers a number of techniques, and we utilized it to create machine learning models that can predict the sentiment from any text.
-	PySpark ML
Users can build and fine-tune practical machine learning pipelines with the aid of the uniform set of high-level APIs offered by ML Pipelines, which are constructed on top of DataFrames.
-	Beautiful Soup API
BeautifulSoup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. We utilized it to avoid fail while importing the text due to BOM characters.
