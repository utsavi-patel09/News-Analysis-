
News Analysis System

This project develops a News Analysis System that automatically collects news articles from various websites using web scraping. It performs sentiment analysis for news' intensity analysis as positive, negative or neutral with its intensity scores and classifies articles as real or fake, providing the probability of each classification. The system supports two languages, English and Hindi, allowing for broader applicability. The results are displayed in an interactive dashboard, where patterns in real and fake news are analyzed. A user-friendly interface is created using Streamlit to facilitate easy visualization and exploration of the analysis results.

Features
Automated Data Collection
Sentiment Analysis of news in positive,negative and neutral
Pattern Analysis using clustering algorithms
Real or Fake News Classification
Two languages adaptability
Interactive Dashboard
Dataset
The dataset used in this project is a CSV file containing news articles collected through web scraping from various news websites. This file includes relevant information such as article titles, content, publication dates, and labels indicating whether the news is classified as real or fake. The dataset serves as the primary input for performing sentiment analysis and classification tasks in the News Analysis System.

Code Files
Real_or_fake: https://github.com/YashviPopat/News-Analysis-System/blob/2921c858e35f2b52f059e4b05c6f9c7cf20cbb8b/fake_real_with_pattern.ipynb

Sentimental_Analysis_of_news: https://github.com/YashviPopat/News-Analysis-System/blob/4dd9704fc764097180adc6c10536f7f6feb408ae/sentimental_analysis_with_pattern.ipynb

Hindi_News_Analysis: https://github.com/YashviPopat/News-Analysis-System/blob/4dd9704fc764097180adc6c10536f7f6feb408ae/sentimental_analysis_with_pattern.ipynb

Requirements
Programming Language and Environment Python 3.8+ Jupyter Notebook (optional, for running the code interactively)

Libraries and Frameworks Streamlit BeautifulSoup (for web scraping) Requests (for making HTTP requests) Pandas NumPy NLTK or TextBlob (for sentiment analysis) Scikit-learn (for classification models) Matplotlib and Seaborn (for data visualization)

Dataset CSV file containing web-scraped news articles in both English and Hindi, including relevant information such as titles, content, publication dates, and classification labels (real or fake).

Authors
-@Yashvi Popat

-@Pooja Mehta