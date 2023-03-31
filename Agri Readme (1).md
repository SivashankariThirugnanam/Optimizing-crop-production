# Agriculture -Optimizing Crop Production

The Project is about Agricultural optimization of crop production based on certain climatic conditions by using Statistical Analysis,
K-means clustering,Predictive Modelling on the dataset.
 
# Understand the problem statement of this project

Agriculture is the art and science of cultivating the soil, growing crops and raising livestock.

Agriculture is the process of producing food, fiber and many other desired products by the cultivation of certain plants.

Agriculture makes us less dependent on other foreign countries as it provides food and also provides income to farmers and revenue to the government.

You need to analyze these conditions and form clusters of crops which helps understand which group of crops require similar kinds of conditions to grow.

You will be using K-Means clustering for this and form clusters.

K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science. In this topic, we will learn what is K-means clustering algorithm, how the algorithm works, along with the Python implementation of k-means clustering.

Determines the best value for K center points or centroids by an iterative process. Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster.

After you analyze the different climatic conditions required for different crops, you will perform multi-class classification and will predict which crop can be grown with given climatic conditions.

# Overview

In this Jupyter notebook, we will perform Statistical Analysis,K-means clustering,Predictive Modelling on the Agriculture dataset which contains,

“N” represents the ratio of Nitrogen content in the soil.

“P” represents the ratio of Phosphorus content in the soil.

“K” represents the ratio of Potassium content in the soil.

“Temperature” represents the temperature in degrees celsius.

“Humidity” represents the relative humidity in Percentage. 

“Ph” represents the ph value of the soil.

“Rainfall” represents the rainfall in mm.

“label” column contains the names of different crops grown in these particular conditions.

The Dataset contains complete of 2200 rows and 8 columns.


# Importing the Libraries

#For Manipulations

import numpy as np
import pandas as pd

#For Data Visualizations

import matplotlib.pyplot as plt
import seaborn as sns
plt.style.use('fivethirtyeight')

#For Interactivity

import ipywidgets
from ipywidgets import interact

#Version of Jupyter Notebook  - v6.5.3

#Interface 

Statistical Programming Python -  3.9.7

# Analysis of the Project

Descriptive Analysis - Mean(),Sum(),Median().

Analysing statistical conditions -Distribution conditions, Intersting patterns.

K-mean clustering analysis -Optimum Number of Clusters within the Dataset by using Elbow method(Soft clustering and Hard clustering).


# Predictive Modelling

Prediction modelling done with Logistic Regression- Precision,recall,f1-score,support using Confusion matrix

# Conclusion

Some of the important key points in this project were:-

We learnt about the use of statistics in summarizing the major facts about the data. We got general information about the conditions to be taken care of while growing different crops. We learnt the use of ipywidgets to make the functions more interactive to the user. We learnt about clustering analysis and applied in the data to form clusters of crops. We learnt the difference between soft clustering and hard clustering. We learnt the importance of Data Visualization to find hidden patterns from the data. We learnt how to apply Logistic Regression to solve a real life problem. We also learnt about the evaluation metrics used for Classification problems.
