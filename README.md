This project is made using Python, Pandas and Jupyter Notebook....

After examining the raw dataset (the messy one) I found out that those are the steps I'm going to do in order to clean the dataset:
  1- Removed Duplicate Rows
  2- Dropped Unnecessary Columns
  3- Rename Columns(for better readability and consistency)
  4- Changed Column Data Types
  5- Standardized IDs
  6- Handled Missing Values (NaN)
     -Removed rows with critical missing data.
     -For non-critical fields, replaced NaN with "Unknown" where appropriate.
  7- Reindexed the dataset
  8- Reset the dataset index after row deletions.

the dataset represent movies and series from netflix with the columns :
  show_id, type, title,	director,	cast,	country, release_year,	rating,	duration,	genre, description

This dataset can help us to analyse:
  -The relashion between the genre and the rating
  -The relashion between the genre and the country
  -What are the best countries in this industry
  -The directors with most contents on Netflix
  -What does Netflix foucuses on more, movies or series
  and a lot of thing more ....

You can find the original dataset(the messy one) here:
https://www.kaggle.com/datasets/shivamb/netflix-shows
