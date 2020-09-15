# Analysis of Airbnb data

This Repo includes an analysis of Airbnb data from Munich, Germany. See my Kernel on Kaggle with the complete description of this analysis here.

Table of Contents
Installation and Dependencies
Motivation
File Descriptions
Results
Thanks
Installation and Dependencies
The project is running with Python 3 and Jupyter Notebook. After installing the following libraries, you can simply run the notebook in Jupyter.

Numpy
Pandas
matplotlib
Seaborn
plotly
Scikit-Learn
Motivation for the project
This analysis and the additional blog post was done as a project within the Udacity Data Science Nanodegree. I am a resident in Munich, Germany so I find that data particularly interesting. In order to get a better insight into Airbnb, especially in Munich, I am particularly interested in the answers to the following three questions:

When is the most expensive time of the year to visit Munich and how much does the price spike?
What are the most expensive neighbourhoods in Munich?
What factors influence the price most?
File Descriptions
Analysis of Airbnb data from Muinch Germany.ipynb:
The main file is the Jupyter Notebook which contains all code needed to answer the questions.

calendar.zip:
contains calendar.csv - data such as availability, dates, price for the upcoming year

listings.zip:
contains listings.csv - every listing and has data such as bedrooms, bathrooms, host rating

reviews.zip:
contains reviews.csv - unique id for each reviewer and detailed comments

Results
The derivation of the results can be found in the blog post here.

In a nutshell:
When is the most expensive time of the year to visit Munich and how much does the price spike?
The most expensive time of the year 2020 is between the end of September and the beginning of October during the Oktoberfest. The average price spikes around +15 USD.

What are the most expensive neighbourhoods in Munich?
The TOP 3 expensive neighbourhoods in Munich (in average) are: *Altstadt-Lehel *Trudering-Riem *Allach-Untermenzing

What factors influence the price most?
The TOP 5 factors of an apartment that have the greatest influence on the price are:

Accommodates
Entire home/ Apartment
Extra people
Number of reviews
Guest included
Thanks, Authors, Acknowledgements
The source for the data is Inside Airbnb which was imported to Kaggle here and is available under Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.
