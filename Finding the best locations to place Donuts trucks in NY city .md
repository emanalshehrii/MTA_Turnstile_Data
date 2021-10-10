## Finding the best locations to place Donuts trucks in NY city 

## Abstract

Donuts trucks is a new business company that needs to explore the areas with the highest traffic in New York City. 
This analysis will provide information regarding the most crowded subway stations. They need to distribute 3 trucks as a first step, three days weekly. So, by analyzing MTA Turnstile Data we can help them to explore where should these Dounts' trucks take location. Then, we will give recommendation regarding this analysis concerning where should Donuts trucks sit location and which days of the week are the best in each station. The insights were reached by cleaning the data, aggregating the data, and visualizing the data using different techniques.

## Goals
- Determining the top 10 busiest stations to explore where should these trucks take location.

- Discovering the days with the highest traffic per station to determine the suitable days of work.

## Algorithms

Exploratory data analysis and visualization tools were used to read, clean, and visualize the data. the first step after read the data is cleaning data by handling missing values, deleting duplicated rows and unnecessary columns such as desc, and division. Also, we added new columns (date-time, day-name), and strip all the names of columns to remove both the leading and trailing spaces. The second step of this project is to calculate the daily entries, daily exits, and daily traffic using the entries and exits columns. Finally, for data visualization, matplotlib and seaborn were used to create graphs.

## Data description

- The project used MTA turnstile data to analyze subway stations in New York City, the data is public and it is available on http://web.mta.info/developers/turnstile.html

- This project used a selected sample of four months From Jul. to Oct. of 2018 which contain 555156 rows and 12 columns
 
- The features that worked with are the name of stations with control area and unit, the number of entries and exits for each station, date, and time.

## Tools

- Jupyter notebook.
- The important tool used in this project is SQLAlchemy for connect to database. it is used to import all the datasets into SQL database and query the database in Python. 

- Also, Pandas were used in this project for data manipulation such as convert the date from object type to data-time type and reading CSV and SQl files. 

- For the data visualization, the project used matplotlib and seaborn libraries.


## Future work

#### Generating other insights by:
- focusing on time periods for the highest traffic stations to determine when the trucks opening and closing.

- Looking to expand our dataset.



```python

```
