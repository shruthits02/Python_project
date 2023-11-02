<h1>Python web scraping project using IMDb</h1>

Scraping IMDb's top 20 movies list, the goal is to extract information about the top-rated movies, including their titles, release years, and ratings. IMDb is a popular online database of movies, TV shows, and celebrities, and it provides a list of the top-rated movies based on user and critic reviews. Web scraping allows you to automate the process of collecting this data instead of manually copying and pasting it.
<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/7c793f9c-f634-4ff0-ba0b-9787eb942870" alt="Image" width="900">
</p>

## Information Source

The information is used in this analysis is derived from the following 

```
URL: https://www.imdb.com/list/ls576754431/
URL: https://www.imdb.com/title/tt10366206/reviews
```
## Data Content

The project involves web scraping, data cleaning, analysis, and visualization data, the following information are :
- IMDb Movie Details Scraper
- IMDb Movie Review Sentiment Analysis
- IMDb Movie Review Sentiment Analysis with Visualization
- IMDb List Image Downloader

## IMDb Movie Details Scraper

The Python script is designed to scrape movie details from a specific IMDb list. It extracts information about movies, including their names, release years, runtimes, ratings, metascores (if available), and genres. 

### The script populates several lists with movie details:

- movie_names: A list of movie names.
- movie_years: A list of movie release years.
- movie_times: A list of movie runtimes.
- movie_ratings: A list of movie ratings.
- movie_metascores: A list of movie metascores (if available).
- movie_genres: A list of movie genres.

## IMDb Movie Review Sentiment Analysis

The Python script scrapes movie reviews from IMDb and performs sentiment analysis to classify them as positive or negative. It uses the BeautifulSoup library for web scraping and the TextBlob library for sentiment analysis.

## IMDb Movie Review Sentiment Analysis with Visualization

The Python script scrapes movie reviews from IMDb, performs sentiment analysis using TextBlob, and visualizes the results using a bar chart. It classifies reviews as positive or negative based on a predefined sentiment polarity threshold.
<p align="center">
  <img src="https://github.com/shruthits02/Python_project/assets/147556178/b1c37ed6-0851-4235-989b-d4fb3419fa26">
</p>

## IMDb List Image Downloader

The Python script scrapes and downloads images from an IMDb list. It sends an HTTP GET request to the IMDb list URL, parses the HTML content to find image elements with the "loadlate" class, and then proceeds to download and save these images to a specified directory.



