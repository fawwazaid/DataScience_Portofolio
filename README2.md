# Fawwaz_Portofolio
Data Science Portofolio

# yandex-practicum-projects
Compilation of all projects completed throughout [Practicum's Data Science professional training program]().

| Project name | Description | Libraries used |
| :---------------------- | :---------------------- | :---------------------- |
| [Credit Score Analysis](credit_score) | Utilizing different metrics to determine the likelihood that a customer defaults on a loan. | *pandas*, *nltk* |
| [Real Estate Analysis](real_estate) | Determining the market value of real estate in Saint Petersburg, Russia, and defining parameters that make it possible to create an automated system capable of detecting anomalies and fraud. | *pandas*, *matplotlib.pyplot* |
|[Telecom Plans Analysis](telecom_plans)| Selecting the plan with the highest potential revenue for different target markets through analyzing data from different telecom packages and conducting statistical hypothesis testing. | *pandas*, *numpy*, *math*, *scipy*, *functools* |
|[Video Game Analysis](video_game)| Identifying patterns in historical game sales data, analyzing metrics for each video game platform, and conducting statistical hypothesis testing to spot potential big winners and plan advertising campaigns. | *pandas, numpy, math, scipy, functools, matplotlib.pyplot* |
|[Telecom Plans ML Model](telecom_plans_model)| Developing a machine learning model using aggregated data from the [Telecom Plans](telecom_plans) project to predict the most suitable plan for each customer. | *pandas, sklearn* |
|[Bank Customers Model](bank_customers)| Creating a classification model to predict customer churn for a bank from an imbalanced dataset. | *pandas, sklearn, numpy* |
|[Oil Well Model](oil_well)| Analyzing data from several petroleum reservoir regions and oil wells to calculate the profitability and risk of loss of developing a new well in each region. | *pandas, numpy, sklearn* |
|[Gold Extraction Model](gold_extraction)| Preparing a machine learning model that predicts the amount of gold recovered from the extraction process for the purpose of optimizing production and eliminating unprofitable parameters. | *pandas, numpy, matplotlib.pyplot, sklearn* |
|[Insurance Company Data Obfuscation](insurance_company)| Developing a data transforming algorithm for data obfuscation, and ensuring that data obfuscation does not impact the quality of a machine learning model. | *pandas, sklearn, numpy* |
|[Car Price Model](car_price)| Building a model using historical car data for an app feature that can determine the market value of a user's car. | *pandas, catboost, sklearn, time, lightgbm* |
|[Taxi Orders Model](taxi_orders)| Utilizing historical data on taxi orders at airports to create a model that predicts the amount of taxi orders for any given time frame. | *pandas, statsmodels.tsa.seasonal, matplotlib.pyplot, sklearn, lightgbm* |
|[Movie Review Sentiment Analysis](movie_review)| Training a model to automatically detect negative reviews for a system used to filter and categorize movie reviews. | *math, numpy, pandas, matplotlib, seaborn, tqdm* |
|[Grocery Chain Model](grocery_chain)| Training and evaluating a model to automatically detect the age of a customer at a checkout counter. | *pandas, tensorflow, PIL, glob, numpy, matplotlib.py* |
|[Steel Processing Project](steel_processing)| Optimizing production costs by reducing energy consumption through analyzing historical data from the different stages of steel processing, and creating a model from the consolidated data that can predict the final temperature of finished steel. | *pandas, numpy, sklearn, lightgbm* |

*Projects are listed in the order that they were completed.*

[Certification of completion](https://code.s3.yandex.net/practicum_certificate/DS/04/Wesley_Christyono.pdf)



# Data Scientist 

tasks and projects from the data science [course](https://practicum.yandex.com/profile/data-scientist/) by Yandex

### Final project
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/final/final_project.ipynb)

The telecom operator Interconnect would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. Interconnect's marketing team has collected some of their clientele's personal data, including information about their plans and contracts.


### Sprint #16 - Unsupervised Learning

Theoretical parts and quizzes

### Sprint #15 - Computer Vision
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint15/sprint15.ipynb)

Supermarket chain Good Seed is introducing a computer vision system for processing customer photos. Photofixation in the checkout area will help determine the age of customers in order to:
Analyze purchases and offer products that may interest buyers in particular age groups
Monitor clerks selling alcohol
Build a model that will determine the approximate age of a person from a photograph. To help, you'll have a set of photographs of people with their ages indicated.

### Sprint #14 - Machine Learning for Texts
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint14/sprint14.ipynb)

