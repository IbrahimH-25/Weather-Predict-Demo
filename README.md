# Weather-Predict-Demo
## Purpose:
### Create a demo program that predicts what the current weather is based on a few parameters. The Program uses supervised learning with a Guassian Naive Bayes model. The notebook goes through the steps it took from getting data, looking at the data, determining parameters and what machine learning model to use, training and testing. THe data used is a data from seattle weather. 

## Dependencies
1. Pandas
2. Sklearn
3. Numpy
4. Matplotlib

## Main Functions
1. getInputs
  - Gets inputs to use in the ML model from the user
  - Uses a series of if statements and inputs
  - UseSys paremeter is default to True, This means that the program wont ask for the date from the user and use the systems date
2. PredictCurWeather
  - inputList paremeter is default as a empty list, if a list with 7 values for predicting is passes then it will use that list, if not will use getInputs method to get input
  - askInput is set to True by default, When true it will ask for the users input with the method getInput
  - This method is a short version of the entire notebook, just using the neccesary code to run, create a model, and predict the value with a output that shows the predicted value ad the accuracy of the prediction.

## Sources
- can be run on google colab - https://colab.research.google.com/drive/11h-pof9e9gPl_gFD4QQZrUl3HwEFdsmG?usp=sharing
- Dataset Used
- Can be downloaded and run with a program that runs jupyter notebooks, must keep csv file in the same folder as notebook.
