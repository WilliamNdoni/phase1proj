# AFFLUENT FILMS AT BOX OFFICE : CASE STUDY MICROSOFT

## Introduction

Microsoft is  a technology corporation best known for software products such as Windows operating system. The company would like to create a movie studio due to the trending original video creation. In order to do this,the company needs to know the type of films that they should create. 

This project will extract the relevant data and provide a better insight on filming by providing meaningfull visualizations. It will also recommend on the type of films the head of Microsoft's new movie studio should venture into.The recommendation of films will be based on their rating and profits gained. The project will also help determine the most appropriate budget for filming and the most appropirate duration of films.
## Problem statement

In order to begin making films the company needs to know the type of films it needs to focus. There are several genres in the filming industry. This project helps the head of Microsoft's new movie studio decide on what films to create.
## Main objective
- Identify the films the head of Microsoft's new movie studio should start creating.

## Specific objectives
- Identify the films with the highest profits.
- Identify the most appropriate runtime (duration) of films to be created.
- Identify which films are highly rated.
- Identify the budget that should be allocated to film making.
## Notebook structure
1. Business understanding
2. Data understanding
3. Data preparation :
                  - Importing the relevant libraries
                  - Loading and exploring the datasets
                  - Checking for missing values and duplicates
                  - Checking for placeholders
                  - Note on outliers
4. Data analysis :
                - Determining which films had the highest rating on IMDb
                - Determinig which films have the highest profits
                - Investigating the relationship between budget and profit in filming
                - Determining the most appropriate duration (runtime_minutes) of films          
5. Conclusions.
6. Recommendations.

## Data understanding

The data used in this project was extracted from [IMDb](https://www.imdb.com/) ,[Box Office Mojo](https://www.boxofficemojo.com/) and [The Numbers](https://www.the-numbers.com/)
The dataset from Box Office Mojo contains the gross income of each movie,both domestic and foreign and the year it was released. This helps in determining the income generated from each movie. 

The IMDb website contained multiple datasets. The following datasets were extracted:
- title and ratings dataset : This dataset contains the code names of movies their rating and number of people who voted. It can be of use to determine whether a certain film was popular(loved) or hated.

- title and basics dataset : This dataset contains the names and code names of movies and their genres. 

The dataset extracted from [The Numbers](https://www.the-numbers.com/) website contains the names of movies and their associated budgets as well as the domestic and worldwide gross.This dataset will help determine losses associated with each film as well as the profits.

The project will use these datasets to come up with insights and relevant recommendations.

## Conclusions
- Films related to adventure have the highest profits with the film containing action,adventure and sci-fi getting the highest profits.
- Considering votes of above one thousand,documentary related films have the highest ratings.The film containing animation,documentary,mystery had the highest average rating.
- The most appropriate length (runtime) of films should be around 93 minutes.
- Most films having a budget of above 220 million dollars record profits higher than those having a lower budget.

## Recommendations

- The head of Microsoft's new movie studio should focus on adventure related films to realize more profits. A film containing action,adventure and sci-fi (science_fiction) is the most appropriate for this purpose.
- The head of Microsoft's new movie studio should create films that have a runtime minutes of around 93 minutes.
- If possible,the head of Microsoft's new movie studio should ensure the budget of films are above 220 million in order to increase the chances of getting higher profits.
- The head of Microsoft's new movie studio should focus on films related to documentaries to gain higher film ratings specifically,films containing animation,documentary,mystery which had the highest rating.