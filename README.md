# Google Play Store Market Analysis with Python

## Overview
This project analyzes Google Play Store applications to understand which factors are associated with better ratings and stronger user acceptance. The analysis explores app categories, installs, ratings, prices, size, and user review sentiment to identify meaningful market patterns.

## Objective
The main objective of this project is to explore the Google Play Store dataset and answer questions such as:

- Do category, size, or price influence app ratings
- Which categories are most common in the market
- Are paid apps better rated than free apps
- How do installs and reviews differ between free and paid apps
- What does review sentiment suggest about user experience

## Datasets
The project uses the following datasets:

- `apps.csv`
- `user_reviews.csv`

These datasets include information about app category, rating, installs, reviews, price, size, and sentiment polarity from user reviews.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow
1. Load and inspect the datasets
2. Clean important variables such as `Installs` and `Price`
3. Convert fields into numeric format for analysis
4. Perform exploratory data analysis
5. Visualize category distribution, ratings, installs, price behavior, and sentiment
6. Interpret patterns and summarize business insights

## Key Analysis Performed
- Category frequency analysis
- Average rating analysis by category
- Comparison of free vs paid apps
- Relationship between app size and rating
- Relationship between app price and rating
- Outlier detection in app prices
- Sentiment polarity analysis from user reviews

## Main Findings
- The dataset contains a broad variety of apps across many categories
- The most represented categories are FAMILY and GAME
- The average app rating is approximately 4.17, suggesting that most apps are generally well rated
- Categories such as EVENTS, EDUCATION, and ART_AND_DESIGN show some of the highest average ratings
- There is no strong linear relationship between app size and rating
- Higher price does not guarantee better ratings among paid apps
- Free apps dominate the market in quantity, installs, and reviews
- Paid apps tend to have slightly higher ratings and slightly more positive sentiment on average
- App success appears to depend more on user experience, utility, accessibility, and service quality than only on size, category, or price

## Conclusion
This project shows that app performance in Google Play Store cannot be explained by a single variable. While price, size, and category provide useful context, user satisfaction seems to be more strongly influenced by overall experience, usefulness, and accessibility. The analysis demonstrates the value of data cleaning, exploratory analysis, and visualization in extracting business insights from marketplace data.

## Repository Structure
```text
google-play-store-analysis/
│
├── data/
│   ├── apps.csv
│   └── user_reviews.csv
│
├── notebooks/
│   └── Python.ipynb
│
├── images/
│   └── charts and screenshots
│
├── docs/
│   └── project conclusions
│
└── README.md
