# Kaggle TGS Salt Identification Challenge
*Using feature engineering and LightGBM to build a bronze medal solution to the [Kaggle TGS Salt Identification Challenge](https://www.kaggle.com/c/tgs-salt-identification-challenge/overview) on kaggle.*

<img src="https://github.com/jamesdellinger/kaggle_home_credit_default_risk_competition/blob/master/images/thumb76_76.png" height="140">

## Competition Solution
* [Notebook](http://nbviewer.jupyter.org/github/jamesdellinger/kaggle_tgs_salt_identification_challenge/blob/master/kernel_tgs_salt_sub6_unet-ish_resnet34_(BEST).ipynb)

## Concepts
* I applied extensive exploration and preprocessing to the competition's [dataset](https://www.kaggle.com/c/home-credit-default-risk/data).
* Compared the performance various learning models/featuresets/dimensionality reduction.
* Engineered a handful of new features.
* Ultimately got best results by fitting a LightGBM model to the full featureset, in order predict which borrowers are most likely to have difficulty repaying their loans.

## Background
* I participated in the [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) kaggle competition during June of 2018 in order to complete my [final project](https://github.com/jamesdellinger/machine_learning_nanodegree_capstone_project) for Udacity's Machine Learning Engineer nanodegree. At this time I earned a public leaderboard score of `0.74111`.
* After finishing this project writeup, I continued to refine my algorithm over the next two months, and was ultimately able to achieve a final private leaderboard score of `0.79506` when the competition ended on August 29, 2018.
* This put my solo submission inside the top 8% and was good enough to earn me a bronze medal in the competition.
* My best performing kernel is [here on kaggle](https://www.kaggle.com/jamesdellinger/home-credit-putting-all-the-steps-together), and in the notebook just above.

## Competition Summary
* The goal of the [Home Credit Default Risk competition](https://www.kaggle.com/c/home-credit-default-risk) on Kaggle is the creation of a machine learning algorithm that is able to predict the likelihood that a loan applicant will make at least one late payment when repaying their loan. 
* The competition is sponsored by [Home Credit](http://www.homecredit.net), whose mission is to provide a positive and safe borrowing experience to groups of people that traditional, mainstream banks and financial institutions typically refuse to serve.

## Dependencies
* [requirements.txt](https://github.com/jamesdellinger/kaggle_home_credit_default_risk_competition/blob/master/requirements.txt)

* [environment.yml](https://github.com/jamesdellinger/kaggle_home_credit_default_risk_competition/blob/master/exploration.ipynb)
