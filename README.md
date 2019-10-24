# NoSQL-Projection with MongoDB
## Introduction
Python can be used in database applications. One of the most popular NoSQL database is **MongoDB**.
#### MongoDB
MongoDB stores data in JSON-like documents, which makes the database very flexible and scalable. To be able to experiment with the code examples in this tutorial, you will need access to a MongoDB database. Then you can download  a free MongoDB database at [MongoDB]https://www.mongodb.com.
#### PyMongo
Python needs a MongoDB driver to access the MongoDB database. In this tutorial we will use the MongoDB driver "PyMongo". We recommend that you use PIP to install "PyMongo". PIP is most likely already installed in your Python environment.
- !pip install pymongo
- !pip install pymongo[srv]
---
## Get Started
In conducting the analysis using NoSQL, this stage uses two clusters with two conditions:
- Cluster to check collection movies using ```clustermovie``` <br>
  mongodb + srv: // userstudent: admin1234@cluster0-nnbxe.gcp.mongodb.net/test? retryWrites = true & w = majority
- Clusters to create new collections using ```cluster_cleanmovies``` <br>
  mongodb + srv: // admin1234: 12345@cluster0-miqju.gcp.mongodb.net/test? retryWrites = true & w = majority
#### Provisions
1. Create a new collection using ```pymongo projecting_queries```
2. Fill in the value of ```each variable``` in one document in the new collection using ```movies_initial``` in the ```sample_mflix database``` in the ```clustermovie connection```
3. Save the ```new collection``` with the name of each participant in the connection ```cluster_cleanmovies```, namely clean_movies_nurlailiis into the ```sample_mflix database```
#### Validation
1. All documents on ```clean_movies``` and ```movies``` are the same.
2. Many documents on ```clean_movies``` and ```movies``` are the same.
3. All fields in ```clean_movies``` are in the ```movies```.
4. All values in ```clean_movies``` are the same as all values in the ```movies``` in the same order.
---
## Technologies
To execute this section you can use this technologies.
1. Jupyter Notebook
2. MongoDB Atlas or MongoDB Compass
