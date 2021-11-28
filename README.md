# ML-Project

## Introduction
<p align="center"><img src="https://d1wa5qhtul915h.cloudfront.net/app/uploads/2021/08/Bike-Europe-Stock-Chart.jpg" width="200"></p>
Our project aimed to analyze various predictive models on the
stock market trends of the selected companies and try to find
the best prediction technique that is effective for stock market
prediction. Stock market trends are nonlinear, and much data is
generated worldwide every day, causing extreme speculation
globally.
To be specific, for a given company, we obtain its historical
stock prices, opening, closing, and daily highs and lows records
and try to predict the direction and magnitude of the trend of
the price using the trained models. We analyzed our results and
tried to compare various learning approaches for predictions,
and this comparative analysis will allow us to determine the
more reliable attributes that can be trusted to predict future
stock market trends.
We plan to analyze predictions on machine learning models
based on Stochastic Gradient Descent(SGD) regression,
Support vector machine (SVM), Long-short term memory
(LSTM), and Convoluted Neural Network (CNN).

## Objective:  We want to use ML techniques to help predict stock prices of various companies.
 The companies which we have chosen are:
    Amazon  
    TCS 
    Thomas Cook India
    Coca-cola company
    Tesla
    

 We intend to analyse various ML models on the available data for the given companies. we have trained 4 diffeent models, Linear Regression (SDG), Support-vector machine (SVM), Convoluted Nueral Network (CNN) and Long-short term memory model (LSTM).
 
 # How to Run the project
For each model user can find different files in the root folder named with the name of the model

1. For analysis of SVM and SGD user can find the python notebook as SVM__and_SGD.ipynb. To run the file click the below button or download it and run the file using jupyter notebook.
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhakaraman/ML-Project/blob/main/SVM__and_SGD.ipynb)

2. For analysis of CNN model user can find the python notebook as CNN.ipynb.
To run the file click the below button or download it and run the file using jupyter notebook.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhakaraman/ML-Project/blob/main/CNN.ipynb)

3. For analysis of LSTM model user can find the python notebook as LSTM.ipynb.
To run the file click the below button or download it and run the file using jupyter notebook.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhakaraman/ML-Project/blob/main/LSTM.ipynb)

For running the analysis user needs to download the data for all the companies it can be found in the data folder of in the root directory(click below links for the data diretory).

Traing data : [Training Data for 5 companies](https://github.com/dhakaraman/ML-Project/tree/main/data)
Here you can see the data named as [company_name].csv for 5 different companies.

Testing Data : [Testing Data for 5 companies](https://github.com/dhakaraman/ML-Project/tree/main/data/test)
Here you can see the data named as [company_name_test].csv for 5 different companies.

You need to download the data and upload it on google colab.
![alt text](https://i.postimg.cc/sXf7hdPX/colab-Image.png)
In the above image you can see a highlighted box. You can upload the files in the google colab using this button. After opening the file to be analysed in google colab

# Data Preprocessing:
Exploratory Data Analysis and Visualisation was carried on out on the training data and the results are present in the Data Analysis folder, the file ML_proj.ipynb contains all the visualisation graphs for each of the company selected. Some of the features were dropped due to their unrelated nature from the problem in hand.

![alt text](https://github.com/dhakaraman/ML-Project/blob/c9669fa13e42ce9c08f6c7d4619c9b32545e537b/Data%20Analysis/Analysed_Data.png)

# Results and Analysis
Results are compiled in the Report and were presented during the presentation. The plots are presented in the plots folder.

![alt text](https://github.com/dhakaraman/ML-Project/blob/3015a227198ba6c4539bfeac3577086cd801bc29/Plots/SDG/COKE.png)
![alt text](https://github.com/dhakaraman/ML-Project/blob/3015a227198ba6c4539bfeac3577086cd801bc29/Plots/CNN/TCS_train_validation_loss.jpg)




