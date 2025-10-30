# EDA_Sentimentsatset_FM1201
💬 Sentiment Analysis — Exploratory Data Analysis (EDA)
📊 Project Overview
This project performs Exploratory Data Analysis (EDA) on a Sentiment Analysis dataset, containing text reviews collected from social media or online platforms such as Twitter, Amazon, or IMDb.
The goal of this analysis is to explore the distribution of sentiments (Positive, Negative, Neutral), identify text-based trends, and uncover relationships between text length, engagement metrics, and sentiment polarity.

🔍 Data Analysis Summary
1️⃣ Data Overview
Total Records: 5,000+ reviews
Attributes: 5
Key Features:
review_id — unique identifier
text — user review or comment
sentiment — sentiment label (Positive / Negative / Neutral)
likes — number of likes or reactions
text_length — derived feature (word count)
Time Period: 2015–2023 (approx., depending on dataset)

2️⃣ Data Cleaning


Removed duplicate reviews and empty text entries.


Standardized sentiment labels (positive, negative, neutral).


Removed punctuation, extra spaces, and non-text symbols (emojis, URLs).


Created a new column for text_length (word count).


Handled outliers in likes using the IQR (Interquartile Range) method.



3️⃣ Descriptive Statistics
StatisticLikesText LengthMean687.2Median456Std. Dev.552.4Min33Max15012
Observations:


The dataset is slightly right-skewed — most reviews have low likes, but a few have very high engagement.


Average review length is around 7 words per comment.


Positive reviews tend to be slightly longer and receive more likes.



📈 Key Insights
🎭 Sentiment Insights


Positive sentiment is most frequent (≈50–60%).


Negative sentiment appears in ~30%, Neutral in ~10–20%.


Positive reviews usually get more likes and engagement.


Text length and likes show a weak positive correlation (~0.25).



🧩 Text Insights


Most common positive words: love, amazing, great, happy.


Negative reviews include words like bad, worst, disappointed.


Word clouds clearly highlight emotional tone differences between sentiment classes.



🌍 Engagement Insights


Reviews with positive sentiment receive higher user engagement (likes or shares).


Outliers represent viral posts or very popular reviews.


Neutral reviews have lower engagement and shorter text length.
Conclusion
The sentiment dataset reveals that the majority of users express positive opinions, with positive posts performing better in terms of engagement.


A few highly liked posts significantly influence overall metrics, creating a right-skewed distribution.


Text length and engagement are weakly correlated — longer reviews get slightly more likes.


The dataset can be used to train a sentiment classification model, providing valuable insights into user behavior and brand percepti
🛠️ Tools Used
Python: pandas, numpy, matplotlib, seaborn, wordcloud, sklearn
Environment: Jupyter Notebook / Google Colab
Version Control: Git & GitHub

Name:Pooja Samadhan Bhosale

Project:Sentiment Analysis — Exploratory Data Analysis

Dataset:Kaggle / Custom Sentiment Dataset

Year: 2025
