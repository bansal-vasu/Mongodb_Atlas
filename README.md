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

**Movies per Genre Chart-** This chart illustrates the distribution of movies across different genre combinations in the dataset.
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

**Rating Distribution Chart-** This chart displays the distribution of movie ratings in a dataset.
The visualization presents a frequency distribution of movie ratings, showing the count of movies assigned to each rating category. The ratings are displayed on the y-axis, while the count of movies (count_id) is shown on the x-axis, extending from 0 to 35 movies.
Key observations from the distribution:

R-rated movies dominate the dataset with approximately 32-33 movies
"Passed" and "Not Rated" categories form the second tier, each containing roughly 12-15 movies
PG and PG-13 ratings show similar frequencies, with about 10-12 movies each
G-rated and "Approved" movies appear less frequently, with roughly 7-8 movies each
GP-rated movies are the least common, with only about 2 movies in this category

The visualization demonstrates the prevalence of R-rated content in this particular dataset, while also highlighting the relatively balanced distribution among middle-tier ratings (Passed, Not Rated, PG, and PG-13) and the lower representation of family-friendly ratings like G and GP.

**Movie Duration Trends Chart-** This graph represents the duration of the movies in the dataset. It is clearly visible that most movies have a duration of 120 minutes. As the duration increases or decreases from this number the number of movies take a substantial drop indicating that most viewers prefer the movie duration of around 120 minutes and it is well described by most movie makers as the "Sweet Spot" of movie durations.

The duration 120 minutes has the highest count, followed by 130 minutes and 122 minutes.
Other durations like 152 minutes, 105 minutes, and 161 minutes also appear frequently.
There is a significant drop in the counts as the durations deviate from the peak values, such as 228 minutes and 94 minutes showing lower frequencies.
This chart highlights common durations that filmmakers target.

**Year-wise trends Chart-** This chart illustrates the temporal distribution of awarded movies across different decades from the 1920s to the 2020s.
The visualization presents the number of awarded movies per decade, with time periods on the y-axis and the count of movies (count_id) on the x-axis, ranging from 0 to 10. The data is represented using consistent green horizontal bars.
Key findings from the year-wise distribution:

Earlier Period (1920-1930):
Shows notably fewer awards, with approximately 3 movies
Represents the initial phase of the awards system

Consistent Pattern (1930-2020):
All decades from 1930 onwards show remarkably consistent numbers
Each decade maintains approximately 10 awarded movies
This consistency spans nine consecutive decades

Notable observations:

There is a clear establishment of a standardized award frequency after the 1930s
The initial decade (1920-1930) shows lower numbers, likely reflecting the early development of the awards system
The consistency in numbers across later decades suggests:

A well-established awards protocol
Stable selection criteria
Consistent recognition patterns in the film industry

The visualization demonstrates the evolution and subsequent standardization of movie awards over a century. The stark contrast between the first decade and the subsequent periods highlights the maturation of the awards system.
This temporal analysis provides valuable insights into the historical development and stability of the awards process, showing how it evolved from its inception to become a regularized institution in the film industry.

**Star Appearances Chart-** This chart visualizes the frequency of star appearances in Oscar-winning films within the dataset.
The visualization presents the distribution of actor appearances, with actor names on the y-axis and their appearance count (count_id) on the x-axis, ranging from 0 to 2.8. The data is represented using blue horizontal bars.
Key observations from the star appearances:

Dustin Hoffman leads the cast frequency with approximately 2.8 appearances
Herbert Mundin and Sidney Poitier follow with roughly 2.4 appearances each
Barbara O'Neil and Susannah York show similar frequencies with about 2 appearances
The remaining actors (Esmond Knight through Alex R. Hibbert) demonstrate a gradual decrease in appearances, ranging from approximately 1.6 to 0.8 appearances

The distribution shows three distinct tiers:

Top tier (2.4-2.8 appearances): Hoffman, Mundin, and Poitier
Middle tier (1.6-2.0 appearances): O'Neil, York, and Knight
Lower tier (0.8-1.6 appearances): Remaining actors including Roberts, Harris, Livingston, DeVito, and Hibbert

**Liked Movies Chart-** The word cloud presents the most liked movie genres with size-based emphasis on frequency and popularity. 

Key observations:
"Drama" dominates as the central and largest term, indicating its overwhelming presence
Various genre combinations radiate from the center, showing common hybrid patterns:

Drama-Western combinations
Comedy-Drama pairings
Adventure-Drama-Fantasy
Crime-Drama variations

The visualization effectively demonstrates how Drama serves as a foundational genre that frequently combines with other genres

**Genre Split Chart-** The donut chart provides a quantitative breakdown of Oscar wins by genre combinations. 

Notable patterns:
Pure Drama (green) occupies the largest segment
Biography-Drama-History (blue) forms the second largest category
Drama-Romance-War (yellow) represents another significant portion
The remaining segments show various Drama-hybrid combinations including:

Crime-Drama-Thriller
Drama-War
Comedy-Drama combinations
Biography-based variations

Synthesis of Both Visualizations:
The complementary visualizations reveal several key insights:

Drama's Dominance: Both visualizations consistently show Drama as the predominant genre
Genre Hybridization: Most successful films combine multiple genres, with Drama as a common element
Oscar Recognition: The donut chart specifically shows how certain genre combinations are more likely to receive Oscar recognition
Diversity in Storytelling: Despite Drama's dominance, there's considerable variety in how it's combined with other genres

This comprehensive genre analysis demonstrates the film industry's tendency to blend different storytelling elements while maintaining dramatic components as a core feature of award-winning and popular films.\

**Count of Osccar Wins Chart-** The x-axis represents the names of directors, such as William Wyler, Billy Wilder, Leo McCarey, and others.
The y-axis, labeled as "count(_id)", represents the number of Oscars won by each director, with values ranging from 0 to 3.
William Wyler has the highest count of Oscars, with close to 3 wins.
Billy Wilder follows with slightly less than 2 wins.
The remaining directors, such as Leo McCarey, Cecil B. DeMille, and others, have counts closer to 1 or less.
This chart highlights the most awarded directors in the dataset and their relative success in winning Oscars.
