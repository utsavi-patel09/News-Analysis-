# News Analysis System

This project develops a **News Analysis System** that automatically collects news articles from various websites using web scraping. It performs sentiment analysis to classify news as **positive**, **negative**, or **neutral**.

The system supports two languages — **English** and **Hindi**, extending its applicability. Results are displayed in an **interactive Streamlit dashboard**, enabling users to explore patterns in news content with ease.

## 📌 Features

- **Automated Data Collection:** Web scraping to gather news articles.
- **Sentiment Analysis:** Classify news sentiment as positive, negative, or neutral, along with intensity scores.
- **Pattern Analysis:** Cluster news articles to detect patterns.
- **Multilingual Support:** Analysis in both English and Hindi.
- **Interactive Dashboard:** Visualize and explore results through a user-friendly interface.

## 🗃 Dataset

The dataset consists of a **CSV file** containing web-scraped news articles. Each entry includes:
- **Title** of the article
- **Content** of the article
- **Publication date**
- **Classification label** indicating whether the article is real or fake

The dataset serves as the primary input for sentiment analysis and classification tasks.

## 📂 Code Files

- **Sentiment Analysis of News:** [sentimental_analysis_with_pattern.ipynb](https://github.com/YashviPopat/News-Analysis-System/blob/4dd9704fc764097180adc6c10536f7f6feb408ae/sentimental_analysis_with_pattern.ipynb)
- **Hindi News Analysis:** [hindi_sentimental_analysis_with_pattern.ipynb](https://github.com/YashviPopat/News-Analysis-System/blob/4dd9704fc764097180adc6c10536f7f6feb408ae/sentimental_analysis_with_pattern.ipynb)

## 📂 Demo
- [Watch video](Demo): Click on view Row option.


## 🛠 Requirements

### **Programming Language & Environment:**
- **Python 3.8+**
- **Jupyter Notebook** 

### **Libraries & Frameworks:**
- **Streamlit** *(for UI and dashboard)*
- **BeautifulSoup** *(for web scraping)*
- **Requests** *(for making HTTP requests)*
- **Pandas & NumPy** *(for data manipulation)*
- **NLTK or TextBlob** *(for sentiment analysis)*
- **Scikit-learn** *(for machine learning models)*
- **Matplotlib & Seaborn** *(for data visualization)*

## 👩‍💻 Authors

- [**Yashvi Popat**](https://github.com/YashviPopat)
- [**Pooja Mehta**](https://github.com/pooja-mehta)

