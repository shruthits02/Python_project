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
https://imdb-top-100-movies.p.rapidapi.com/
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
- IMDb Movie Rankings vs. Ratings
- Average IMDb Ratings Over the Years

## :cinema: IMDb Movie Details Scraper

The Python script is designed to scrape movie details from a specific IMDb list. It extracts information about movies, including their names, release years, runtimes, ratings, metascores (if available), and genres. 

### The script populates several lists with movie details:

- movie_names: A list of movie names.
- :calendar: movie_years: A list of movie release years.
- :watch: movie_times: A list of movie runtimes.
- :star: movie_ratings: A list of movie ratings.
- movie_metascores: A list of movie metascores (if available).
- movie_genres: A list of movie genres.

## :cinema: Movie Rating statistics Analysis with Visualization :bar_chart:

In this analysis, we delve into the distribution of movie ratings for a set of movies. We explore the dataset, calculate key statistics, and visualize the distribution to gain insights into how these movies are rated. The dataset consists of movie ratings on a scale of 1 to 10, and our goal is to understand the central tendencies and spread of these ratings.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/4d76097f-e56c-414b-9728-085573d18cf9">
</p>

## :cinema: Top 15 Movies by Rating Visualization :bar_chart:

The Python script generates a horizontal bar chart to display the top 15 movies with the highest ratings. It uses a DataFrame to store movie data, sorts the data by rating, and then creates a visual representation of the top-rated movies.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/47d9435e-9a6d-4b31-9fa6-d2b4746d72c4">
</p>

## :cinema: Distribution of Movie Genres Analysis with Visualization :bar_chart:

In this analysis, we explore the distribution of movie genres within a dataset of movies. Our goal is to visualize the prevalence of different genres in the dataset, providing insights into the diversity of movie categories. The dataset includes a list of movie titles, each associated with one or more genres.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/ce3c47c5-a5a0-4061-a1fb-50f8b0bf4cd0">
</p>

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

## :cinema: IMDb Movie Rankings vs. Ratings

This project retrieves data for the IMDb Top 100 Movies using the IMDb Top 100 Movies API from RapidAPI. It fetches movie details such as titles, ratings, ranks, and years, and then visualizes the data in a scatter plot.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/d4aa7669-4999-49c0-8698-f2c55bdd7e26"alt="Image" width="900">
</p>

## Average IMDb Ratings Over the Years

In this project, we utilize the IMDb Top 100 Movies API from RapidAPI to collect data on movie titles, ratings, ranks, and release years. The data is then processed and visualized using Python and popular data analysis libraries.

<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/9214e746-6d6d-45f5-bd8d-e81b33bf54a6"alt="Image" width="900">
</p>

## Conclusion

the Python scripts provided in this project are designed for various tasks related to movie data, including web scraping, sentiment analysis, image downloading, and statistical analysis of movie ratings. These scripts are versatile and can be adapted for specific use cases or integrated into larger projects. They demonstrate the use of libraries such as requests, beautifulsoup4, pandas, textblob, and matplotlib to perform a range of data-related tasks.
