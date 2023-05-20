# recipe-rating
This is a project for DSC80 at UCSD

## Introduction
This project is about the recipes with ratings from the website food.com. The questions for this project is: What is the relationship between calories and average rating of recipes. There are 234429 rows in the dataset and the relevant columns to my questions are colories, average_rating_per_recipe and the description of these two columns are:

colories: colories of the recipes(#).

average_rating_per_recipes: the mean rating of the recipes.

## Cleaning and EDA(Exploratory Data Analysis)
1. I left merge two dataframe raw_recipes and raw_interactions.
2. filling np.nan to replace data that should be missing.
3. adding new columns: average_rating_per_recipe
4. extracting nutrition columns to the following new columns: calories, total fat, sugar, sodium, protein, saturated fat, carbohydrates.
5. dropping unnecessary columns: nutrition, contributor_id