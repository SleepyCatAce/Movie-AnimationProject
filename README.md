# Movie-AnimationProject
My Data Taming and Prediction project looking at different movies. Data Taming and Prediction was the first R class that I had taken, so it's interesting to see how I've grown since then.

The dataset used for this report is the IMDB Movies Dataset from Kaggle which is a .csv file 
https://www.kaggle.com/datasets/ashishjangra27/imdb-movies-dataset
###THIS FILE IS TOO BIG TO UPLOAD, PLEASE DOWNLOAD IT YOURSELF FROM THIS LINK###

This dataset comes with 2 data types: Character and Numeric. To meet the character, numeric and date
requirements, the character column “year” was transformed to a date. However, due to the nature of the
column, a lot of the years were defaulted to NA, so the year was not used in any analysis.

The dataset originally comes with 14 variables. id, name, year, rating, certificate, duration, genre, votes,
gross_income, directors_id, directors_name, stars_id, stars_name and description
Cleaning this dataset included the following.
1 - making columns based on if the movie or tv show falls under the romance genre 
2 - Removing items that are 0 minutes long, earn 0 gross income and removing the
id columns and the description 
3 - turn the dataset into two datasets (movies and tv shows) based on the certificate 
4 - transformed the year column to a date 
5 - the column rating is transformed to numeric values
6 - merge the movie and tv show datasets to show whether each item is a movie or tv show
