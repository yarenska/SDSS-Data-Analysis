# Data-Science-Project

## Overview
In this project, I worked on Sloan Digital Sky Survey(SDSS) sky observation data. Normally it is possible to query the SDSS database server to retrieve newest data: </br>
http://skyserver.sdss.org/dr12/en/tools/search/sql.aspx </br></br>
But I couldn't find a package to handle this retrieval through Python(All of them are deprecated). So I decided to take data from Kaggle. You can find additional information about the data here:</br>
https://www.kaggle.com/lucidlenn/sloan-digital-sky-survey/home </br></br>
First, I analyzed the data and did the necessary transformation, normalization on it. Then, I did some visualization and implementation of supervised algorithms to classify given data whether it is a Star, Quasar or Galaxy using many classification algorithms such as KNN, Decision Tree, SVM and LightGBM. I checked the accuracies of them. I used these tools: pandas, matplotlib, sklearn, jupyter notebook. 
