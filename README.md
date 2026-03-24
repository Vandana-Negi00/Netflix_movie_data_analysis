
# Netflix Movie Data Analysis using Python

## Description

This project performs exploratory data analysis (EDA) on a movie dataset to identify patterns related to genres, popularity, ratings, and release trends. The analysis focuses on extracting meaningful insights about movie performance and audience engagement.

---

## Problem Statement

The objective of this project is to analyze movie data and uncover insights about genre distribution, popularity, ratings, and yearly trends. The goal is to understand factors that influence movie success and audience preferences.

---

## Objectives

* Identify the most frequent movie genres
* Analyze rating categories based on vote counts
* Determine the most and least popular movies
* Examine relationships between popularity, genre, and ratings
* Identify the year with the highest number of movie releases
* Analyze trends in movie production over time

---

## Dataset Overview

* Total Records: 9,837
* Total Features: 9

The dataset includes information such as movie title, release date, popularity, vote count, rating, language, and genre.

---

## Data Dictionary

| Column Name       | Description                    |
| ----------------- | ------------------------------ |
| Release_Date      | Date of movie release          |
| Title             | Name of the movie              |
| Overview          | Short description of the movie |
| Popularity        | Popularity score               |
| Vote_Count        | Total number of votes          |
| Vote_Average      | Average rating                 |
| Original_Language | Language of the movie          |
| Genre             | Movie category                 |
| Poster_Url        | Link to the poster             |

---

## Data Preprocessing

* Converted Release_Date to datetime format
* Extracted Year from release date
* Split and transformed Genre column for analysis
* Created Rating_Category using binning
* Handled missing and inconsistent values

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Key Insights

* Drama is the most frequent genre with 3,744 entries, followed by Comedy with 3,041
* The Average rating category has the highest total votes with 3,024,983
* Spider-Man: No Way Home (2021) has the highest popularity score of 5983.954 with 8,940 votes and belongs to Action, Adventure, and Science Fiction genres
* Movies with the lowest popularity include The United States vs. Billie Holiday (2021) with a popularity of 13.355 and The Traps (1984) with a popularity of 14.354
* The year 2020 has the highest number of movie releases with a total of 1,638

---

## Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Data Visualization
6. Conclusion

---

## Conclusion

The analysis reveals that drama is the most dominant genre, while average-rated movies receive the highest audience engagement. The study also shows that recent years, particularly 2020, experienced a peak in movie production.
