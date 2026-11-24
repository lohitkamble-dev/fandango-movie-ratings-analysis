# Is Fandango Inflating Movie Ratings?

Exploratory data analysis comparing Fandango's displayed star ratings with Rotten Tomatoes, Metacritic and IMDb, recreating the FiveThirtyEight analysis "Be Suspicious Of Online Movie Ratings, Especially Fandango's".

## Key findings
- Fandango's displayed stars are never lower than its actual ratings, and are usually rounded up by 0.1 to 0.5 stars.
- Fandango's ratings sit mostly between 3 and 5 stars, while Rotten Tomatoes critic scores cover the full range.
- Example: *Taken 3* showed 4.5 stars on Fandango, against an average of about 1.86 across five other rating sources.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn

## Data
[Be Suspicious Of Online Movie Ratings (Kaggle)](https://www.kaggle.com/datasets/mikhail1681/be-suspicious-of-online-movie-ratings)

## How to run
Open `fandango-movie-ratings-analysis.ipynb` in Jupyter, Colab or Kaggle. Update the CSV paths in the loading cells if you run it outside Kaggle.
