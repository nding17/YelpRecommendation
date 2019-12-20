# Yelp Recommendation
Yelp Recommendation - Final Project for the Personalization Course

#### Project Status: [Completed]

## Project Objective
The team aims to develop a recommendation system for Yelp that can predict ratings of restaurants for different users. Bias model and collaborative filtering model (item-based) were used as baseline model to provide benchmarks. Additional models including collective matrix factorization, content-based model and deep learning models were developed to improve the recommendation system. The goal is to utilize the benefits of various models and try to recommend the best restaurants for the users. 

### Methods Used
* Data Visualization
* Baseline Bias Model
* Model Based Collaborative Filtering
* Matrix Factorization
* Natural Language Processing
* Content Based Model
* Consine Similarity
* Latent Semantic Indexing
* Mixture Similarity Matrix
* Collective Matrix Factorization
* Deep Wide Neural Network
* Hyper-parameter Tuning

### Technologies
* Python
* Pandas, Numpy, jupyter
* PySpark
* Surprise
* Sklearn
* Tensorflow 

## Project Description
The objective of the project is to build a recommendation system for Yelp based on their dataset. The recommendation system is designed to predict the last rating for each active user. Based on the prediction of the ratings, the recommendation system can further recommend restaurants to users more accurately to improve user experience, attract new users and retain current users. In this case, Yelp can be more competitive in the market and make more profits.

The team is trying to optimize RMSE and MAE of models to get as accurate predictions of the ratings as possible. Due to the complexity of models, the team used a subset of the whole dataset to develop the models. The recommendation system is built to serve for users, which can predict ratings of restaurants for different users. In this case, to maximize user satisfaction, it is important to develop a model with the lowest RMSE and MAE. Moreover, to provide users with various recommendations rather than limited number of restaurants, the model needs to have large coverage value. 

The team first set up a baseline bias model, and tried to implement various other machine learning models such as deep wide neural network, model based recommendation system utilizing collective matrix factorization, content based model using NLP techniques etc. to out-perform the baseline model. Each of these models have been evaluated with different metrics such as RMSE, MAE and Coverage to consistently measure the the improvements generated by each model, regardless of its computation complexity. 

## Needs of this project

- data sampling
- data exploration/descriptive statistics
- recommendation modeling
- neural network 
- write-up/reporting

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data could be extracted from [here](https://www.yelp.com/dataset/challenge).
3. Check the package requirements necessary to perform the analysis [here](https://github.com/nding17/YelpRecommendation/blob/master/requirements.txt).
4. Write-up/report could also be found [here](https://github.com/nding17/YelpRecommendation/blob/master/IEOR4571_Final_Project_Report.pdf).

## Featured Notebooks
* [Data Sampling](https://github.com/nding17/YelpRecommendation/blob/master/Data%20Sampling.ipynb)
* [Baseline Models](https://github.com/nding17/YelpRecommendation/blob/master/Baseline.ipynb)
* [Side Info](https://github.com/nding17/YelpRecommendation/blob/master/Side%20Info.ipynb)
* [Multiple Correspondence Analysis ](https://github.com/nding17/YelpRecommendation/blob/master/Multiple%20Correspondence%20Analysis.ipynb)
* [Collective Matrix Factorization](https://github.com/nding17/YelpRecommendation/blob/master/Collective%20Matrix%20Factorization%20Model.ipynb)
* [Content Based Models](https://github.com/nding17/YelpRecommendation/blob/master/Content%20Based%20Models.ipynb)
* [Deep Learning Model](https://github.com/nding17/YelpRecommendation/blob/master/Deep%20Wide%20Model.ipynb)

## Contributing Members

|Name     |  Email   | 
|------|-----------------|
|[Chenchen He](https://github.com/ch3385) | ch3385@columbia.edu | 
|[Naili Ding](https://github.com/nding17)| nd2588@columbia.edu        |
|[Tao Li](https://github.com/Megatao) |     tl2863@columbia.edu    |
|[Chaoyue Zheng](https://github.com/chaoyuezheng) |     cz2529@columbia.edu    |
|[Jinglin Chen](https://github.com/Jinglinchen97) |     jc5059@columbia.edu    |


## Contact
* Feel free to contact any of our team members with any questions or if you are interested in contributing!
