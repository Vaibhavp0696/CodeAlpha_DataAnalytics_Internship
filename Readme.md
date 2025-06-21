# 📊 CodeAlpha Data Analytics Internship Project

## 🎯 Overview
This repository contains the completed tasks for the **CodeAlpha Data Analytics Internship**, where I applied Python-based data analysis, web scraping, visualization, and sentiment analysis techniques on real-world datasets.

Tasks Completed:
- ✅ Task 1: Web Scraping  
- ✅ Task 2: Exploratory Data Analysis (EDA)  
- ✅ Task 4: Sentiment Analysis  

---

## 🧹 Task 1: Web Scraping — Books to Scrape

### 🔍 Objective
Extract book titles and prices from [BooksToScrape.com](https://books.toscrape.com) using Python and BeautifulSoup, and save the data in a structured format.

### 🛠️ Tools Used
- Python
- `requests`, `BeautifulSoup`, `pandas`

### 🚀 What I Did
- Fetched HTML data using `requests`
- Parsed book titles and prices using `BeautifulSoup`
- Stored the scraped data in a CSV file

### 📁 Output
- File: `books_data.csv`

---

## 📊 Task 2: Exploratory Data Analysis (EDA) — Titanic Dataset

### 🔍 Objective
Perform data cleaning and EDA on the Titanic dataset to uncover patterns and relationships influencing passenger survival.

### 🛠️ Tools Used
- Python
- `pandas`, `matplotlib`, `seaborn`

### 🚀 What I Did
- Cleaned missing values
- Explored variables like `Sex`, `Pclass`, `Age`, and `Fare`
- Created plots: bar charts, histograms, heatmaps, box plots

### 📈 Key Insights
- Females and first-class passengers had higher survival rates
- Children had a slightly better chance of survival
- Strong correlation between fare and survival

---

## 🧠 Task 4: Sentiment Analysis — Amazon Reviews

### 🔍 Objective
Classify product reviews from Amazon as **Positive**, **Negative**, or **Neutral** using VADER sentiment analysis.

### 🛠️ Tools Used
- Python
- `pandas`, `vaderSentiment`, `seaborn`, `wordcloud`

### 🚀 What I Did
- Analyzed review text using VADER's compound score
- Created two columns: `VADER_Score` and `VADER_Sentiment`
- Visualized sentiment distribution and created optional word clouds

### 📈 Example Output

| Review                                      | VADER_Score | VADER_Sentiment |
|---------------------------------------------|-------------|-----------------|
| I absolutely love this product!             | 0.81        | Positive        |
| Terrible quality, very disappointed.        | -0.68       | Negative        |
| It's okay, not the best but not bad either. | 0.00        | Neutral         |

---

## 📂 Files Included

| Task | File(s) |
|------|---------|
| Task 1 | `web_scraper.py`, `books_data.csv` |
| Task 2 | `eda_titanic.ipynb` |
| Task 4 | `SentimentAnalysis.ipynb`, `sentiment_results.csv` |

**Dataset Download Link:**  
I created a Sentiment Analysis .ipynb using the dataset given below.

[Amazon Fine Food Reviews - Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
