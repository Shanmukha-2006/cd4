# Task 4 – Sentiment Analysis Using NLP

This project is part of my **Data Analyst Internship at CodeTech**. The objective of Task 4 is to analyze the **sentiment** of customer reviews using **Natural Language Processing (NLP)** techniques.

## Task Objective

> Perform sentiment analysis on textual data (e.g., reviews or tweets) using NLP techniques. The task involves:
- Data preprocessing
- Model implementation
- Extracting actionable insights

## Dataset

The dataset used is a synthetic Amazon-style product reviews file, containing:
- `review_id`: Unique ID
- `product_title`: Product name
- `review_body`: Customer review text
- `star_rating`: Rating (1 to 5)
- `review_date`: Date of the review

> 📄 File: `sample_amazon_reviews.csv`

## Tools & Libraries Used

- Python
- Pandas
- TextBlob (for sentiment analysis)
- Matplotlib / Seaborn (for visualization)

## NLP Workflow

1. **Data Cleaning** – Removed missing reviews
2. **Sentiment Analysis** – Applied `TextBlob` to analyze review sentiment
3. **Classification** – Categorized sentiment into:
   - Positive
   - Negative
   - Neutral
4. **Visualization** – Plotted sentiment distribution
5. **Insights** – Identified which products had more negative reviews
   
## Key Insights

- Most reviews were **positive**, indicating general customer satisfaction.
- Products like **Smart Watch** had the highest number of positive sentiments.
- A small portion of reviews were clearly **negative**, useful for quality feedback.
- Sentiment analysis helps companies **monitor public opinion** and improve services.
