+++
categories = ["articles"]
comments = false
date = "2016-10-02T22:55:05-04:00"
draft = false
slug = ""
tags = ["projects"]
title = "Projects"

showpagemeta = true
+++

## Data Science

<br/>

**Pass Prediction In Soccer**: [[Blog]](https://medium.com/@gorafle/predicting-pass-recipients-in-soccer-a3acf0fa2652) | [[Code]](https://github.com/gfleetwood/pass-prediction)

Description: Analysis of data for the [Football Pass Prediction Challenge of the 5th Workshop on Machine Learning and Data Mining for Sports Analytics](https://github.com/JanVanHaaren/mlsa18-pass-prediction). It consisted of mostly of player location data for over 12,000 passes from Belgian soccer. The stated goal was to predict the recipient of a pass.

Summary: The main pipeline involved feature engineering to create a feature for distance, another for the product of x-y coordinates, scaling numeric features, and dummying the sole categorical column. A 5-fold cross validated untuned Logistic Regression model with a 23% accuracy score compared to a naive baseline of 5.6%.

**Classifying Hate Speech**: [[Blog]](https://www.opendatascience.com/blog/identifying-hate-speech/) | [[Code]](https://github.com/gfleetwood/crowd-flower-hate-speech)

Description: Identifying hate speech is an important task on the internet. I used scikit-learn and the nltk package to build a hate speech classifier using Twitter data from CrowdFlower.

Summary: The final model utilized the Random Forest Classifier and achieved 76% accuracy on unseen data, a 26% increase over the baseline accuracy of 50%. I productionized the model as an app which allows a user to submit text to be classified. The app is no longer currently deployed.

## Software

**cantor**: [[Site]](https://cantor.bubbleapps.io/)

Description: A website to follow GitHub organizations. Users are notified whenever new repositories are created. The front end uses a no code platform called Bubble to take care of user and database management. The back end uses Python for processing data, updating data, and sending emails.

**handyman**: [[Code]](https://github.com/gfleetwood/handyman)

Description: A collection of personal Python Data Science scripts. 

**sansor**: [[Code]](https://github.com/gfleetwood/sansor)

Description: A collection of personal R Data Science scripts.

**ODSC Meetup Map**: [[App]](https://gfleetwood.shinyapps.io/odsc_meetup_map/)[[Code]](https://github.com/OpenDataScienceConference/meetup-map)

Description: An interactive app made in R which shows the Open Data Science Conference's (ODSC) meetups around the world. Data is scraped from the Meetup.com using rvest, and displayed as a map via the leaflet library. The flexdashboard library provides the layout.
