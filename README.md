# DSA 210 Term Project: Analyzing Factors Influencing IMDb, Rotten Tomatoes and MetaCritic Ratings of Netflix Content

## Project Overview
The aim of this project is to analyze and compare the impact of various factors on the IMDb and Rotten Tomatoes scores of Netflix films and TV shows. By manually curating a dataset of approximately 200 titles, we will investigate how aspects such as language, content genre, content type, trailer popularity, watch time, budget, and production year (etc.) influence audience and critic ratings.

## Motivation
- **Personal Interest**
  Understanding the factors that contribute to a movie’s or TV show’s success is a fascinating topic in media analytics. Streaming platforms like Netflix provide a massive selection of content, and exploring which attributes correlate with higher audience engagement and ratings aligns with my interest in data-driven decision-making.
- **Application**
  This project bridges media analytics and data science. By integrating data from multiple sources, we aim to uncover key predictors of high IMDb and Rotten Tomatoes scores, providing valuable insights for both content creators and streaming platforms.

## Data Source
The dataset for this project will be manually compiled by selecting around 200 Netflix films and TV shows based on a diverse range of characteristics. Additional data will be incorporated from external sources such as:

- **IMDb API**: For IMDb ratings and additional movie details.

- **Rotten Tomatoes API**: For critic reviews and audience scores.

- **YouTube API**: To extract trailer view counts for selected titles.

- **Google Trends**: To measure search interest for specific movies and TV shows.

This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.
-[Dataset Link](https://www.kaggle.com/datasets/thedevastator/rotten-tomatoes-top-movies-ratings-and-technical)
-[Dataset Link](https://www.kaggle.com/datasets/ashishgup/netflix-rotten-tomatoes-metacritic-imdb)
-[Dataset Link](https://www.kaggle.com/datasets/danielgrijalvas/movies?resource=download)

## Tools & Technologies Used
- Programming Language: Python

- Data Analysis & Processing: Pandas, NumPy

- Data Visualization: Matplotlib, Seaborn

- Machine Learning: Scikit-learn
  
## Data Analysis
Project structure is as following;

1. **Data Collection & Cleaning**:

- Manual Data Compilation: Used 3 different datasets which contains more than 20.000 movies and tv shows.

- Handling Missing Values: Filling in missing data from external APIs.

- Standardizing Formats: Ensuring consistency in numerical values (e.g., IMDb ratings, watch time) and categorical variables (e.g., genres, languages, production year).

2. **Exploratory Data Analysis**:
- Impact of Language on Ratings: Examining whether certain production languages result in higher or lower IMDb/Rotten Tomatoes scores.

- Netflix Originals vs. Licensed Content: Comparing ratings and watch time between original and non-original content.

- Producing company vs. IMDb Ratings: Investigating if highly viewed trailers correlate with higher IMDb scores.

- Watch Time vs. Content Type: Analyzing whether films or TV shows have higher engagement levels.

- Production Year & Rating Trends: Checking whether newer content tends to receive better or worse reviews.

- Film Duration & IMDb Scores: Evaluating whether longer films have better ratings.

- Director Influence: Investigating if films with well-known actors or directors receive higher ratings.

- Genre-Based Rating Differences: Analyzing which genres generally receive better scores.

3. **Machine Learning application**:
- regression models could be applied to predict IMDb and Rotten Tomatoes scores based on multiple factors, including director, language, production year, and content type.

## Expected Findings
- Certain languages and genres may consistently perform better in audience and critic ratings.

- High trailer view counts might correlate with stronger IMDb scores, reflecting audience anticipation.

- Netflix Originals may have different rating trends compared to licensed content.

- Production year and film duration may influence ratings significantly.

- Actor and director reputation might play a role in the perceived quality of content.

## Challenges and Future Improvements
- **Dataset Size Constraints**: Since the dataset is manually compiled, the sample size will be limited compared to large-scale, publicly available datasets.

- **Data Gaps**: Some attributes, such as exact watch time or regional viewership statistics, may not be readily available.

- **Selection Bias**: As the films and shows are selected manually, there is a possibility of unintentional bias in the dataset.

- **Potential Expansions**: Future iterations of this project could involve increasing the dataset size and incorporating additional metrics, such as streaming hours from Netflix (if accessible), to provide deeper insights into audience 
 preferences and content engagement.
