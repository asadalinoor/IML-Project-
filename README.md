# IML-Project-S17

# Description
  Our project is predict the price of house. The main purpose of this project to give accurate prediction about the price of house. We are using Linear Regression to solve this problem. In implementation we will use Linear Regression and we can also use Nueral Network to solve this problem. It means we are going to apply both models Linear Regression and Nueral Netwrok on local dataset.

# Data
  We are using local dataset 780 local entries and 10 variables for predict the price. Training dataset in RealEstate.csv file. In training dataset prediction shall be based on location, bedrooms, bathrooms, lounge, price per square feet, and garage. In short terms we are generated local dataset through local property dealer LDA(Lahore Development Authority). First we will load the local dataset(load RealEstate.csv file) and then apply the both model Liner Regression and Nueral Network on loacl dataset.
  For loading the data, first we import pnadas library.

# How to Run
  Firstly i will tell you how to load dataset, and how to run dataset.
  For loading the data, first we import pnadas library.
  import pandas as pd
  Now, we read the data from csv file.
  data = pd.read_csv('RealEstate.csv')
  now display data.
  data.head()
