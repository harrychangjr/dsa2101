# dsa2101
Assignments, Midterm and Group Project on Data Visualization using R Markdown - AY21/22 Semester 2

## Midterm
1. Explored College Dataset to investigate majors with high unemployment rates, as well as distribution between males and females across majors
2. Plotted customised correlation matrix using only base R to examine relationship between unemployment rate, percentage of women and annual median salary between STEM and non-STEM majors
3. Scraped rental prices dataset using API from data.gov.sg and performed exploratory data analysis
4. Investigated popularity of rentals by region through comparing total number of rental contracts signed
5. Exploratory data analysis on retail dataset in rds format

## Group Project
Spotify is one of the largest music streaming services in the world with over 406 million monthly active users (Spotify, 2022). In this project, we are looking to answer the following questions regarding the music hosted on the platform:  

1. What differentiates songs of different genres? For this question, we are interested in investigating the differences in songs of different genres. This could be useful in designing an algorithm to automatically classify songs to their genres which can be used in recommendation systems. This question seemed natural to ask since information like `genre` and numerical features of each song like `danceability`, `energy`, ... `duration_ms` is given in the dataset. 
2. How do the 4 seasons affect the number of songs produced in each period? This question explores the relationship between the number of songs produced and the season the songs are released in per genre. Thus, the parts of the dataset necessary are the playlist genre and track album release date.  From the track album release date, we extracted the month and year, to group into seasons e.g. all track albums released from March to May in all years are grouped under the season “Spring”; June to August under “Summer”; September to November under “Autumn”; and December to February under “Winter”.  We are interested in this question due to the conjecture that certain genres are associated with certain moods and festivals, thus will be more profitable/popular during certain seasons. For instance, winter could be a more melancholic season due to Christmas, thus more slow and moody songs. Therefore, there is an increase/decrease in release of each genre, depending of the different season(s).

To do so, we will be using the dataset on Spotify song metadata in 2020 obtained from [tidytuesday/data/2020/2020-01-21/](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-21).

Visualizations used: ridgeline faceted density plot, boxplot, line chart, faceted donut chart
