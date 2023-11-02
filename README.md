<h1>Python web scraping project using IMDb</h1>

Scraping IMDb's top 20 movies list, the goal is to extract information about the top-rated movies, including their titles, release years, and ratings. IMDb is a popular online database of movies, TV shows, and celebrities, and it provides a list of the top-rated movies based on user and critic reviews. Web scraping allows you to automate the process of collecting this data instead of manually copying and pasting it.
<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/7c793f9c-f634-4ff0-ba0b-9787eb942870" alt="Image" width="900">
</p>

## :clipboard: Information Source

The information is used in this analysis is derived from the following 

```
URL: https://www.imdb.com/list/ls576754431/
URL: https://www.imdb.com/title/tt10366206/reviews
```
## :page_facing_up: Data Content

The project involves web scraping, data cleaning, analysis, and visualization data, the following information are :
- IMDb Movie Details Scraper
- IMDb Movie Review Sentiment Analysis
- IMDb Movie Review Sentiment Analysis with Visualization
- IMDb List Image Downloader
- Top 15 Movies by Rating Visualization
- Movie Rating statistics Analysis with Visualization
- Distribution of Movie Genres Analysis with Visualization

## :cinema: IMDb Movie Details Scraper

The Python script is designed to scrape movie details from a specific IMDb list. It extracts information about movies, including their names, release years, runtimes, ratings, metascores (if available), and genres. 

### The script populates several lists with movie details:

- movie_names: A list of movie names.
- :calendar: movie_years: A list of movie release years.
- :watch: movie_times: A list of movie runtimes.
- :star: movie_ratings: A list of movie ratings.
- movie_metascores: A list of movie metascores (if available).
- movie_genres: A list of movie genres.

## :cinema: IMDb Movie Review Sentiment :chart_with_upwards_trend: Analysis

The Python script scrapes movie reviews from IMDb and performs sentiment analysis to classify them as positive or negative. It uses the BeautifulSoup library for web scraping and the TextBlob library for sentiment analysis.

## :cinema: IMDb Movie Review Sentiment Analysis with :bar_chart: Visualization

The Python script scrapes movie reviews from IMDb, performs sentiment analysis using TextBlob, and visualizes the results using a bar chart. It classifies reviews as positive or negative based on a predefined sentiment polarity threshold.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/c9e8f81b-8c33-4ae8-b927-016a48fc1ec3">
</p>

## :cinema: IMDb List Image Downloader

The Python script scrapes and downloads images from an IMDb list. It sends an HTTP GET request to the IMDb list URL, parses the HTML content to find image elements with the "loadlate" class, and then proceeds to download and save these images to a specified directory.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/21a34171-9b38-4acf-91e4-b902ea82923f"alt="Image" width="900">
</p>

## :cinema: Top 15 Movies by Rating Visualization :bar_chart:

The Python script generates a horizontal bar chart to display the top 15 movies with the highest ratings. It uses a DataFrame to store movie data, sorts the data by rating, and then creates a visual representation of the top-rated movies.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/fde21cb5-31c8-4da3-81d4-9106c4314c2d">
</p>

## :cinema: Movie Rating statistics Analysis with Visualization :bar_chart:

In this analysis, we delve into the distribution of movie ratings for a set of movies. We explore the dataset, calculate key statistics, and visualize the distribution to gain insights into how these movies are rated. The dataset consists of movie ratings on a scale of 1 to 10, and our goal is to understand the central tendencies and spread of these ratings.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/4d76097f-e56c-414b-9728-085573d18cf9">
</p>

## :cinema: Distribution of Movie Genres Analysis with Visualization :bar_chart:

In this analysis, we explore the distribution of movie genres within a dataset of movies. Our goal is to visualize the prevalence of different genres in the dataset, providing insights into the diversity of movie categories. The dataset includes a list of movie titles, each associated with one or more genres.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/1648651a-c023-4d0f-8d2c-a997e8e8cc83">
</p>

## Conclusion

the Python scripts provided in this project are designed for various tasks related to movie data, including web scraping, sentiment analysis, image downloading, and statistical analysis of movie ratings. These scripts are versatile and can be adapted for specific use cases or integrated into larger projects. They demonstrate the use of libraries such as requests, beautifulsoup4, pandas, textblob, and matplotlib to perform a range of data-related tasks.
