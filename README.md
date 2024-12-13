# BAIS-3250-Final-Project

![Python badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Iowa City badge](https://img.shields.io/static/v1?message=IA&logo=google-maps&labelColor=ffcd00&color=000000&logoColor=black&label=Iowa%20City&style=for-the-badge)

# IMDB Top 250 Movies Analysis (2021 vs 2024)

## 3250: Data Wrangling

## Melanie Gradeler & Delanie Dahm

### Project Overview

This project analyzes changes in the IMDB Top 250 Movies list between 2021 and 2024. We aim to uncover trends, identify correlations, and explore the factors that contribute to a movie's success over time.

## 📖 Data Dictionary

| Field              | Type    | Source         | Description                                                                                |
| ------------------ | ------- | -------------- | ------------------------------------------------------------------------------------------ |
| `rank_2021`        | Integer | Kaggle dataset | This is the ranking of each movie in 2021 (based on IMDB user rating)                      |
| `rank_2024`        | Integer | IMDB.com       | This is the ranking of each movie in 2024 (based on IMDB user rating)                      |
| `title`            | Object  | Both           | Title of the movie                                                                         |
| `year`             | Integer | Both           | Year the movie was released                                                                |
| `run_time`         | Integer | Both           | The duration of the movie in minutes                                                       |
| `IMDB_rating_2021` | Float   | Kaggle dataset | User rating of the movie on IMDB scale (1-10)                                              |
| `IMDB_rating_2024` | Float   | IMDB.com       | User rating of the movie on IMDB scale (1-10)                                              |
| `average_rating`   | Float   | Both           | Average of the user rating on the IMDB scale (1-10) between 2021 and 2024                  |
| `genre`            | Object  | Kaggle dataset | Genres of the movie                                                                        |
| `box_office`       | Float   | Kaggle dataset | Total box office revenue collection across the world (in $ USD)                            |
| `budget`           | Float   | Kaggle dataset | The total cost of producing the movie (in $ USD)                                           |
| `certificate`      | Object  | Kaggle dataset | Movie Certificate (PG-13, R, PG, etc.)                                                     |
| `tag_line`         | Object  | Kaggle dataset | A slogan/catchphrase used to promote the movie                                             |
| `cast`             | Object  | Kaggle dataset | List of main actors and actresses or anyone that appeared as part of the cast in the movie |
| `directors`        | Object  | Kaggle dataset | The person responsible for overseeing the creative aspects of the film                     |
| `writers`          | Object  | Kaggle dataset | List of writers that created and wrote the script/story of the movie                       |
| `popularity_score` | Integer | IMDB.com       | Additional ranking encompassing present user interaction with the movies                   |
| `metascore`        | Integer | IMDB.com       | Numeric score that combines user and critic ratings and reviews (1-100)                    |
| `oscars`           | Object  | IMDB.com       | Number of Oscars won by the movie                                                          |
| `url`              | Object  | IMDB.com       | Link to each movie’s page pulled from the list                                             |

---

Feel free to explore the code, data, and results to gain insights into the IMDB Top 250 Movies over time! 🎥
