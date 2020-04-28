# Telecom-Data-Analysis-Project

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Libraries used](#libraries-used)
* [Dataset used](#dataset-used)
* [Built on](#built-on)
* [Questions answered](#questions-answered)
* [Hypotheses Tested](#hypotheses-tested)
* [Ackowledgements](#ackowledgements)
* [Author](#author)


## About the Project 
Exploratory Data Analysis of a telecommuncation service provider's dataset to answer the problem statement given.</br></br>

Our objective in this project is to build a dashboard to understand the user's demographic characteristics based on their mobile usage, geolocation, and mobile device properties. Doing so will help developers, brand advertisers and other telecom companies around the world to pursue data-driven marketing efforts which are relevant to their users and catered to their preferences.

The python notebook __"Telecommunication Data Analysis Project"__ contains an initial EDA of data from the telecommuncation service provider and analyzes how different features impact the usage of the mobile network. 

It also suggests actionable insights as well as the features to concentrate on in order to give other telecom companies an insight into the market. We also offer more than one way to answer the problem statement and different approaches that companies could take as well as ways to interpret the data. 

## Libraries used 
* Numpy
* Pandas
* Matplotlib
* Seaborn
* mysql.connetector
* Basemap

```bash
import mysql.connector as mysql                                  # Used to pull data using sql
import pandas as pd                                              # For data manipulation and analysis
import numpy as np                                               # Implemennts milti-dimensional array and matrices operations
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
from mpl_toolkits.basemap import Basemap
import matplotlib.cm
from matplotlib.patches import Polygon
from matplotlib.collections import PatchCollection
from matplotlib.colors import Normalize
```

## Dataset used 
* __INSAID__ - Telecom Customer Behaviour

## Built with
* Jupyter Notebook

## Questions answered 
1. How are customers distributed statewise?
2. How are customers distributed city-wise?
3. What is the distribution of various phone brands between customers?
4. What is the gender distribution of customers?
5. What is the distribution of customers by age group?
6. Does the day of the week influence the usage of the network?
7. How does the hour of the day influence mobile usage?

## Hypotheses Tested
1. Mobile network usage is influenced by the time of day and the particular day of the week.
2. A customers gender does not influence the brand of phone they decide to use.

## Ackowledgements
* <a href='https://www.insaid.co/'>INSAID</a> - dataset

## Author - Sharan Sukesh



