﻿# ReviewGameOf2024

## Introduction
This project analyzes user reviews of the game. The goal is to identify key factors affecting review scores, extract common keywords, and visualize data using WordCloud.

## Tools
 Google CoLab, Instant Data Scaper

## Data
  Google Reviews

## Analysis Steps

1. Data Preprocessing

Convert text to lowercase.

Remove punctuation and special characters.

Eliminate stopwords to focus on key terms.

2. Keyword Extraction

Use WordCloud to visualize frequently mentioned words in reviews.

Compute word frequency statistics.

3. Review Score Trends Analysis

Analyze the relationship between keywords and review scores.

pip install pandas matplotlib wordcloud nltk

2. Execute the Analysis Script

python analyze_reviews.py

3. Output Results

WordCloud image displaying common keywords in reviews.

Statistical analysis of keywords impacting review scores.

Processed CSV file with cleaned data.
