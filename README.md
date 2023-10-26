# Exploratory Data Analysis of Google Play Store Apps

## Introduction
The Google Play Store has a vast range of apps to meet various user needs. As the Android market is crucial, comprehending patterns and trends can be immensely useful for app developers. This EDA delves into the "Google Play Store Apps" dataset from [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps), with the aim of uncovering insights that can assist developers in their efforts.

## Dataset Overview
- **Entries**: 10,841
- **Attributes**: 13 (12 categorical, 1 numeric)
- **Description**: The dataset encompasses various attributes of apps available on the Google Play Store, offering insights into app performance, user reviews, ratings, and more.

## Objectives
The primary focus of this analysis includes:
- Understanding correlations with the number of app installs.
- Identifying highly downloaded categories and genres.
- Investigating the relationship between app ratings, install counts, and update frequency.

## Tools & Libraries Used
- numpy
- pandas
- matplotlib.pyplot
- seaborn

## Key Findings

### Correlations and Relationships
- **Reviews and Installs**: Apps with more reviews often have higher installs, reinforcing the importance of user feedback in app success.
- **Ratings and Installs**: A direct relationship between higher ratings and more installs suggests that app quality impacts popularity.
- **App Size**: Contrary to expectations, the app's size doesn't significantly influence its popularity.
- **Free vs. Paid**: Paid apps generally see fewer installs than their free counterparts.

### Category Analysis
- **Ratings**: Apps in 'Art and Design', 'Comics', 'Health and Fitness', and 'Education' enjoy the highest median ratings, pointing to higher user satisfaction in these categories.
- **Reviews**: 'Entertainment' leads in terms of median reviews.
- **Size**: Games, being graphics-intensive, typically demand more storage.
- **Pricing**: 'Finance' apps come with a highest median price, possibly due to their specialized nature.
- **Installations**: Dominating categories in terms of installations include 'Weather', 'Education', 'Video players', 'Shopping', 'Photography', 'Game', and 'Entertainment'.

### Other Noteworthy Insights
- **Genre Focus**: High-install apps generally specialize in a single genre, hinting at either user preference for specificity or ease of understanding for such apps.
- **Update Frequency vs. Ratings**: Although there's no solid correlation, a steady trend of app development over the years is evident.
- **Content Rating**: Apps in the 'Adults only 18+' segment surprisingly have the highest average ratings, reflecting niche satisfaction.

## Conclusion
The Google Play Store is a dynamic ecosystem with diverse offerings. As demonstrated by the findings, user feedback and app quality play pivotal roles in determining an app's success. While categories like 'Entertainment' and 'Game' are leading in popularity, it's clear that niche categories also have their dedicated, satisfied audience. As the Android market continues to expand, these insights will prove invaluable for app developers and marketers looking to make their mark.


You can view my notebook and visualizations [here](https://nbviewer.org/github/sherniia/Google-Play-Store-App-EDA-Project/blob/main/Google_apps_EDA_1.ipynb). 


