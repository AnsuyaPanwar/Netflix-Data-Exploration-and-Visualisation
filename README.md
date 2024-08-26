# Netflix-Data-Exploration-and-Visualisation
## Problem Statement
Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.
Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries

## 1. ASK

## Questions:
1. Un-nesting the columns : Un-nest the columns those have cells with multiple comma separated values by creating multiple rows.
2. Handling null values : For categorical variables with null values, update those rows as unknown_column_name.
3. Find the counts of each categorical variable both using graphical and non-graphical analysis.
  * For Non-graphical Analysis:find the values counts of each category for the given column.
  * For graphical analysis: We can use a count plot to get the counts of each category.
4. Comparison of tv shows vs. movies.
  * Find the number of movies produced in each country and pick the top 10 countries.
  * Find the number of Tv-Shows produced in each country and pick the top 10 countries.
5. What is the best time to launch a TV show?
  * Find which is the best week to release the Tv-show or the movie. Do the analysis separately for Tv-shows and Movies.
  * Find which is the best month to release the Tv-show or the movie. Do the analysis separately for Tv-shows and Movies.
6. Analysis of actors/directors of different types of shows/movies.
  * Identify the top 10 directors who have appeared in most movies or TV shows.
  * Identify the top 10 directors who have appeared in most movies or TV shows.
7. Which genre movies are more popular or produced more?
8. Find After how many days the movie will be added to Netflix after the release of the movie (you can consider the recent past data)

## 2. PREPARE

## Data Storage:
The public dataset is completely available on the google drive platform where it stores and consolidates all available datasets for analysis. The specific individual datasets at hand can be obtained at this link below: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/000/940/original/netflix.csv

## 3. PROCESS

## Tools Used:
1. Google_Collab

## 4. ACT

### Insights Generation:

* The United States stands out as the leading producer of movies, with a significantly higher count compared to other countries.
* The United States emerges as the leading producer of TV shows, with a significantly higher count compared to other countries.
* Rajiv Chilaka and Suhas Kadav are prominent directors with 22 and 16 unique titles.
* Anupam Kher and Shah Rukh Khan are among the top actors in the dataset, with 43 and 35 unique titles, respectively.
* December and July have the highest numbers of TV shows added, with 266 and 262 respectively.
* December and July have the highest numbers of Movies added, with 565 and 550 respectively.
* in the last 30 years has been increasing at an extraordinary rate.

### Recommendations :
1. Netflix should try to increase the number of TV shows by reaching out to customers and understanding what is popular in order to
increase itʼs TV Shows viewership.
2. The number of movies released drastically went down in 2020. Netflix should partner with Production houses and ramp up the
production and making of movies as soon as possible.
3. Netflix should focus on genres Action & Adventure, Comedy, Documentaries and Dramas because they are the ones with most
viewership and will likely bring more profits for the company. 4.The most popular markets for the company are United States and India
however United States is vastly ahead of India in terms of number of users so, the company should try to penetrate deeper into Indian
market by providing local language content in a very personalized way to each state of India. In the US, it should look for genres where
there has not been much success and try to promote them as well.
4. Also, according to the data, the best time to release movies is between week 1 and week 15. As for the TV shows it is the month of
December and July.
