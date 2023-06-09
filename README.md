# Joaquín Rodrigo García - Data Science Portfolio

## About portfolio
Projects, practices, examples of my job as Data Science, focused on modelling.

Below some examples as a showcase of my skills and work during my Master in Data Science at Immune Technology Institute and self-learning projects. 
I hope it could be useful and of your interest.

## Table of contents

* [About portfolio](#about-portfolio)
* [Projects](#projects)
  * [KMeans: Customer Segmentation (ML: Unsupervised Algorithm)](#kmeans-customer-segmentation)
  * [DBSCAN: Customer Segmentation (ML: Unsupervised Algorithm)](#dbscan-customer-segmentation)
  * [Isolation Forest: Bank Fraud (ML: Unsupervised Algorithm)](#isolation-forest-bank-fraud)
  * [Apriori: Shopping Basket Analysis (ML: Unsupervised Algorithm)](#apriori-shopping-basket-analysis)
  * [Linear Regression: Property Prices (ML: Supervised Algorithm)](#linear-regression-property-prices)
  * [Lasso and Ridge Regularisation: Fat Content in Food (ML: Supervised Algorithm)](#lasso-and-ridge-regularisation-fat-content-in-food)
  * [SVM: Heart Abnormality for Defibrillator (ML: Supervised Algorithm)](#svm-heart-abnormality-for-defibrillator)
  * [Naive Bayes: Diabetes Diagnosis (ML: Supervised Algorithm)](#naive-bayes-diabetes-diagnosis)
  * [Decision Tree Classifier: Top-Selling Shops (ML: Supervised Algorithm)](#decision-tree-classifier-top-selling-shops)
  * [Decision Tree Regressor: Property Prices (ML: Supervised Algorithm)](#decision-tree-regressor-property-prices)
  * [Random Forest: Top-Selling Shops (ML: Supervised Algorithm)](#random-forest-top-selling-shops)
  * [Ensemble: Binary Classification (ML: Supervised Algorithm)](#ensemble-binary-classification)
  * [Time Series: Weather Forecast (ML: Supervised Algorithm)](#time-series-weather-forecast)
  * [NLP: Reviews Analysis (ML: Supervised Algorithm)](#nlp-reviews-analysis)
  * [NLP: Film Recommender (ML: Supervised Algorithm)](#nlp-film-recommender)
  * [NLP: Sentiment Analysis (ML: Supervised Algorithm)](#nlp-sentiment-analysis)
  * [DNN: Bank Churn Rate (ANN)](#dnn-bank-churn-rate)
  * [CNN: Pneumonia Diagnosis (ANN)](#cnn-pneumonia-diagnosis)
  * [LSTM: Microsoft Stock Prediction (ANN)](#lstm-microsoft-stock-prediction)

## Projects

### KMeans: Customer Segmentation
_Code_: [ML_U_KMeans_Customer_Segmentation.ipynb](/ML_Unsupervised/KMeans/)  
_Description_: It was clustered a dataset of 200 customer profiles using the KMeans algorithm, which were described by 5 variables (ID, sex, income, score, and age), into a minimum number of groups.

### DBSCAN: Customer Segmentation
_Code_: [ML_U_DBSCAN_Customer_Segmentation.ipynb](/ML_Unsupervised/DSBCAN/)  
_Description_: dataset corresponds to data from a supermarket, which, through loyalty cards, has data on its customers, such as customer ID, age, gender, annual income and spending score, which is something it assigns to the customer based on its defined parameters such as customer behaviour and purchase data. Let's make a customer segmentation with DBSCAN model.

### Isolation Forest: Bank Fraud
_Code_: [ML_U_Isolation_Forest_Bank_Fraud.ipynb](/ML_Unsupervised/IsolationForest/)  
_Description_: let's work on an example of banking fraud, which contains data on customers who have applied for a loan from the bank. 

### Apriori: Shopping Basket Analysis
_Code_: [ML_U_Apriori_Shopping_Basket.ipynb](/ML_Unsupervised/Apriori/)  
_Description_: from a dataset with 38.765 rows of grocery shop purchase we are going to perform a shopping basket analysis with the Apriori algorithm.

### Linear Regression: Property Prices  
_Code_: [ML_S_LinearRegression_Property_Prices.ipynb](/ML_Supervised/LinearRegression/)  
_Description_: estimate the price of houses in certain districts of California (USA) based on the average values of the characteristics of the houses in each district. 

### Lasso and Ridge Regularisation: Fat Content in Food
_Code_: [ML_S_L1L2_Fat_Content_Food.ipynb](ML_Supervised/Regularisation/)  
_Description_: train a regression model to help us determine the fat content of a certain food product. We have a set of 100 predictor variables associated with the absorption channel spectrum. 

### SVM: Heart Abnormality for Defibrillator
_Code_: [ML_S_SVM_Heart_Abnormality_Defibrillator.ipynb](/ML_Supervised/SVM/)  
_Description_: Automated External Defibrillators (AEDs) are electronic devices commonly used to treat certain types of arrhythmias. These devices are equipped with a predictive classification algorithm that detects whether or not there is any cardiac anomaly. It was used Support Vector Machine for classify a ventricular fibrillation correctly.

### Naive Bayes: Diabetes Diagnosis
_Code_: [ML_S_NaiveBayes_Diabetes_Diagnosis.ipynb](/ML_Supervised/NaiveBayes/)
_Description_: Work out a Naive Bayer model to determine whether or not a person suffers from diabetes.

### Decision Tree Classifier: Top-Selling Shops
_Code_: [ML_S_Decision_Tree_Top-Selling_Shops.ipynb](/ML_Supervised/DecisionTreeClassifier/)  
_Description_: using a Decision Tree Classifier model, top-selling shops were grouped according to their profile as determined by population, shop and product variables.

### Decision Tree Regressor: Property Prices
_Code_: [ML_S_Decision_Tree_Regressor_Property Prices.ipynb](/ML_Supervised/DecisionTreeRegressor/)  
_Description_: model for property prediction in California, using Decision Tree Regressor.

### Random Forest: Top-Selling Shops
_Code_: [ML_S_Ensemble_Random_Forest_Classifier_Top-Selling_Shops.ipynb](/ML_Supervised/RandomForest/)  
_Description_: using a Random Forest, a kind of Ensemble model, top-selling shops were grouped according to their profile as determined by population, shop and product variables.

### Ensemble: Binary Classification
_Code_: [ML_S_Ensemble_Binary_Classification.ipynb](/ML_Supervised/Ensemble/)
_Description_: a binary classification problem is posed to be solved with ensemble algorithms such as VotingClassifier, StackingClassifier, BaggingClassifier and AdaBoostClassifier. Using as simple predictors or weak learners, SVM, decision tree and logistic regression.

### Time Series: Weather Forecast
_Code_: [ML_S_TimeSeries_Weather_Forecast.ipynb](/ML_Supervised/TimeSerie/)
_Description_: a complete univariate time series analysis is performed. Evaluating whether the series is additive or multiplicative, its decomposition into trend, seasonality and noise components. In addition, we will analyse whether the series is stationary, and if not, we will apply the transformations to make it stationary and then apply different algorithms (Benchmark, ARIMA, Prophet) to predict 1 year ahead.

### NLP: Reviews Analysis  
_Code_: [ML_S_NLP_Reviews_Analysis.ipynb](/ML_Supervised/NLP/Reviews_Analysis/)  
_Description_: the objective is to train a model that, from the text of reviews, can detect how positive or negative it is. We are going to work with the dataset of restaurant ratings.

### NLP: Film Recommender  
_Code_: [ML_S_NLP_Film_Recommeder.ipynb](/ML_Supervised/NLP/Film_Recommender/)  
_Description_: let's create a "content-based" film recommendation system.

### NLP: Sentiment Analysis  
_Code_: [ML_S_NLP_Sentiment_Analysis.ipynb](/ML_Supervised/NLP/Sentiment_Analysis/)  
_Description_: from a dataset of tweets labelled according to whether they correspond to good or bad news, we will generate a predictive model that allows us to perform this classification using TF-IDF vectorization with NaiveBayes and LogisticRegressor VS an example made with ruled-based model VADER.

### DNN: Bank Churn Rate  
_Code_: [ANN_DNN_Bank_Clients_Churn.ipynb](/ANN/DNN_Bank_Churn/)
_Description_: work on the usual case of bank churn rate with predictors associated to customer profile and an independent variable indicating whether or not the customer remains with the bank. Using a predictive model of neural network model of the DNN type.

### CNN: Pneumonia Diagnosis  
_Code_: [ANN_CNN_Pneumonia_Analysis.ipynb](/ANN/CNN_Pneumonia_Diagnosis/)  
_Description_: from chest X-ray images (anterior-posterior) selected from retrospective cohorts of paediatric patients aged one to five years from the Guangzhou Women's and Children's Medical Centre, Guangzhou, we are going to train a Convolutional Neural Network model to predict pneumonia cases.

### LSTM: Microsoft Stock Prediction
_Code_: [ANN_LSTM_Microsoft_Stock_Prediction.ipynb](/ANN/LSTM_Microsoft_Stock_Prediction/)
_Description_: As you know it is quite difficult to predict the stock market value as future values are independent of past values, but what we can see is the sign of the trend, if it is positive the stock will go up and if it is negative it will go down. To do this we use the API of the yahoo finance portal and using the yfinance python library we connect and extract the data for 7 years Microsoft Stock Market Price.



## About me

I'm a tech enthusiast, living in Barcelona and working as industrial engineer the last 16 years in many roles and sector: retail, insurance, real estate, architecture, hospital, educational. But always one common factor has always been with me, data and its power when it's turned into information and knowledge. That's maybe the reason why I'm here.

## Contact

* https://www.linkedin.com/in/joaquinrgs/

