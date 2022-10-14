# Ford GoBike System Data Exploration

## by Pacifique Clement Ndayisenga

## Dataset

This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset consists of 183412 rides taken in a bike-sharing system covering the greater San Francisco Bay area in the month of February of 2019. The dataset consists of 16 features that include trip duration in seconds, rider type and gender, the start and end timestamp of the trip and so on. This dataset can be downloaded [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)

## Summary of Findings

During my data exploration, I started by cleaning the dataset by removing all of the missing values, and convert the columns that have wrong data types like start and end time columns, etc. to appropriate data types. After the cleaning, my exploration led me to these key findings:

- The average trip duration is around 500 seconds
- Young riders spend more time in a trip than the older ones
- Customers spend more time in a trip than subscribers
- Weekend trips take longer compared to the ones taken during the week
- Female and other spend more time than male users

## Key Insights for Presentation

For the presentation, I focus on just the influence of the user age, user gender, user type and days of the week
on trip duration. I start by introducing the trip duration variable and generate it's histogram, followed by generating a new age column, and then plot the scatterplot of trip duration against age.

Afterwards, I introduce each of the categorical variables one by one. I use the box plots to plot user type, user gender and days of week against trip duration. I added titles, X labels, Y labels and used seaborn darkgrid style to polish more my plots.
