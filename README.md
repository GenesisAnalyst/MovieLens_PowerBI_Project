# MovieLens_PowerBI_Project
# Business Context: 
Movie Lens is a company on the internet and entertainment domain that provides an online database of information related to films, television series, and online streaming content, including cast, production crew, trivia, ratings, fan, and critical reviews. Every year, in collaboration with a guest curator, Movie Lens publishes their annual insights based on a theme, providing a comprehensive view of a topic. The company plans to bring out the "Movie Talkies: Classic" edition this year. The goal is to connect with viewers with strong movie preferences and promote classic movies to attract newer customers and expand their viewer base.


# Problem Statement:
To create the "Movie Talkies: Classic" edition, the challenge lies in effectively analyzing and presenting a wealth of information about movies from a bygone era. The core issue is understanding the characteristics of these classic movies, user interests, and the relationship between user demographics and movie ratings. Without clear visuals, it's difficult to identify patterns, draw meaningful conclusions, and engage the audience on a deeper level. The company hired me as a Data Analyst to create a report that provides a detailed analysis of the classic movies released till 2000. The dashboard should provide insights on the following questions:
1.	How many movies were released until 2000? How many distinct genres have come up till the year 2020?
2.	How many users are part of the Movie Lens community, and what is the gender diversity in this community?
3.	What are the genre preferences of different genders, highlighting user engagement?
4.	What's the average user rating for classic movies, reflecting overall reception? How does the distribution of film vary across different genres?
5.	What is the demographic distribution of the users across genders? Where do these users live?
6.	How do users across different age groups and professions engage with classic movies, revealing generational interests?
7.	Which classic movies and genres are top-rated? How do these ratings differ based on user age and occupation?
8.	Is there a link between user age and their ratings for classic movies, providing insights into age-related viewing habits? How do the average ratings vary over the years based on the genre considered?


# Overview Approach.
This report aims to analyze classic movies released until 2000 using Movie Lens data. By leveraging Power BI's data visualization capabilities, we will gain insights into user preferences, demographics, and engagement with classic films. This will help Movie Lens curate its "Movie Talkies: Classic" edition and connect with viewers effectively.


# Data Source.


* rating.csv: It contains information on ratings given by users of a particular movie.
* user_id: id assigned to every user.
* movie_id: id assigned to every movie released.
* rating: the rating given by the user.
* timestamp: Time recorded when the user gave a rating.
-------------------------------------------------------------------------------------
* movie.csv: The file contains information related to the movies and their genre.
* genre: genre of the movie - a movie can have multiple genres separated by a pipe.
* movie_id: id assigned to every movie released.
* movie_name: Title of the movie.
* year: Year of release of the movie.
------------------------------------------------------------------------------------- 
* user.csv: It contains information about the users who have rated the movies.
* user_id: id assigned to every user. 
* age: Age of the user.
* gender: Gender of the user (M: Male, F: Female).
* occupation: Occupation of the user.
* zipcode: Area code for the user's residence.




# Solution Approach.
# 1.	Data Cleaning and Transformation:
* •	Cleanse movie and user data for inconsistencies and missing values.
* •	Transform the data into a format suitable for Power BI analysis.
* •	Create calculated fields for user engagement metrics.

# 2.	Visualizations and Analysis:
 
![image](https://github.com/GenesisAnalyst/MovieLens_PowerBI_Project/assets/134435634/495e883d-4803-4233-bc18-c3fd038bafb4)


![image](https://github.com/GenesisAnalyst/MovieLens_PowerBI_Project/assets/134435634/ac6b4448-21e2-4c4f-a345-e5b7e9c9eb7f)


![image](https://github.com/GenesisAnalyst/MovieLens_PowerBI_Project/assets/134435634/17086d34-da7b-4c62-b84f-c64f9a1d9793)


![image](https://github.com/GenesisAnalyst/MovieLens_PowerBI_Project/assets/134435634/23c944af-d474-4602-921b-8c80fdd101c8)




