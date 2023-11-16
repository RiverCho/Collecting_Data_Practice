
# IMDB Top-Rated Movies Dataset

## Description
This dataset contains approximately 10,000 entries detailing movies from IMDB. Each entry provides the movie's title, release year, runtime in minutes, age certification, genre, director, leading stars, average IMDB rating out of 10, metascore based on critical reviews, total user votes on IMDB, and its box office gross earnings. It serves as a comprehensive reference for movie enthusiasts and researchers analyzing cinema trends.

## Variables

| Variable     | Description                                        | Data Type |
|--------------|----------------------------------------------------|-----------|
| title        | The name/title of the movie.                       | String    |
| year         | The release year of the movie.                     | Integer   |
| runtime      | The total duration/length of the movie in minutes. | Integer   |
| certificate  | The age certification or rating of the movie.      | String    |
| genre        | The category or type of movie.                     | String    |
| director     | The director of the movie.                         | String    |
| stars        | Leading actors and actresses featured in the movie.| String    |
| rating       | The average IMDB rating of the movie out of 10.    | Float     |
| metascore    | The metascore rating based on critical reviews.    | Float     |
| votes        | The total number of user votes/ratings on IMDB.    | Integer   |
| gross        | The total box office collection/gross earnings.    | Float     |

## Creator/Curator and Source
- **Creator:** Ashutosh Devpura
- **Source:** [IMDB Top 10000 Movies (Updated August 2023)](https://www.kaggle.com/datasets/ashutoshdevpura/imdb-top-10000-movies-updated-august-2023)

## About the Dataset
### Scraping Process
The dataset has been obtained through Python code meticulously crafted by the curator, ensuring the accuracy and integrity of the data. The scraping process involved extraction directly from the IMDB website.

### Inspiration
The motivation behind compiling this dataset was to analyze the factors contributing to a film's success. By juxtaposing various metrics like ratings, metascores, and box office earnings, this dataset caters to cinephiles, data scientists, and industry professionals alike, enabling a deeper exploration into the evolving landscape of cinema.

### Important Note
While sourced from IMDB, it's crucial to acknowledge that web scraping may introduce discrepancies. Hence, responsible usage of the data is recommended.

