# etl-project

Group 3 Proposal

DATA SETS:
We’re using this population data from Kaggle: https://www.kaggle.com/utkarshxy/who-worldhealth-statistics-2020-complete?select=alcoholSubstanceAbuse.csv
And this US Real Estate Listings data from Kaggle: https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)_per_capita


EXTRACT:
We are going to download the first file as CSV (Arthur, 10 minutes)
Then we'll scrape the second data source and extract country and per capita GDP. (group, 45minutes)

CHALLENGE: 
We'll use pandas (read_csv) to import the first CSV file (Sonny, 20 minutes)
And use MongoDB to scrape the second datasource 


TRANSFORM
Once imported, we will join the tables on country (Dainty: 15 min)
Rename all columns based on the indication from the first datasource and drop the columns that we didn't find meaningful. 

LOAD
We'll do this as a group activity, and load the cleansed dataframe into Postgres database. (Mabel and group assists, 45 minutes)
