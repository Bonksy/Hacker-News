# Project: Exploring Hacker News Posts

## Overview
In this project, we analyze data from Hacker News, focusing on two types of posts: Ask HN and Show HN. We aim to answer the following questions:

1. Which type of posts receives more comments on average?
2. Does the time of posting affect the number of comments received?

## File Overview
- **File:** hacker_news.csv
- **Description:** Contains data on Hacker News posts including ID, title, URL, number of points, number of comments, author, and creation timestamp.

## Getting Started
1. Open the file "hacker_news.csv" in read mode. You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/hacker-news/hacker-news-posts).
2. Convert the CSV data into a list of lists for analysis.

## Removing Headers
- Extract the headers (column names) and remove them from the data.

## Categorizing Posts
- Separate posts into three categories: "Ask HN", "Show HN", and others based on their titles.

## Analysis: Comments on Ask HN and Show HN Posts
1. Determine the average number of comments for "Ask HN" posts.
2. Determine the average number of comments for "Show HN" posts.

## Time Analysis: Comments vs. Post Time
1. Extract the hour from the creation timestamp for each "Ask HN" post.
2. Calculate the average number of comments per "Ask HN" post for each hour of the day.

## Results
- Identify the hours with the highest average comments per "Ask HN" post.
- Print the top 5 hours with the highest average comments.

## Next Steps
- Further exploration into the factors affecting post engagement.
- Refining the analysis to gain deeper insights into user behavior.

For detailed code implementation, refer to the provided code snippets.
