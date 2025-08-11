readme_sentiment = """# 📝 Amazon Reviews Sentiment Analysis

## 📌 Overview
This project performs **sentiment analysis** on Amazon product reviews using **TextBlob**.  
It analyzes the polarity of customer reviews and categorizes them as Positive, Negative, or Neutral.

---

## 🗂️ Dataset
- File: `Reviews.csv`
- Source: Kaggle - Amazon Fine Food Reviews

---

## 🎯 Objectives
✅ Perform sentiment analysis on text reviews  
✅ Categorize reviews as Positive, Neutral, or Negative  
✅ Visualize sentiment distribution  

---

## 🛠️ Tools Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **TextBlob** for sentiment polarity
- **Jupyter Notebook**

---

## 📊 Workflow
1. Load dataset (`Reviews.csv`)
2. Compute polarity using TextBlob
3. Classify reviews as Positive, Negative, Neutral
4. Visualize sentiment distribution with Seaborn

---

## 🚀 How to Run
1. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn textblob
   python -m textblob.download_corpora
