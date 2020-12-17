<h1 align="center">DMML 2020 - Project: Real or Not? NLP with Disaster Tweets</h1>
<h1 align="center"> Team Hublot</h1>

## Team members

- Aliou BALDE 
- Lorenzo Mezzini
- Zachary Said

## Video presentation
[![Watch the video](https://img.youtube.com/vi/EygBMdGmrUk/maxresdefault.jpg)](https://www.youtube.com/watch?v=EygBMdGmrUk)

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Roadmap](#Roadmap)
* [Progression report](#Tasks)
  * [Week 1](#Week-1)
  * [Week 2](#Week-2)
  * [Week 3](#Week-3)
  * [Week 4](#Week-4)
  * [Week 5](#Week-5)
* [Results](#Results)



<!-- About the project-->
## About the project
Twitter is one of the most used Social Media websites. A lot of information is disseminated everyday. Lately, one can hardly distinguish real news from fake news. 
This project aims to build a Machine Learning model that can predict which tweets are about real disasters and which are not. 
The project topic relates to a kaggle competition. We have two datasets (a training set and a test set) at our disposal to analyse and make the best prediction possible for the test set.

<!-- Roadmap -->
## Roadmap
We will start by carrying out basic EDA to get familiar with the data. We will continue by applying text processing techniques to clean the tweets. We will finish by building different classifiers using different methods such as logistic regression, kNN, Decision trees and Random Forest. 
Our objective is to get the best prediction score (accuracy). 
<!-- Progression report -->
## Progression report 

### Week 1

**Github** 
- Repo initialisation
- Readme.md creation
- Data upload

 **Data** 
- Brainstorming, tasks repartition within the team
- First analysis and submission

### Week 2

**Github**
- Readme.md update

 **Data** 
- Text analysis and pre-processing: remove stopwords, lemmatize, punctuation
- Adjustment to the classifier using logistic regression

### Week 3

**Github**
- Readme.md update

 **Data** 
- Exploratory data analysis to help improve the text cleaning
- Feature engineering and hyper parameter tuning
- Classifier comparison: Logistic regression (with and without Cross validation), Random Forest, Decision Tree, k-Nearest Neighbor

### Week 4

**Github**
- Readme.md update

 **Data** 
- More EDA
- Further engineering
- Classifier comparison and improvement

 **Project submission** 
 - Final notebook preparation with the different elements required
 
 ### Week 5 (Final week)
**Github**
- Readme.md update and finalisation
- Upload the final notebook, a file tracking our submissions and the submissions

 **Data** 
- Further feature engineering
- Classifier comparison and improvement using different techniques

 **Project submission** 
 - Project notebook completion: it contains EDA, Text cleaning, Classifier comparison, Hyperparameter tuning and a discussion of the results-
 - Video preparation



<!-- Results -->
## Results 
In this section we report the results of our submissions on the [AI CROWD DMML COMPETITION](https://www.aicrowd.com/challenges/final-project-of-the-data-mining-and-machine-learning-course/leaderboards).

### Week 1
Best accuracy score =  0.81  
-Tokenizer: remove stopwords, lemmatize, bag of words  
-CLassifier: Logistic regression  
-Parameters: (solver: 'lbfgs', max_iter=1000)  
### Week 2
Best accuracy score =  0.823  
Feature engineering: Concatenate text and keywords into 'key_text' feature  
Tokenizer: remove stopwords, lemmatize, bag of words  
CLassifier: Logistic regressionCV  
Parameters: (solver: 'lbfgs', max_iter=2000, cv=3)  
### Week 3
Best accuracy score =  0.823  
Same as above
### Week 4
We got better results in our training set but the final accuracy score stayed 0.823  
### Week 5
We tried new techniques that helped us reach our best results so far (0.823).   
Correct some target values in the training set  
Improved cleaning to preserve patterns in the data and let the classifier train on these patterns. 
  
### Final
- Best accuracy score = 0.823
- Rank = 3 (on AI Crowd competition)


![alt text](https://github.com/zsgithub2/Hublot-project/blob/main/Documents/accuracy%20plot.png?raw=true)
