# Analysis of Airbnb Data for Munich Octoberfest, Germany

This Repo includes an analysis of Airbnb data, especially for the octoberfest in Munich, Germany.
See my Kernel on Kaggle with the complete description of this analysis [here](https://www.kaggle.com/chocoschoch/analysis-of-airbnb-data-for-munich-octoberfest). 

### Table of Contents

- [Installation and Dependencies](#installation)
- [Motivation](#motivation)
- [File Descriptions](#description)
- [Results](#results)
- [Thanks](#thanks)

## Installation and Dependencies<a name="installation"></a>

The project is running with Python 3 and Jupyter Notebook.
After installing the following libraries, you can simply run the notebook in Jupyter. 
- Numpy
- Pandas
- matplotlib 
- Seaborn
- plotly
- Scikit-Learn

## Motivation for the project<a name="motivation"></a>

I am still trying to understand a bit more about the current real estate market in munich, especially the area around the octoberfest (theresienwiese). Therefore I think the Airbnb dataset for munich could be one possible source of information to gain usefull insights in the current situation.

**Specific questions to answer:**
1. What are the TOP 3 most expensive city districts for a stay in Munich in general?
2. What are the TOP 5 city districts in munich with the best distance-price-ratio for a stay near the are of the octoberfest?
3. What are the TOP 3 factors influence the price for a stay near the area of the octoberfest?


## File Descriptions<a name="description"></a>

`Analysis of Airbnb data from Muinch Germany.ipynb`:  
The main file is the Jupyter Notebook which contains all code needed to answer the questions.

`calendar.zip`:  
contains calendar.csv - data such as availability, dates, price for the upcoming year

`listings.zip`:  
contains listings.csv - every listing and has data such as bedrooms, bathrooms, host rating

`reviews.zip`:  
contains reviews.csv - unique id for each reviewer and detailed comments



## Results <a name="results"></a>

The derivation of the results can be found in the blog post [here](https://www.kaggle.com/chocoschoch/analysis-of-airbnb-data-for-munich-octoberfest).

In a nutshell:  

### Question 1: "What are the TOP 3 most expensive city districts for a stay in Munich in general?"  
**Answer:**  
The TOP 3 expensive districts in Munich (on average price) are   
- Altstadt-Lehel 
- Trudering-Riem
- Allach-Untermenzing

### Question 2: "What are the TOP 5 city districts in munich with the best distance-price-ratio for a stay near the area of the octoberfest?" 
**Answer:**   
The TOP 5 locations (district) with the best price-distance-ration are:  
- Sendling
- Sendling-Westpark
- Untergießing-Harlaching
- Laim
- Neuhausen-Nymphenburg

### Question 3: "What are the TOP 3 factors influence the price for a stay near the area of the octoberfest?"
**Answer:**
The TOP 3 factors of an apartment that have the greatest influence on the price are:
- Accommodates
- Bedrooms
- Extra people

This analysis was done as a project within the Udacity Data Science Nanodegree.   
Any kind of optimization is very welcome. I really appreciate any feedback to improvement.  

The underlying Jupyter Notebook to this evaluation can be found on GitHub (https://github.com/andreasschoch/airbnb-munich-octoberfest-analysis)


## Thanks, Authors, Acknowledgements <a name="thanks"></a>

The source for the data is Inside Airbnb which was imported to Kaggle [here](https://www.kaggle.com/chocoschoch/analysis-of-airbnb-data-for-munich-octoberfest) and is available under Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license. 
