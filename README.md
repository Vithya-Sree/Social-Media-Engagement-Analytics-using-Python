# Social Media Engagement Analytics Using Python

## Project Overview

Social media platforms generate large amounts of data such as likes, comments, shares, impressions, watch time, followers, and engagement rates.

This project focuses on analyzing social media engagement data using Python. The dataset contains 5,000 social media records with information about users, posts, engagement metrics, devices, countries, sentiment, and other factors.

The project covers the complete data analysis process, including **data cleaning, data exploration, data wrangling, statistical analysis, visualization, and insight generation**.

---

## Dataset

**Dataset Name:** `social_media_engagement_5000.csv`

The dataset contains information such as:

* User age
* Gender
* Country
* Post type
* Post category
* Likes
* Comments
* Shares
* Watch time
* Impressions
* Followers
* Verified account status
* Device type
* Sentiment
* Hashtags
* Engagement rate
* Posted date

---

## Objectives

The main objectives of this project are to:

* Understand the structure of social media engagement data
* Clean and prepare the dataset for analysis
* Handle missing and duplicate data
* Correct data types and inconsistent categories
* Analyze user and content behavior
* Calculate statistical measures
* Study relationships between engagement metrics
* Create meaningful visualizations
* Identify factors that influence social media engagement
* Generate useful business insights

---

## Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Plotly**
* **Google Colab**

---

## Project Workflow

### 1. Data Import and Setup

The dataset is imported using Pandas.

The initial analysis includes:

* Checking dataset shape
* Viewing column names
* Checking data types
* Viewing the first and last records
* Generating summary statistics

---

### 2. Data Cleaning

The dataset is cleaned before performing analysis.

The cleaning process includes:

* Detecting missing values
* Handling missing numeric values using the median
* Handling missing categorical values using the mode
* Removing duplicate records
* Converting columns to appropriate data types
* Converting the posted date into datetime format
* Standardizing categorical values
* Cleaning gender and sentiment labels
* Identifying unrealistic values
* Correcting invalid engagement values

---

### 3. Feature Engineering

New features are created to make the analysis more useful.

The project creates:

* **Engagement Score** — calculated using likes, comments, and shares
* **Hashtag Count** — number of hashtags used in each post
* **Day** — extracted from the posted date
* **Hour** — extracted from the posted date
* **Month** — extracted from the posted date
* **Age Group** — created for comparing engagement across different age ranges

---

### 4. Data Exploration

Pandas is used to explore the cleaned dataset.

The analysis includes:

* Post type distribution
* Post category distribution
* Country distribution
* Gender distribution
* Device distribution
* Sentiment distribution
* Unique values
* Number of unique categories
* Correlation between numeric variables
* Grouped analysis by post type, country, category, and sentiment

---

### 5. Statistical Analysis

Descriptive statistics are calculated for important engagement metrics.

The analysis includes:

* Mean
* Median
* Mode
* Standard deviation
* Variance
* Percentiles
* Minimum and maximum values

The main metrics analyzed are:

* Likes
* Comments
* Shares
* Watch time
* Engagement rate
* Followers

---

## Data Visualization

Different Python visualization libraries are used to understand patterns in the dataset.

### Matplotlib

The project includes:

* Scatter plot — Likes vs Impressions
* Line chart — Daily Engagement Trend
* Bar chart — Posts by Category
* Pie chart — Gender Distribution
* Histogram — Age Distribution
* Box plot — Engagement Rate Distribution

### Seaborn

The project includes:

* Count plot — Post Type
* Bar plot — Average Likes by Category
* Violin plot — Followers vs Sentiment
* Pair plot — Numeric Features
* Heatmap — Correlation Matrix
* Swarm plot — Engagement Rate by Device

### Plotly

Interactive visualizations include:

* Interactive daily engagement trend
* Interactive average likes by category
* Interactive followers vs impressions bubble chart

---

## Key Analysis Questions

The project is designed to answer questions such as:

### Content Performance

* Which post type has the highest engagement?
* Which content category performs best?
* Which countries have the highest average engagement rate?

### User Trends

* How does age affect engagement?
* Do verified accounts receive higher engagement?
* Which age group shows the highest engagement?

### Behavioral Insights

* What time of day receives the highest impressions?
* Which device has the highest average watch time?
* How do different devices affect engagement?

### Sentiment Analysis

* Which sentiment performs best?
* How do negative posts perform?
* How do neutral posts perform?
* Do positive posts receive higher engagement?

---

## Insights Generated

The final section of the analysis automatically identifies:

* Best-performing post type
* Best-performing content category
* Country with the highest average engagement
* Engagement by age group
* Performance of verified accounts
* Best time of day for impressions
* Watch time by device
* Best-performing sentiment
* Performance of negative and neutral posts

---

## Conclusion

This project demonstrates how Python can be used to analyze social media engagement data from beginning to end.

The analysis combines **Pandas and NumPy for data processing**, **Matplotlib and Seaborn for visualization**, and **Plotly for interactive analysis**.

The project helps identify patterns in content performance, user behavior, device usage, posting time, and sentiment. These insights can be useful for understanding which types of social media content are more effective and how engagement varies across different user and content characteristics.
