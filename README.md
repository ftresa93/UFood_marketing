# UFood_marketing Data Analysis Project

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [References](#references)

### Project Objective: 

UFood is a hypothetical lead food delivery app in Brazil, present in over a thousand cities. The Key Objectives of the project are:

1. Explore the data – don’t just plot means and counts. Provide insights, and define cause and effect. Provide a better understanding of the characteristic features of respondents;
2. Propose and describe a customer segmentation based on customers behaviors;
3. Visualize data and provide written reasoning behind discoveries;

Globally, the company had solid revenues and a healthy bottom line in the past 3 years, but the profit growth perspectives for the next 3 years are not promising. For this reason, several strategic initiatives are being considered to invert this situation. One is to improve the performance of marketing activities, with a special focus on marketing campaigns. The marketing department was pressured to spend its annual budget more wisely. Desirably, the success of these activities will prove the value of the approach and convince the more skeptical within the company.

### Data Sources:

The primary dataset used for the analysis "imdb_movies.csv" contains information about 4,803 movies. It provides a wide range of details about each movie, including budget, genres, production companies, release date, revenue, runtime, language, popularity, and more.

### Tools Used:

- Jupyter Notebook (Python) 

### Data Processing:

#### Data Import:

The "u_food_marketing.csv" dataset was imported into Python- Jupyter Notebook.

#### Data Cleaning and Preparation: 

- Removing Duplicates
- No null values were present in the dataset
- Standardizing Data types

#### Exploratory Data Analysis: 

- Propose and describe a customer segmentation based on customers' behaviors.
- Visualize data and provide written reasoning behind discoveries.
 
### Findings:

- Common Genres: Drama is the most common genre, with the highest number of movies.
- Budget and Revenue: Adventure has the highest average budget and revenue. It also leads in average profit.
- Popularity: Adventure is the most popular genre, followed by Science Fiction.
- Voting Average: Drama has the highest number of movies with a voting average of >=8.
- Vote Average Correlation: The best movies according to voting average do return high profit and revenue. The correlation between voting average and profit/revenue is positive but not very strong.
- Popularity Correlation: The best movies according to popularity return high profit and revenue, showing a strong positive correlation.
- Budget Correlation: Highly budgeted movies tend to return high revenue, profits and have high popularity, the correlation is positive yet not very strong.
  
### References:

1. Kaggle-[Movie Dataset: Budgets, Genres, Insights](https://www.kaggle.com/datasets/utkarshx27/movies-dataset)
2.  Analyst builder
