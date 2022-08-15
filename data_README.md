# Overview of Data and Data Analysis
## Data Processing
Since our project focus is a big ambiguous, we decided to start our analysis by running sampled data through a simple model, with the goal being to get a visualization of how accidents might be grouped together. From this visualization, we could have a better understanding of what our story is and how it can be told. First though, the data had to be wrangled and cleaned.

We decided on accomplishing this task by using only one year's worth of data. The first step in the data wrangling process after accessing the raw data was indentifying what columns from which CSV's we wanted to keep. After loading and cleaning the files in python, the next step was merging the tables together. This became difficult because the indeces for the files were different. Although each accident had its own unique `ST_CASE` identifier, some of the tables also had `VEH_NO` and `PER_NO` multi-indexes.

In merging the tables, for each added column, we had to figure out how to merge it together. It generally fell into two categories: if any vehicle or person was a 'yes', then mark that factor as a yes for the whole accident; or a count of each instance of a factor in an accident. This method also naturally bucketed and encoded a couple columns, namely `BODY_TYP` and `ACC_TYPE`. Once this was done, the next step before running the data through a model was encoding and scaling.

In `exploratory_encoding.ipynb`, I started by identifying the columns and checking to see how many were already encoded, then I created buckets for `HARM_EV` and encoded the needed columns using pandas `get_dummies()` method. I dropped the location and year columns and scaled the dataframe using `StandardScaler()`. Finally I re-added `ST_CASE` to the scaled DataFrame as an identifier.
## Interpretation
A lot of the columns have number codes. An explanation of the number codes is in `Data_Columns.xls`