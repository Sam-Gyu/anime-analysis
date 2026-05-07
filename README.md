# Anime Data Analysis

This project performs an exploratory data analysis (EDA) on a dataset of anime to uncover insights into their characteristics, popularity, and ratings.

## Project Goals
- **Data Loading:** Load the anime dataset into a pandas DataFrame.
- **Data Preprocessing & Cleaning:** Handle missing values, convert data types, and clean textual data.
- **Exploratory Data Analysis (EDA):** Visualize distributions, relationships between variables, and identify patterns or anomalies.
- **Reporting:** Generate a comprehensive profile report using `ydata-profiling`.

## Key Findings
- **Rating Distribution:** The majority of anime ratings fall between 5.5 and 7.5, with very few extreme high or low scores.
- **Anime Types:** TV series are the most prevalent, followed by OVAs and Movies.
- **Average Ratings by Type:** Movies generally receive the highest average ratings, suggesting higher production quality or critical reception.
- **Top Genres:** Comedy, Action, and Adventure are the most frequent genres, indicating popular themes among anime viewers.
- **Community Engagement:** There's a positive correlation between higher ratings and the number of community members, though popularity isn't solely driven by rating.
- **Episode Count:** Most anime have a single episode (movies, OVAs), with 12-13 and 24-26 episodes being common for multi-episode series.

## Technologies Used
- Python
- Pandas (for data manipulation)
- Matplotlib & Seaborn (for data visualization)
- NumPy (for numerical operations)
- `ydata-profiling` (for automated data profiling)