The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. It will need to reach an F1 score of at least 0.85.

### Sprint #13 - Time Series
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint13/sprint13.ipynb)

Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.
The RMSE metric on the test set should not be more than 48.

### Sprint #12 - Numerical Methods
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint12/sprint12.ipynb)

Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value.
Rusty Bargain is interested in:
* the quality of the prediction
* the speed of the prediction
* the time required for training

### Sprint #11 - Linear Algebra
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint11/sprint11.ipynb)

The Sure Tomorrow insurance company wants to protect its clients' data. Your task is to develop a data transforming algorithm that would make it hard to recover personal information from the transformed data. This is called data masking, or data obfuscation. You are also expected to prove that the algorithm works correctly. Additionally, the data should be protected in such a way that the quality of machine learning models doesn't suffer. You don't need to pick the best model. Follow these steps to develop a new algorithm:
* construct a theoretical proof using properties of models and the given task;
* formulate an algorithm for this proof;
* check that the algorithm is working correctly when applied to real data.

### Sprint #10 - Integrated project 2
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint10/sprint10.ipynb)

Prepare a prototype of a machine learning model for Zyfra. The company develops efficiency solutions for heavy industry.
The model should predict the amount of gold recovered from gold ore. You have the data on extraction and purification.
The model will help to optimize the production and eliminate unprofitable parameters.
You need to:
* Prepare the data;
* Perform data analysis;
* Develop and train a model.
To complete the project, you may want to use documentation from pandas, matplotlib, and sklearn.
The next lesson is about the ore purification process. You will pick the information that is important for the model development.


### Sprint #9 - Machine Learning for Business
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint09/sprint9.ipynb)

You work for the OilyGiant mining company. Your task is to find the best place for a new well.
Steps to choose the location:
Collect the oil well parameters in the selected region: oil quality and volume of reserves;
Build a model for predicting the volume of reserves in the new wells;
Pick the oil wells with the highest estimated values;
Pick the region with the highest total profit for the selected oil wells.
You have data on oil samples from three regions. Parameters of each oil well in the region are already known. Build a model that will help to pick the region with the highest profit margin. Analyze potential profit and risks using the Bootstrapping technique.


### Sprint #8 - Supervised learning
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint08/sprint8.ipynb)

Beta Bank customers are leaving: little by little, chipping away every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.
We need to predict whether a customer will leave the bank soon. You have the data on clients’ past behavior and termination of contracts with the bank.
Build a model with the maximum possible F1 score. To pass the project, you need an F1 score of at least 0.59. Check the F1 for the test set.
Additionally, measure the AUC-ROC metric and compare it with the F1.


### Sprint #7 - Introduction to machine learning
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint07/sprint7.ipynb)

Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra.
You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model.
Develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.


### Sprint #6 - Data Collection and Storage (SQL)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint06/sprint6.ipynb)

You're working as an analyst for Zuber, a new ride-sharing company that's launching in Chicago. Your task is to find patterns in the available information. You want to understand passenger preferences and the impact of external factors on rides.
You'll study a database, analyze data from competitors, and test a hypothesis about the impact of weather on ride frequency.

### Sprint #5 - Integrated Project 1
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint05/sprint5.ipynb)

You work for the online store Ice, which sells videogames all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This allows you to put your money on a potentially hot new item and plan advertising campaigns.
In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.
The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 2026.
The data set contains the abbreviation ESRB (Entertainment Software Rating Board). The ESRB evaluates a game's content and assigns an appropriate age categories, such as Teen and Mature.

### Sprint #4 - Statistical data analysis
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint04/sprint4.ipynb)

