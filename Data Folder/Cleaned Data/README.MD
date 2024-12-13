### Data Overview

This project utilizes multiple datasets to analyze the IMDB Top 250 Movies from 2021 and 2024. Below is an explanation of where each dataset originates and what it contains.

#### **1. `2021_List_Top_250_Movies.csv`**

- **Source**: Kaggle dataset ([IMDB Top 250 Movies Dataset](https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset?resource=download)).
- **Description**: This dataset provides a snapshot of the Top 250 movies from 2021, including:
  - Title
  - Release year
  - IMDB rank and rating
  - Cast and director
  - Box office revenue and budget
  - Genre, tagline, and certificate

#### **2. `2024_List_Top_250_Movies_Cleaned_Merged.csv`**

- **Source**: Scraped from the IMDB website ([Top 250 Movies List](https://www.imdb.com/chart/top/?ref_=nv_mv_250&sort=user_rating%2Cdesc)).
- **Description**: This dataset combines the latest 2024 rankings with additional details:
  - Updated rank, rating, and popularity score
  - Metascore (combining user and critic reviews)
  - Number of Oscars won

#### **3. `top_250_cleaned.csv`**

- **Source**: Cleaned version of the raw 2024 Top 250 Movies dataset.
- **Description**: Includes cleaned and verified columns for:
  - Title
  - Rank
  - Rating
  - Release year
  - Runtime

#### **4. `top_250_details_cleaned.csv`**

- **Source**: Scraped additional details from individual movie pages on IMDB.
- **Description**: Provides enriched information such as:
  - Metascore
  - Popularity score
  - Number of Oscars won

#### **5. `2021_2024_List_Top_250_Movies.csv`**

- **Source**: Merged dataset combining cleaned 2021 and 2024 movie data.
- **Description**: This is the final dataset used for analysis, including:
  - Titles present in both years
  - Comparison of rankings, ratings, and additional metrics
  - Calculated columns like average rating and profit
