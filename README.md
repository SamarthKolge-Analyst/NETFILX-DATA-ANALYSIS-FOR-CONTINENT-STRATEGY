# 📊 Netflix Case Study - Data Exploration and Visualization

## 🌟 Project Overview

This project involves performing data exploration and visualization on the Netflix dataset to gain insights that can help Netflix decide what types of shows/movies to produce and how to grow the business in various countries.

### 📈 Business Problem

Analyze the data to generate insights that could help Netflix decide which type of shows/movies to produce and how they can grow their business in different countries.

### 📁 Dataset

The dataset contains information about TV shows and movies available on Netflix, including the following attributes:

* **Show\_id**: Unique ID for every Movie/TV Show
* **Type**: Identifier - A Movie or TV Show
* **Title**: Title of the Movie/TV Show
* **Director**: Director of the Movie
* **Cast**: Actors involved in the movie/show
* **Country**: Country where the movie/show was produced
* **Date\_added**: Date it was added on Netflix
* **Release\_year**: Actual Release year of the movie/show
* **Rating**: TV Rating of the movie/show
* **Duration**: Total Duration - in minutes or number of seasons
* **Listed\_in**: Genre
* **Description**: Summary description

### Objectives

1. Define the problem statement and analyze basic metrics.
2. Analyze the data structure, detect missing values, and generate a statistical summary.
3. Perform non-graphical analysis: value counts and unique attributes.
4. Visual Analysis:

   * Univariate, Bivariate analysis using various plots (Distplot, Countplot, Boxplot, Heatmaps, Pairplots).
   * Missing Value and Outlier check.
5. Derive business insights and make actionable recommendations.

### 📝 Recommendations

1. Focus on popular genres like Drama, Comedy, and International TV Shows/Movies.
2. Release TV Shows in July/August and Movies at the end or start of the year.
3. For the USA, produce movies of 80-120 minutes and Kids TV Shows.
4. For the UK, maintain the same movie length and target mature audiences.
5. In India, increase the number of movies as it has been declining since 2018.
6. Create Anime content for Japan and Romantic TV Shows for South Korea.
7. Consider popular actors/directors and their combinations while creating content.

### Challenges Faced

1. **Multiple Directors Issue**: Some movies have two directors, making it difficult to perform certain operations. To manage this, I reduced the granularity.
2. **Duration Column**: The 'Duration' column had numerical values for movies (e.g., '120 min') but categorical values for series (e.g., '2 seasons'), requiring special handling.
3. **Date Column Handling**: The 'Date\_added' column was recognized as an object data type by Pandas, hindering date extraction. I converted it using `pd.to_datetime()`.
4. **Missing Value Imputation**: Replaced missing values with the most appropriate estimates to improve analysis accuracy.
5. **EDA Challenges**: Performed extensive univariate and bivariate analysis to extract meaningful insights from the data.

### 📂 Files

* PDF Report: [Netflix\_case\_study\_2.0.pdf](https://drive.google.com/file/d/1JlTjTwsZlDhqdrEoiNn80FtLh21u55uj/view?usp=drive_link)
* Jupyter Notebook: [Netflix\_case\_study\_2.0.ipynb](https://drive.google.com/file/d/1dNNSALliFfQjR6CT_Bx-40eMgeDjrVIK/view?usp=sharing)
* Dataset: [Netflix Data](https://drive.google.com/file/d/1w4Ybop112QGhcQVNBrxokPnwEgpnaEuE/view?usp=drive_link)
