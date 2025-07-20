**📘 Phase 1: Simple Analysis (Beginner)**

1. List the first 10 movies with their genres.
2. Show all distinct genres in the dataset.
3. Find all movies that include “Comedy” in their genre.
4. Count how many movies belong to the ‘Action’ genre.
5. Find the average rating for the movie “Toy Story (1995)”.
6. List the top 5 highest-rated movies (by average rating), with their movie titles.
7. Count how many unique users have rated movies.
8. List all tags used by user ID 10.
9. Find all movies tagged with “sci-fi”.
10. Get the total number of ratings per movie, sorted by the most-rated movies.



**📗 Phase 2: Intermediate Analysis**

1. Join movies with their average ratings and show top 10 highest-rated movies with at least 100 ratings.
2. Display userId and number of tags they have added, sorted in descending order.
3. Using a CASE statement, classify movies as ‘Low’, ‘Medium’, or ‘High’ rated based on average rating.
4. Get the top 3 tags applied most frequently across all movies.
5. List the most relevant tag (highest relevance score) for each movie from the genome\_scores and genome\_tags tables.
6. List the top 5 users who rated the most number of movies.
7. Find movies that have not been rated by any user.
8. Using a CTE, find the average rating of each movie, and then filter for those with avg rating > 4.5.
9. Find the 5 most recently tagged movies (based on timestamp).
10. Use a window function to rank all movies by average rating within their genres.



**📕 Phase 3: Advanced Analysis**

1. Create a view that shows movie title, genre, average rating, and number of ratings.
2. Write a stored function that accepts a genre and returns the top 3 rated movies in that genre.
3. Create a temporary table to store movies with an average rating above 4.0 and use it in a JOIN.
4. Create a materialized view for movieId and its most relevant tag from genome\_scores.
5. Use EXPLAIN ANALYZE to evaluate the performance of a JOIN query between ratings and movies.
6. Find users who have rated both "Toy Story (1995)" and "Jumanji (1995)".
7. Normalize genres (currently pipe-separated) into a new table with one row per genre per movie (using string functions or unnest).
8. Generate a report using a recursive CTE: all tags that include the substring 'war' and related tagIds.
9. Create a user-defined function that returns the number of ratings a movie received above a given threshold.
10. Simulate a transaction: insert a new rating, then rollback to demonstrate ACID behavior.
