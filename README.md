# alone_project_2024
Project status - Complete

# Project objective
The primary objective of this project is to delve into the extensive dataset of the "Alone" TV show to uncover factors that may provide insights into the survival times of contestants. By analyzing variables such as contestant background, survival tools, environmental conditions, and the strategies employed, we aim to identify patterns and correlations that could predict the length of time a contestant might last in the wilderness.  

The critical question: *What are the key factors that significantly influence the survival duration of contestants on the 'Alone' TV show, and how can these insights inform both survival strategy optimization and viewer understanding of wilderness survival skills?*

# Methods

General
- Head
- Columns
- Count

Cleaning 
- Drop na values
- Fill na
- Nunique

Tranformation
- Merge
- Groupby
- Sort values
  
Exploratory Data Analysis (EDA)
  - Aggregating (Mean, Median, Standard Deviation)  
  - Correlation
  - Mapping

  
# Technologies

- Matplotlib
- Numpy
- Pandas
- Python
- Scipy
- Seaborn
- Tableau


# Overview
The Alone TV Show Database is an expansive resource designed for fans, researchers, and enthusiasts of the hit survival series "Alone." This database collects and organizes detailed information about each season, contestant, survival techniques, and the unique challenges faced by participants as they navigate wilderness survival solo. Aimed at providing a comprehensive look into the series' rich history, the database serves as a central hub for episode summaries, contestant strategies, and survival outcomes.

The 4 dataframes:

1. Survivalists (df_survivalists): Details like contestants name, age, gender, profession, amount of days lasted, season they participated in and reason they quit.
2. Loadouts (df_loadouts): A list of the 10 items each contestant is allowed to bring for their survival.
3. Seasons (df_seasons): A list of each season, location, country, latitude, longitude and amount of contestants per season.
4. Episodes (df_episodes): A list of each episode, the season, episode number, air date, title, a quote and its author and the ratings.


# Steps
For the project, the dataframes needed to be cleaned and tranformed to make the best use of them

- df_armed: Merged the cleaned survivalist dataframe with the clean loadout dataframe on name and season to make our initial analysis. 

- analysis_df_clean: Utilised one hot encoding to transform each item in a row into its own column to make a statistical analysis for each item the contestants took using (mean, median, standard deviation and correlation)

- To get a better insight into constestant background and survival rate, we mapped all the professions into categories and plotted their survival rate per category to see which would benefit the most.

- For an insight into demographicss we took a look into their gender and and age to find any particular groups which might be better at survival. 





# Conclusion


# Contact
- www.linkedin.com/in/bryanortegaleon
- Github: baonline
