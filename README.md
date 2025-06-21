# Sentiment-Analysis-of-Indian-Elections
This project aims to analyze public sentiment around key Indian political leaders, namely Narendra Modi and Rahul Gandhi, during the election season using tweets collected from online sources. The analysis helps understand how people feel about these leaders based on social media content and public discussions on Twitter.

 📌 Project Overview

- **Project Type:** Data Analysis & Natural Language Processing (NLP)  
- **Focus:** Indian General Elections – Public sentiment comparison between Narendra Modi & Rahul Gandhi  
- **Primary Tools:**  
  - **Excel**: For initial data cleaning and formatting  
  - **Python (Jupyter Notebook)**: For preprocessing, sentiment classification, and visualization  
  - **Libraries:** Pandas, NLTK, TextBlob, VADER, Scikit-learn, Seaborn, Matplotlib



🔧 Workflow Summary

 1. Data Cleaning (Excel & Python)
- Removed null values and duplicates  
- Cleaned text: removed hashtags, mentions, URLs, emojis, and special characters  
- Standardized format for easy processing in Python

2. Text Preprocessing
- Tokenization  
- Stopword removal using NLTK  
- Lemmatization and lowercasing  
- Created a clean corpus for analysis

3. Sentiment Analysis
- Applied **TextBlob** and **VADER** for sentiment scoring  
- Classified tweets as **Positive**, **Negative**, or **Neutral**  
- Mapped sentiment with leader mentions

 4. Data Visualization
- Word clouds for most frequent terms  
- Sentiment distribution charts for both leaders  
- Comparative bar plots and time-based trend lines

5. Optional Modeling (if done)
- Trained basic ML classifiers (e.g., Naive Bayes)  
- Evaluated using accuracy, precision, and recall metrics  



 📊 Key Insights

- Public opinion on both leaders varies with timing and events.
- Narendra Modi had a higher tweet volume and more extreme sentiments (both positive and negative).
- Rahul Gandhi's mentions were often more neutral, with peaks around debates and media appearances.



## 📁 Project Structure
Tools & Technologies Used

| Task | Tools Used |
|------|------------|
| Data Cleaning | Microsoft Excel |
| Programming | Python, Jupyter Notebook |
| NLP & Sentiment Analysis | NLTK, VADER, TextBlob |
| Visualization | Seaborn, Matplotlib, WordCloud |
| ML (if applicable) | Scikit-learn |



 🚀 Future Scope

- Include more leaders or party-level sentiment analysis  
- Stream real-time tweets using Twitter API  
- Build a **Streamlit** or **Power BI** dashboard  
- Enhance prediction accuracy using **LSTM** or transformer models

