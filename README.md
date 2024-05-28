Project Statement:

In the contemporary digital landscape, the vast array of movie options spanning diverse genres poses a significant challenge for users in efficiently discovering films that resonate with their preferences. In response to this challenge, the system is designed to analyse and present diverse insights into user preferences and movie ratings based on various demographic factors such as age, gender, occupation, and user-specific criteria. It encompasses functionalities like displaying the total number of movies rated over the years, providing IMDb and TMDb links for each movie title, finding highest and lowest-rated movies based on occupation and age, determining mean ratings by gender, and identifying genre preferences and ratings across different demographic segments. Additionally, the system allows for personalized searches based on keywords or movie titles, explores genre-specific ratings, and offers insights into the overall movie-watching patterns of users. Through these features, the system aims to enhance the user experience by delivering tailored movie recommendations and detailed statistical analyses of user preferences within the realm of cinematic entertainment.

Use cases:

•	Fetching the total number of movies rated over the years. 
•	Fetching the IMDb and TMDb links for each movie title.
•	Fetching the count of the total number of ratings for each movie title.
•	Finding the ratings for each movie title.
•	Finding the movie titles which got highest and lowest rating based on occupation.
•	Finding the titles which got highest rating based on age.
•	Finding the mean rating for each movie based on gender.
•	Finding the movies preferred by females but not by males.
•	Finding the movies preferred by males but not by females.
•	Finding the highest rated movies based on the UserID entered.
•	Finding the highest rated movies based on the occupation entered.
•	Finding the highest rated movies based on the gender entered.
•	Finding the highest rated movies based on the age (age group) entered.
•	Searching for a relevant movie information based on a keyword or movie title entered. 
•	Finding the number of movies per genre.
•	Finding the genres which got highest rating by males.
•	Finding the genres which got highest rating by females.
•	Finding the top 3 genres which got highest rating by ages groups.
•	Finding the top 3 genres which got highest rating based on occupation.
•	Finding the total and average ratings per genre.
•	Finding the ratings for musical genre movies.
•	Finding the ratings for musical genre based on gender.
•	Finding the ratings for musical genre based on age.
•	Finding the ratings for musical genre based on occupation.
•	Fetching the IMDb and TMDb links to musical genre movies.
•	Finding the genres based on average of ratings given by any particular user.
•	Finding the genres based on average of ratings by age (age group).
•	Finding the genres based on average of ratings given an occupation.
•	Finding the genres based on average of ratings given a gender.
•	Finding the movies based on average of ratings given a genre.
•	Finding the overall average rating of movies by female users.
•	Finding the overall average rating of movies by male users.
•	Finding the minimum, maximum and average rating for all users.
•	Finding the average rating of all genres given by each user.
•	Finding the total number of ratings per genre given by each user.
Importance/ Requirement:

1.	Dataset integration and information retrieval:
This is fundamental for the recommendation system as it involves integrating diverse datasets containing movie information, user information and preferences. Efficient information retrieval ensures that the system has access to a comprehensive set of data for accurate recommendations.
2.	Information fetch, reporting and recommendation:
This process involves gathering, analysing, and reporting on the information fetched from the datasets. It plays a crucial role in generating accurate recommendations based on user preferences and content attributes.
3.	User-guided fetch:
Allowing users to guide the information retrieval process by entering the age, genre, occupation, gender, etc to enhance the personalization of recommendations. User-guided fetch empowers users to express their preferences explicitly.
4.	Information presentation:
The significance of the presentation aspect in our work lies in its ability to transform intricate datasets into visually compelling and easily interpretable representations. These visual insights not only contribute to a deeper understanding of the movie landscape but also serve as valuable assets in steering the direction of content creation, platform enhancement, and strategic decision-making in the dynamic realm of entertainment. 
5.	Graphical User Interface (GUI):
A user-friendly GUI is essential for seamless interaction with the recommendation system. It enhances the overall user experience and accessibility.

Stakeholders:

1.	Content Providers: Stakeholders in this category include movie studios, production companies, music labels, and artists. Their involvement is critical as the success of the recommendation system can result in heightened viewership, increased downloads, and elevated sales for their content.
2.	 Platform Providers: Companies providing the platform or hosting the recommendation system, such as streaming services or digital platforms, are essential stakeholders. The success of the recommendation system may contribute to user retention and platform popularity.
3.	Users/Viewers: The primary stakeholders within this group are the users or viewers of the recommendation system. Their preferences, satisfaction, and engagement serve as pivotal factors for the system's effectiveness. Users derive benefit from tailored content suggestions that align seamlessly with their individual tastes.
4.	Customer Support Teams: Customer support teams are stakeholders, as they deal with user feedback, complaints, and inquiries related to the recommendation system. Addressing user concerns and improving user satisfaction is crucial for the system's success.
5.	Data Analysts: Professionals in this role play a key part in crafting and refining the recommendation algorithms. They engage in the analysis of user data, behaviour patterns, and metrics related to engagement, all aimed at the continual enhancement of recommendation accuracy.
6.	Data Scientists & Engineers: Responsibilities assigned to data scientists and engineers encompass the integration of diverse data sources, data cleaning processes, and the conceptualization of recommendation algorithms. Their work is instrumental in shaping the functionality and efficiency of the recommendation system.

Data acquisition:

The project has been done using MovieLens 1M Dataset (ml-1m) and MovieLens 25M Dataset (ml-25m). The file 'movies.dat', 'users.dat' and 'ratings.dat' are taken from the MovieLens 1M dataset(ml-1m). The file`links.csv' is taken from the MovieLens 25M dataset(ml-25m).
MovieLens 1M dataset : Stable benchmark dataset. These files contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.
MovieLens 25M dataset: Stable benchmark dataset. It contains 25000095 ratings and 1093360 tag applications across 62423 movies. These data were created by 162541 users between January 09, 1995 and November 21, 2019.
These datasets are publicly available for download at https://grouplens.org/datasets/movielens/

