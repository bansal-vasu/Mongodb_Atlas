# Mongodb_Atlas

This repository contains Visulizations created using MongoDB Atlas.

JSON Dataset used has been Attached

## Attirbutes Decription

**ID** - ID of the movie

**Name** - Name of the movie

**Oscar** - Year in which the movie received the oscar

**released_year** - Year when the movie was released

**poster** - Link to the poster of the movie

**rating** - Rating of the movie ( From R, Passed, Not Rated, PG-13, PG, G, Approved, GP)

**duration** - Duration of the movie in minutes

**genre** - Genre of the movie

**summary** - Summary of the movie plot

**directors** - Names of the movie director(s)

**stars** - Names of the movie star(s)

## Dashboard

![Oscar_Movies_Vasu (1)](https://github.com/user-attachments/assets/fbf07a4d-b8f3-43f9-96d1-88560ef9eb71)

**Graph Description-**

**Movies per Genre-** This chart illustrates the distribution of movies across different genre combinations in the dataset.
The visualization presents a comprehensive breakdown of movie counts by genre combinations, with genres listed on the y-axis and the count of movies (count_id) on the x-axis, ranging from 0 to 10 movies.
Key observations:

Pure "Drama" emerges as the most prevalent genre, with approximately 10 movies
Mixed genres involving Drama are notably common throughout the dataset:

"Crime, Drama, Thriller" ranks second with around 6-7 movies
"Adventure, Biography, Drama" follows with roughly 5 movies
"Drama, Family, Musical" shows approximately 4 movies

Notable patterns:

Drama appears as a component in most of the genre combinations, suggesting its fundamental role in storytelling
Genre hybridization is common, with most categories being combinations of 2-3 genres
Musical, Crime, and Biography frequently appear as secondary or tertiary genres
The distribution shows a clear tapering effect, with fewer movies in the more specific genre combinations

This demonstrates the prominence of Drama and its various combinations with other genres in the dataset.

**Rating Distribution-** This chart displays the distribution of movie ratings in a dataset.
The visualization presents a frequency distribution of movie ratings, showing the count of movies assigned to each rating category. The ratings are displayed on the y-axis, while the count of movies (count_id) is shown on the x-axis, extending from 0 to 35 movies.
Key observations from the distribution:

R-rated movies dominate the dataset with approximately 32-33 movies
"Passed" and "Not Rated" categories form the second tier, each containing roughly 12-15 movies
PG and PG-13 ratings show similar frequencies, with about 10-12 movies each
G-rated and "Approved" movies appear less frequently, with roughly 7-8 movies each
GP-rated movies are the least common, with only about 2 movies in this category

The visualization demonstrates the prevalence of R-rated content in this particular dataset, while also highlighting the relatively balanced distribution among middle-tier ratings (Passed, Not Rated, PG, and PG-13) and the lower representation of family-friendly ratings like G and GP.

**Movie Duration Trends-** This graph represents the duration of the movies in the dataset. It is clearly visible that most movies have a duration of 120 minutes. As the duration increases or decreases from this number the number of movies take a substantial drop indicating that most viewers prefer the movie duration of around 120 minutes and it is well described by most movie makers as the "Sweet Spot" of movie durations.

The duration 120 minutes has the highest count, followed by 130 minutes and 122 minutes.
Other durations like 152 minutes, 105 minutes, and 161 minutes also appear frequently.
There is a significant drop in the counts as the durations deviate from the peak values, such as 228 minutes and 94 minutes showing lower frequencies.
This chart highlights common durations that filmmakers target.

