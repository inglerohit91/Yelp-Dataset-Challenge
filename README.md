# Yelp-Dataset-Challenge
Final Project for the Information Retrieval Course

INTRODUCTION - 
The yelp dataset challenge involves data from Phoenix, Las Vegas, Madison, Waterloo and Edinburgh consisting of approximately 42153 businesses where users have provided their tips and reviews for these businesses. The challenge here is divided into 2 tasks. The first task expects these reviews to be classified appropriately by using the reviews that are given to them by multiple users. The second task involves rating a particular business using the tips and reviews available for each of the businesses.

PREPROCESSING - 
The original Yelp dataset is provided in JSON format. Here, we stored the information present in JSON files as Mongo DB collections and then used mongoDB information for these files which helps us to retrieve necessary information and ignore the ones that are not relevant to the tasks. These files are later converted into ARFF file format since the machine learning tools that are used for this challenge takes the input files in ARFF format.
