# IMDb Movie Data Analysis (2000 - 2020)

#### Author: Ziqi (Katie) Chen

## Introduction

Many movies with huge budgets often bring huge profits, like Avatar, Star Wars, The Avengers. There are low-budget movies that also made millions, such as Paranormal Activity, The Blair Witch Project, Juno etc. It seems like Action and Adventure movies are most profitable as they often have large budgets for famous casts and special effects. However, these types of movies may not have the most return on investment. To study further, I analyzed IMDb movie data between 2000 and 2020 using Exploratory Data Analysis and Visualization. In particular, I did my analysis on answering the following questions:

* What genres are most popular each year? Do people like certain genres over time?
* What type of movie receive higher rating?
* Which genre is most profitable? What genres are associated with higher budgets?
* Which genre has the biggest return on investment (ROI)?

## Data Source

There are two datasets that I used in this analysis:
* IMDb movie data (scraped from [IMDb website](https://www.imdb.com/))
* Kaggle movie data (csv file from [Kaggle Movie Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset))

The movie data that I scraped from IMDb was filtered by year from 2000 to 2020. Each year I picked 400 movies by descending voting count, so there are total 8400 movies in the dataset. However, there is no budget information when the data was scraped from the IMDb website. I then used the budget information from Kaggle movie data and merged it to the IMDb dataset so that I had all important information.

These are columns from the dataset that I want:
* IMDb id
* Movie title
* Released year
* Duration (min)
* Genre (one movie can have multiple genres)
* Rating (out of 10)
* Vote Count
* Budget
* Domestic gross
* Worldwide gross

## Data Analysis

After data cleaning, the dataset looks like this:

![](image/dataframe.png)

### What genre are most popular?

![](image/movie_count.png)

## Conclusions
