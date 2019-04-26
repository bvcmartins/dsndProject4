# Airbnb: Boston and Seattle

Blog Post and project 4 for Udacity's Data Scientist Nanodegree

## Overview

This project is available as a [blog post](https://bvcmartins.github.io/jekyll/update/2019/04/23/airbnb.html)

Airbnb, through Kaggle, provided us with a dataset covering all activity
in Boston and Seattle for one year. Based on this information we asked the
following business questions:

1. How is property occupation along the year? (easy one for warming up)
2. For how long a property is occupied and how much owners earn?
3. Can we determine what are the main predictors for property prices?
4. What are the characteristics of the busiest properties?
5. What are the most popular neighbourhoods? Can we understand why they are popular?

The dataset was explored and the questions were solved in the notebook 
airbnb_project.ipynb. 

## Methods

We used supervised learning methods from Scikit-learn
We used Pandas and Scikit-Learn for the analysis. The
following learning methods were used:

- AdaBoost
- PCA
- K-means 
- Latent Dirichlet Analysis

## Files

* airbnb_project.ipynb has the full solution
* airbnb_exploratory.ipynb was used for prototyping

## Conclusions

Here is what we learned:

* demand is high during spring and summer. For all months Boston is in higher demand than Seattle
* 25% of the properties in Boston are rented all year round. These properties are probably mostly rented to students
* price was predicted with around 60% accuracy. The most important features for price determination that are common to both cities are:
        * rooms are private
        * number of people that can be accommodated
        * number of bedrooms
* the most sought-after properties can be grouped by common fetures. Some of the most common features were:
        * rooms are private
        * number of bedrooms
        * cancellation policy is moderate
        * hosts have high reputation
* for Boston, the hottest neighbourhoods were Mission Hill, Allston, South Boston waterfron, South End, Beacon Hill. These places were in general close to universities, historic neighbourhoods or street shopping.
