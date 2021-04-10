# Natural-Language-Processing-on-YELP-Dataset

The aim of our project is to perform natural language processing and sentiment analysis on Yelp’s reviews dataset and compare the accuracies of different classifiers. In this zipped folder , we have total 7 files, where two files are data files, two png files and three code files. Data files which are used here are yelp_reviews.csv and yelp_business.csv . These files are obtained from https://www.yelp.com/dataset/challenge. We attached dataset files with the project for convenience. 

There are two .png files :
thumb_up.png
thumb_down.png 

These .png files are used in the code to display word cloud for positive feedback(thumb up) and negative feedback(thumb down) . These files need to be in the same location as code files for code to work properly. 
There are three code files .
Business_exploratory_Analysis.py : This file has the exploratory data analysis of yelp_business.csv file dataset.
Reviews_exploratory_Analysis.py : This file has the exploratory data analysis of yelp_reviews.csv file dataset.
NLP_Sentiment_Analysis.py : We can consider this file to be most important as it has both main aspects of our project which are Natural Language Processing and Sentiment Analysis. It has code for model creation, feature creation and also for training and testing models and then getting accuracies of different classifiers, their classification reports, confusion matrix and f1-scores . 

Steps to run the project : Place all the csv files and .py files in the same location. For running the program from command prompt or terminator , Kindly run below command preceded by the location where the files are located. location to file > python NLP_Sentiment_Analysis.py 

Packages to be installed :
  Pandas for reading csv file --- command: pip install Pandas
  NLTK package for stopwords removal --- command: pip install NLTK
  Seaborn and matplotlib for exploring and visualizing data --- command: pip install Seaborn, pip install matplotlib
  sklearn --- command: pip install sklearn (This is used for using Multinomial naive Bayes, KNN and SVM and random forest classifiers)
