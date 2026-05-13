Project Dataset (Downloaded on 12-May): https://www.kaggle.com/datasets/danielgrijalvas/movies
Acknowledgements: This data was scraped from IMDb.

Note:
- The dataset has several missing values, including budget, gross and runtime -> Replaced with each columns' median value to avoid data type conflict during anlysis.
- 'released' column also has 'nan' value -> Replaced by value of 'year' column.
- 'released' column include values of different format -> correlation might not reflect correctly -> Use year_correct instead.

Insights:
Votes and budget have the highest correlation to gross earnings.
