# House Price Prediction System 

Introduction
Creating a Machine Learning model to predict the home prices in  USA. We are going to use the dataset from Kaggle.com. We are also going to create a single page website which will provide the front end to access our model for predictions.

Below data science concepts are used in this project.

Data loading and cleaning
Feature engineering
Dimensionality reduction
Gridsearchcv for hyperparameter tunning
K fold cross validation

Technology and tools used in this project

Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Google Colaboratory Notebook
Python flask for http server
HTML/CSS/Javascript for UI
Steps

We will first build a model using sklearn and linear regression using USA Housing dataset from kaggle.com.
Second step would be to write a python flask server that uses the saved model to serve http requests.
Third component is the website built in html and css that allows user to enter home square ft area, bedrooms etc and it will call python Django server to retrieve the predicted price.

# Step Involved For Building Model :

Step#1: Import the required libraries

Step#2: Load the data

Step#3: Understand the data

     
Step#4: Data Cleaning
        - Check for na values
        - Verify unique values of each column
        - Make sure values are correct (eg. 23 BHK home with 2000 Sqrft size is worng)
        - Feature Engineering
        - Dimesionality Reduction
        - Outlier removal using domain knowledge (2bhk price < 3bhk price, size per bhk >= 300 sqft)
        - Outlier removal using standard eviation and mean
        - One Hot encoding
        
        
Step#5: Build Machine Learning Model

Step#6: Testing The model

Step#7: Export the model

Step#8: Export any other important info

Dataset Reference

USA Housing data
I have also uploaded the csv file in this repository /content/USA_Housing (1).csv

# Conclusion : 
 The development of a house price prediction system has shown significant promise in providing valuable insights into real estate markets. By leveraging advanced machine learning techniques and a rich dataset encompassing diverse features such as location, size, amenities, and market trends, the system has demonstrated its ability to forecast property values with reasonable accuracy.

This predictive capability not only aids prospective buyers and sellers in making informed decisions but also provides real estate professionals and investors with a powerful tool for strategic planning and risk management. Moving forward, continued refinement of the model through ongoing data collection and algorithmic improvements promises even greater accuracy and reliability. As the housing market evolves, the adaptation and enhancement of such systems will be crucial in navigating its complexities and maximizing opportunities for all stakeholders involved."
