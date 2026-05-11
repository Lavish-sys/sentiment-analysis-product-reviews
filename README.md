# 🛍️ Sentiment Analysis on Product Reviews

## 📌 Overview

This project analyzes customer product reviews using Natural Language Processing (NLP) techniques to identify customer sentiment as Positive, Negative, or Neutral.

The goal of the project is to automate sentiment classification and generate meaningful insights from customer feedback data. The analysis helps understand customer satisfaction trends and common concerns in product reviews.

The project follows a complete data analysis workflow including:

* Data cleaning
* Text preprocessing
* Sentiment analysis
* Data visualization
* Business insights generation

---

## 🎯 Objective

* Analyze customer reviews from an e-commerce dataset
* Classify reviews into Positive, Negative, and Neutral sentiments
* Identify common customer satisfaction patterns
* Generate visual insights from sentiment trends
* Understand customer complaints and feedback behaviour

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **TextBlob**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📂 Dataset

Dataset used: **Amazon Fine Food Reviews Dataset**

Source:
Kaggle – Amazon Fine Food Reviews

* Used first 5,000 rows for analysis
* Dataset contains customer review text and product ratings

---

## 🔄 Workflow

### 1. Data Loading & Exploration

* Loaded dataset using Pandas
* Explored dataset structure and review columns
* Checked dataset dimensions and previewed records

### 2. Data Cleaning

* Removed null and empty review text
* Removed duplicate reviews
* Selected relevant columns for analysis

### 3. Sentiment Analysis

* Applied TextBlob sentiment polarity scoring
* Classified reviews into:

  * Positive
  * Negative
  * Neutral

### 4. Data Visualization

Created multiple visualizations including:

* Sentiment distribution bar chart
* Sentiment percentage pie chart
* Rating vs sentiment analysis chart

### 5. Business Insights

* Identified customer satisfaction trends
* Analyzed common patterns in negative reviews
* Generated recommendations based on customer feedback

---

## 📊 Visualizations

### Sentiment Distribution

* Compared count of Positive, Negative, and Neutral reviews

### Sentiment Percentage Analysis

* Visualized overall sentiment share using pie chart

### Rating vs Sentiment Analysis

* Compared review ratings with predicted sentiment categories

---

## 🔍 Key Insights

* Majority of reviews were classified as Positive
* Negative reviews commonly mentioned product quality and delivery-related issues
* Ratings strongly aligned with sentiment polarity
* Customer feedback data can help businesses improve product and service quality

---

## 📁 Project Structure

```bash
sentiment-analysis-product-reviews/
│
├── data/
│   └── Reviews.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── charts/
│   ├── sentiment_distribution.png
│   ├── sentiment_pie_chart.png
│   └── rating_vs_sentiment.png
│
├── summary/
│   └── summary.pdf
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/sentiment-analysis-product-reviews.git
```

2. Install dependencies

```bash
pip install pandas matplotlib seaborn textblob
```

3. Run the notebook

```bash
jupyter notebook
```

4. Open and execute:
   `analysis.ipynb`

---

## 💡 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* NLP Basics
* Sentiment Analysis
* Data Visualization
* Business Insight Generation

---

## 📈 Future Improvements

* Use advanced NLP models like VADER or BERT
* Deploy as a web application using Streamlit
* Perform word cloud and topic modeling analysis
* Train custom sentiment classification models