You work as an analyst for "Megaline", a state mobile operator. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department would like to know which of the plans is more profitable in order to adjust the advertising budget.
You are going to carry out a preliminary analysis of the plans based on a relatively small client selection. You'll have the data on 500 "Megaline" clients, specifically, who the clients are, where they are from, which plan they use, the number of calls made and SMS they sent in 2018. You have to analyse clients' behavior and work out the most profitable prepaid plan.

### Sprint #3 - Exploratory Data Analysis (EDA)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint03/sprint3.ipynb)

You’ll have the data from Yandex.Realty provided for you. Working with data will not always be completely familiar - from time to time, you'll encounter data from peculiar sources, operating with peculiar measurements. Let's work with something exotic to keep you on your toes: a real estate agency has an archive of sales ads for realty in St. Petersburg, Russia, and the surrounding areas collected over the past few years. You’ll need to learn how to determine the market value of real estate properties. Your task is to define the parameters. This will make it possible to create an automated system that is capable of detecting anomalies and fraud.
There are two different types of data available for every apartment for sale. The first type is a user’s input. The second type is received automatically based upon the map data. This could be calculated, for example, based upon the distance from the downtown area, airport, the nearest park or body of water.


### Sprint #2 - Data Preprocessing
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imvladikon/ya-praktikum/blob/master/sprint02/sprint2.ipynb)

Your project is to prepare a report for a bank’s loan division. You’ll need to find out if a customer’s marital status and number of children has an impact on whether they will default on a loan. The bank already has some data on customers’ credit worthiness.
Your report will be considered when building a credit scoring of a potential customer. A credit scoring is used to evaluate the ability of a potential borrower to repay their loan.


### Sprint #1

Python and Data Analysis Basics, Introduction to Data Science



#### notes
for pre-commit hooks (converting jupyter notebooks to py/html files) need to install:

```bash
pip install pre-commit
pre-commit install
```

