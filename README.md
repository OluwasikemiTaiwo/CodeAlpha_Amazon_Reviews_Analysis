# Amazon Reviews Analysis

## Project Overview

This project analyzes a large dataset of Amazon customer reviews to identify patterns and trends in customer ratings, review activity, product popularity, review length, and review helpfulness.

The project is being completed as part of a Data Analytics Internship with CodeAlpha and demonstrates the use of Python for exploratory data analysis and data visualization.

## Objectives

The objectives of this project are to:
- Understand the structure and quality of the Amazon reviews dataset.
- Examine the distribution of customer ratings.
- Analyze review activity over time.
- Identify products with the highest number of reviews.
- Identify highly active reviewers.
- Examine the relationship between review length and customer ratings.
- Analyze review helpfulness across different customer ratings.
- Present findings using appropriate data visualizations.

## Dataset

The dataset contains **568,454 Amazon customer reviews**.

The main variables include:
- `Id` – Unique review identifier.
- `ProductId` – Identifier of the reviewed product.
- `UserId` – Identifier of the reviewer.
- `ProfileName` – Name associated with the reviewer profile.
- `HelpfulnessNumerator` – Number of users who found the review helpful.
- `HelpfulnessDenominator` – Total number of users who rated the review's helpfulness.
- `Score` – Customer rating from 1 to 5.
- `Time` – Review timestamp.
- `Summary` – Short summary of the review.
- `Text` – Full review text.

## Tools and Technologies
The following tools and Python libraries were used:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Exploratory Data Analysis

The analysis included:
### Data Quality

- Dataset dimensions
- Data types
- Missing-value analysis
- Duplicate-record analysis

### Customer Ratings

The distribution of ratings was examined to understand overall customer satisfaction.

The dataset has an average customer rating of approximately **4.18 out of 5**.

Five-star reviews represent the largest proportion of reviews, accounting for approximately **63.88%** of the dataset.
### Review Trends Over Time

Review timestamps were converted into readable dates to examine changes in review activity over time.

The dataset contains reviews spanning from **1999 to 2012**, with review activity increasing substantially in the later years.

### Product and User Activity

The analysis identified products receiving the highest number of reviews and users who submitted the highest number of reviews.

The most-reviewed product in the dataset received **913 reviews**.

### Review Length
Review text length was analyzed to examine differences in customer feedback across different rating scores.

### Review Helpfulness

The relationship between customer ratings and review helpfulness was examined using the helpfulness measures available in the dataset.

## Key Findings

The exploratory analysis produced several notable findings:

1. The dataset contains 568,454 customer reviews.
2. There are no duplicate records in the dataset.
3. The overall average customer rating is approximately 4.18 out of 5.
4. Five-star reviews make up approximately 63.88% of all reviews.
5. Review activity increased significantly over the years covered by the dataset.
6. Some products received substantially more reviews than others.
7. A small number of users contributed a large number of reviews.
8. Review length and helpfulness vary across different customer rating levels.

## Project Structure

```text
CodeAlpha_Amazon-Reviews-Analysis/
│
├── data/
│   └── Amazon Review.csv
│
├── notebooks/
│   └── Amazon_Reviews_Analysis.ipynb
│
├── README.md
│
└── requirements.txt
