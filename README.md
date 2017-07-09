# IML-Project-S17

# Description
  Our project is predict the price of house. The main purpose of this project to give accurate prediction about the price of house. We are using Linear Regression to solve this problem. In implementation we will use Linear Regression and we can also use Nueral Network to solve this problem. It means we are going to apply both models Linear Regression and Nueral Netwrok on local dataset.

# Data
  We are using local dataset 780 local entries and 10 variables for predict the price. Training dataset in RealEstate.csv file. In training dataset prediction shall be based on location, bedrooms, bathrooms, lounge, price per square feet, and garage. In short terms we are generated local dataset through local property dealer LDA(Lahore Development Authority). First we will load the local dataset(load RealEstate.csv file) and then apply the both model Liner Regression and Nueral Network on loacl dataset.
  For loading the data, first we import pnadas library.

# How to Run

  In this section we will tell you how to load dataset, and how to run dataset.For loading dataset, we read the data from csv file --> data = pd.read_csv('RealEstate.csv'). Now we will tell you runnning proces on Jupyter.The Jupyter Notebook App can be launched by clicking on the Jupyter Notebook icon installed by Anaconda in the start menu (Windows) or by typing in a terminal (cmd on Windows): jupyter notebook. ![Alt text](https://github.com/asadalinoor/IML-Project-/blob/master/jupyter.PNG "Jupyter Run") 

Run a code on jupyter cell using Shift-Enter. There are two more keyboard shortcuts for running code.
- Alt-Enter runs the current cell and inserts a new one below.
- Ctrl-Enter run the current cell and enters command mode. 

  After running the code on Jupyter, we will run python file on anaconda when we downloaded from jupyter. On anaconda we shall open terminal through project environment. We will follow two steps for running the code on anaconda.
- activate Environment
- file name.py

Dependencies of our project run:
- Jupyter NoteBook 4.3.1 or above
- Anaconda Navigator version 1.5 with Python 3.5 or above
- Congratulations, we installed Jupyter Notebook. To run the notebook: jupyter notebook

# Architecture
  
  We are using two alogrithms one is Linear Regression and other is Neural Netwwork. We are using real estate data. After loading the data, we dropped out of that columns which we did not use. In our project basically we are handle the accuracy of price house. In our dataset we dropped id, status, and size of the house columns because they were not tell prediction. After did it, we did convert some cuolumns in to binary form because they can help to find accuracy. Now firstly, we apply the linear regression model and then apply nueral netwrok model on dataset and at the end we did find the accuracy of the given data and they gave us to results.
  
# Results
# Conclusion
  
  In conclusion, we discuss the overall expireince for complete our project. First Linear Regression is a good model, it give us to prediction but you know every model has a drowback. Linear regression does not handle the overfitting issue and it is very sensitive with the outliers. Linear regressions are meant to describe linear relationships between variables. So, if there is a nonlinear relationship, then it is a bad model. It means it is good for Linear data. If non-linearty occurs then it is fail, so in this case we will apply Neural Network Model it will give us linearty. Neural Netwrok also use for prediction but main advantage is Neural network is adaptable to a wide range of parameters and data requirements, as well as the fact they are easy to use, requiring minimal statistics training.