see [here](https://pre-commit.com/)

# Yandex Practicum Data Science Projects

<p align="center">
  <img src="https://github.com/imeleges/YPDS_Projects/blob/main/img/yandex_practicum.png?raw=true" />
</p>


Repository containing portfolio of **Data Analytics** | **Data Science** with **Machine Learning** projects completed during the training courses at **Yandex.Practicum**

[![certificate](https://img.shields.io/badge/сertificate-Data%20Scientist%20ENG-8abd80)](https://github.com/imeleges/YPDS_Projects/tree/main/certificates/сertificate_yandex_data_scientist_ENG.png)  


## Projects list:  
- [![PROJ_01](https://img.shields.io/badge/🔗%20PROJ-01-success)](#connection-between-loan-borrowers-features-and-chances-of-him-paying-back) "Bank Data Analysis: Connection between loan borrower's features and chances of him paying back"  
- [![PROJ_02](https://img.shields.io/badge/🔗%20PROJ-02-success)](#fraud-prevention-in-real-estate-listings) "Real Estate Market Analysis: Fraud prevention in Real Estate listings"  
- [![PROJ_03](https://img.shields.io/badge/🔗%20PROJ-03-success)](#telecom-company-part-1-statistical-data-analysis-determination-of-a-profitable-tariff-plan) "Telecom Company Pt 1: Statistical Data Analysis. Determination of a profitable tariff plan"
- [![PROJ_04](https://img.shields.io/badge/🔗%20PROJ-04-success)](#gamedev-studying-the-patterns-that-determine-videogame-platform-success) "Gamedev: Studying the patterns that determine videogame platform success"
- [![PROJ_05](https://img.shields.io/badge/🔗%20PROJ-05-success)](#telecom-company-part-2-a-tariff-recommendation-model) "Telecom Company Pt 2: A tariff recommendation model" 
- [![PROJ_06](https://img.shields.io/badge/🔗%20PROJ-06-success)](#bank-customer-churn-modeling) "Bank customer churn modeling"
- [![PROJ_07](https://img.shields.io/badge/🔗%20PROJ-07-success)](#choosing-a-region-for-the-development-of-new-oil-fields) "Choosing a region for the development of new oil fields"
- [![PROJ_08](https://img.shields.io/badge/🔗%20PROJ-08-success)](#building-machine-learning-algorithm-for-a-metalworking-enterprise) "Building machine learning algorithm for a metalworking enterprise"
- [![PROJ_09](https://img.shields.io/badge/🔗%20PROJ-09-success)](#insurance-company-development-of-an-algorithm-to-protect-customer-data) "Insurance Company: Development of an algorithm to protect customer data"
- [![PROJ_10](https://img.shields.io/badge/🔗%20PROJ-10-success)](#car-price-prediction-model) "Car price prediction model"
- [![PROJ_11](https://img.shields.io/badge/🔗%20PROJ-11-success)](#ride-hailing-company-predicting-the-number-of-taxi-orders) "Ride-hailing Company: Predicting the number of taxi orders"
- [![PROJ_12](https://img.shields.io/badge/🔗%20PROJ-12-success)](#natural-language-processing-classifying-comments) "Natural Language Processing: Classifying comments"
- [![PROJ_13](https://img.shields.io/badge/🔗%20PROJ-13-success)](#a-plant-electricity-consumption-optimization) "Optimization of electricity consumption in industry"

***

[![PROJ_01](https://img.shields.io/badge/go%20to%20PROJ-01-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_01)  

## "Connection between loan borrower's features and chances of him paying back"  

### Task
Based on bank clients' statistics related to returning the loans, investigate whether marital status or number of children affect the repayment probability of the loan on time

### Description 
Bank credit department has data on the solvency of their customers.  
This project required cleaning data from outliers, processing missing values and duplicates, as well as data types conversion. Categorization of clients is done using lemmatization.
A credit scoring model is built to evaluate the ability of a potential borrower to repay a loan to a bank.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![PyMystem3](https://img.shields.io/static/v1?label=tool&message=PyMystem3&color=cd6133)](#)  

[![Lemmatization](https://img.shields.io/static/v1?label=skill&message=Lemmatization&color=1B9CFC)](#)
[![Data preprocessing](https://img.shields.io/static/v1?label=skill&message=Data%20Preprocessing&color=B33771)](#)

***

[![PROJ_02](https://img.shields.io/badge/go%20to%20PROJ-02-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_02) 

## "Fraud prevention in Real Estate listings"  
 
### Task  
Based on data from a real estate service for St. Petersburg, Russia, determine the cost of listings based on their parameters to delect fraudulent ones

### Description
Conducted research analysis and data preprocessing for a dataset with apartments listed for sale.
To determine anomalies that might indicate fraud flat features explored: distance from the city center, area in square meters, ceiling height, number of rooms, district, publishing date and price.
Market value of real estate objects was determined uwing Yandex Real Estate Service platform data.
Feature engineering, histograms, boxplots, scatterplots to explore features affecting the price.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)  

[![Data visualization](https://img.shields.io/static/v1?label=skill&message=Data%20visualization&color=F97F51)](#)
[![Exploratory data analysis](https://img.shields.io/static/v1?label=skill&message=Exploratory%20Data%20Analysis&color=82589F)](#)
[![Data preprocessing](https://img.shields.io/static/v1?label=skill&message=Data%20Preprocessing&color=B33771)](#)

***

[![PROJ_03](https://img.shields.io/badge/go%20to%20PROJ-03-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_03) 

## "Telecom Company Part 1: Statistical Data Analysis. Determination of a profitable tariff plan"

### Task  
Based on a mobile network provider's customer behavior data, recommend the tariff that brings most profit

### Description
A telecom operator clients use outdated tariffs.
Sample customers' tariff plan usage analysis helped to find suitable plan recommendations for users.
A/B-test results showed statistically significant revenue difference between two tariffs. Another hypothesis checked with A/B-test - higher revenue from Moscow clients and other regions combined.
To adjust the advertisement budget a more profitable tariff plan has been determined and advised to the marrketing team.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![SciPy](https://img.shields.io/static/v1?label=tool&message=SciPy&color=34ace0)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=Seaborn&color=ff5252)](#)  

[![Descriptive statistics](https://img.shields.io/static/v1?label=skill&message=Descriptive%20statistics&color=58B19F)](#)
[![Statistical hypothesis testing](https://img.shields.io/static/v1?label=skill&message=Statistical%20hypothesis%20testing&color=3B3B98)](#)

***

[![PROJ_04](https://img.shields.io/badge/go%20to%20PROJ-04-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_04)

## "Gamedev: Studying the patterns that determine videogame platform success"

### Task  
Using historical user and expert ratings date, genres and number of copied sold for various platforms, identify patterns that contribute success of a game

### Description
An online computer games store has customers worldwide. Historical data about games from open sources is available to identify a potentially popular product. This helps to plan advertising campaigns.
Games that are the best bet for being popular and bring most sales are selected. Customer preferences for various regions of the world are noted.
A/B-test results revealed that average user ratings between platforms Xbox One and PC do not have statistically significant difference.
Another A/B-test showed that average user ratings between genres Action and Sports are different.
T-test for independent samples.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![SciPy](https://img.shields.io/static/v1?label=tool&message=SciPy&color=34ace0)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=Seaborn&color=ff5252)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)  

[![Descriptive statistics](https://img.shields.io/static/v1?label=skill&message=Descriptive%20statistics&color=58B19F)](#)
[![Statistical hypothesis testing](https://img.shields.io/static/v1?label=skill&message=Statistical%20hypothesis%20testing&color=3B3B98)](#)
[![Data preprocessing](https://img.shields.io/static/v1?label=skill&message=Data%20Preprocessing&color=B33771)](#)
[![Exploratory data analysis](https://img.shields.io/static/v1?label=skill&message=Exploratory%20Data%20Analysis&color=82589F)](#)

***

[![PROJ_05](https://img.shields.io/badge/go%20to%20PROJ-05-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_05)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Telecom Company Part 2: A tariff recommendation model"  

### Task  
Based on the previous data study, build the Machine Learning model for the classification problem, which finds a suitable tariff

### Description
A system recommending users a more suitable tariff based on their data usage, amount of calls and sms.
A classification model with the highest accuracy value is built to select the tariff to be suggested to the user.
Correct ratio answers raised to 0.75. Accuracy tested on the test sample.

**Trends**  
[![Data Analyst](https://img.shields.io/static/v1?label=trend&message=Data%20Analyst&color=218c74)](#)
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_06](https://img.shields.io/badge/go%20to%20PROJ-06-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_06)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Bank customer churn modeling"  

### Task  
Analyse data of clients terminating their contract with the bank and to choose strategy of retainung them or attracting new clients

### Description
More clients leave the bank every month. 
A model is build using unbalanced data to predict the probability of a client leaving the bank in near future.
High F1 sroce was reached with subsequent verification on a test sample. Additionally AUC-ROC score was measured, correlated with F1 score. 

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_07](https://img.shields.io/badge/go%20to%20PROJ-07-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_07)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Choosing a region for the development of new oil fields"  

### Task  
Selecting the most profitable regions for oil extraction. Building a machine learning model helping determine the area where drilling will bring the most profit with the least risk of loss.

### Description
An oil company needs to make decion on developing the next well location.
The existing data is oil samples' characteristics for varoius wells. Data contains oil quality parametres and oil reserves information in three regions. Characteristics of each well in the region are already known.

A machine learning model forecasts oil reserves in new wells.
The model assists in picking the region with most profitable set of wells to be drilled.

Part of the research is potential profit and risk assessment using `Bootstrap` methodology.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)
[![Bootstrap](https://img.shields.io/static/v1?label=tool&message=Bootstrap&color=ffb142)](#)
[![SciPy](https://img.shields.io/static/v1?label=tool&message=SciPy&color=34ace0)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_08](https://img.shields.io/badge/go%20to%20PROJ-08-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_08)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Building machine learning algorithm for a metalworking enterprise"  

### Task  
Building a model predicting recovery rate for gold from gold ore

### Description
A gold mining company needs a solution to perfect its efficiency.
A model forecasting gold recovery rate is created using ore extraction and refinement parametres data.
The model is developed to help optimize production by assessing ore quality to avoid financial losses on ineffective operations.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![Matplotlib](https://img.shields.io/static/v1?label=tool&message=Matplotlib&color=706fd3)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)
[![Seaborn](https://img.shields.io/static/v1?label=tool&message=Seaborn&color=ff5252)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_09](https://img.shields.io/badge/go%20to%20PROJ-09-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_09)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Insurance Company: Development of an algorithm to protect customer data"  

### Task  
Data transformation method for the insurance company clients' personal information protection

### Description
An insurance company needs to protect its customers information using data transformation methods. This helps to prevent sensitive data from being decrypted. 
This project required data preprocessing. The linear regression model algorythm was validated by multiplying the results on an invertible matrix. Conversely, multiplication on an inverse matrix of the invertible matrix proved the model works correctly. R2 score for linear regression model was measured on indentical data: initial data first, then data multiplied on invertible matrix (size of the features count). Metrics matched perfectly which means the algorythm works.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)
[![NumPy](https://img.shields.io/static/v1?label=tool&message=NumPy&color=ffda79)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_10](https://img.shields.io/badge/go%20to%20PROJ-10-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_10)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Car price prediction model"  

### Task  
Train the model to determine the market value of the car based on its parametres

### Description
A company selling used cars is developing an app. One of the features attracting new clients is functionality of estimating a car's worth based on its features and characteristics. A car cost forcasting model was created using historical data.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_11](https://img.shields.io/badge/go%20to%20PROJ-11-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_11)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Ride-hailing Company: Predicting the number of taxi orders"  

### Task  
Train a model to predict taxi ride demand for the next hour

### Description
A taxi hailing services company has historical data of rides ordered from the airport area. Model was built to forecast taxi demand for the next hour. This is to help balance amount of cars around the airport and have the right amount of drivers in the area for peak and off peak hours.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![Scikit-learn](https://img.shields.io/static/v1?label=tool&message=Sklearn&color=ff793f)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_12](https://img.shields.io/badge/go%20to%20PROJ-12-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_12)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "Natural Language Processing: Classifying comments"  

### Task  
Speeding up the moderation of product desctiption commentaries on an ecommerce website by automating their tone assessment. Training the model to classify comments as positive or negative

### Description
An online retail store launched a new feature: product description edit can now suggested by website users similar to wiki communities. Other users comment on proposed changes. A model developed to detect 'toxic' commentaries to be moderated.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![NLP](https://img.shields.io/static/v1?label=tool&message=NLP&color=218c74)](#)
[![nltk](https://img.shields.io/static/v1?label=tool&message=nltk&color=474787)](#)
[![tf-idf](https://img.shields.io/static/v1?label=tool&message=tf-idf&color=227093)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***

[![PROJ_13](https://img.shields.io/badge/go%20to%20PROJ-13-success)](https://github.com/imeleges/YPDS_Projects/tree/main/PROJ_13)
![ML](https://img.shields.io/static/v1?label=&message=ML&color=blue)

## "A plant electricity consumption optimization"  

### Task  
Metallurgical plant production costs optimization by reducing energy consumption during steel processing

### Description
To adjust production costs the smeltery management needs to reduce electricity consumption during the steel processing.

**Trends**  
[![Data Scientist](https://img.shields.io/static/v1?label=trend&message=Data%20Scientist&color=706fd3)](#)

**Tools and Skills**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)  

[![Machine learning](https://img.shields.io/static/v1?label=skill&message=Machine%20learning&color=blue)](#)

***


All work in this repository are my project created as study cases during the online bootcamp  **Data Science** by **Yandex.Practicum**.
All code was validated by a code reviewer whose commentaries were deleted to keep the projects neat.  

Each case study was done in the `Jupyter Notebook` environment and is a `.ipynb` notebook. Every project has a detailed tasks description, skills and tools used.


