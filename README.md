# MoMA_Analysis
This repo contains data analysis using data from the Museum of Modern Art (MoMA). 

- Data was pulled from [Kaggle](https://www.kaggle.com/momanyc/museum-collection) using the following files:
  - ✨Artists✨
    - Features the names, nationality, gender, birth_year, death_year and artist_id of artists
  - ✨Artworks✨
    - Features the artwork_id, title, artist_id (key that can be used to connect data between files), name, date, medium, dimensions, acquisition_date, credit, catalogue, department, classification, object_number, diameter, circumference, height, length, width, depth, weight and duration of artworks


## Notebooks

- ✨Data Cleaning✨
  - In this notebook dataframes are merged and standardizations are made to column headers and genders. Dates are also cleaned and standardized, with age at acquisition being deduced from available columns. 
- ✨Exploratory Data Analysis✨
  - Here cleaned data from the previous notebook is imported and brainstorming is done to produce the following questions:
    - Average num of artworks per artist 
    - Top 10 artists by # of art pieces 
    - Nationality with the highest frequency of art pieces 
    - Frequency of artwork by classification type 
    - Does the frequency of art per artist change based on the type of art? 
    - Number of artists by gender 
    - Largest artwork by weight 
    - Average age of living artists when artwork was acquired 
    - Does the average age change by type of art? 
    - Youngest artist to be featured in MoMA 
    - Number of pieces acquired by year 
    - Did the MoMa become more diverse over time, or was the number of artworks per artist consistent over time? 
    - How has the number of artworks per gender changed over the years?
  - Each question is answered in the notebook to help better understand the data
- ✨Data Modeling/Forecasting✨
  - Once again cleaned data is imported, but this time for the purpose of utilize linear regression to predict the number of artworks that will be collected in future years.
