# Twitter Sentiment Analysis with Selenium and MongoDB

This project performs sentiment analysis on tweets using Selenium for web scraping, NLTK for natural language processing, and MongoDB for data storage. The analysis includes visualizations of sentiment distribution and hashtag frequency.

## Key Technologies

- **Python**: Core programming language.
- **Selenium**: Web scraping and browser automation.
- **NLTK**: Natural language processing and sentiment analysis.
- **MongoDB**: Database for storing tweet data.
- **Matplotlib & Seaborn**: Data visualization.
- **WordCloud**: Generating word clouds.

## Features

- **Tweet Extraction**: Scrapes tweets based on hashtags.
- **Sentiment Analysis**: Classifies tweets as positive, neutral, or negative.
- **Data Visualization**: Bar plots, pie charts, and word clouds for insights.
- **Hashtag Analysis**: Tracks and visualizes hashtag usage.

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/safaeOulaja/tweetsSentimentScraper.git
    cd tweetsSentimentScraper
    ```

2. **Install dependencies**:
    ```bash
    pip install selenium pymongo nltk wordcloud seaborn pandas matplotlib
    ```

3. **Run the script**:
    ```bash
    python Script_Name.py
    ```

## Usage

- **Configure MongoDB**: Ensure MongoDB is running and update the connection string in the script.
- **Run Analysis**: Execute the script to start scraping and analyzing tweets.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
