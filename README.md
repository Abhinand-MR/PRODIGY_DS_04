# PRODIGY_DS_04
# Task 04 – Twitter Sentiment Analysis using NLP

## 🎯 Objective
Analyze sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or entities using Natural Language Processing (NLP).

## 📎 Dataset
- Source: [Twitter Entity Sentiment Analysis Dataset – Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)
- The dataset includes tweets along with associated entities and sentiment labels (positive, neutral, negative).

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- NLTK / spaCy (for text preprocessing)
- TextBlob / VADER (for sentiment scoring)
- WordCloud
- Matplotlib
- Seaborn

## ⚙️ Task Workflow

1. **Data Loading**
   - Imported the dataset into a Pandas DataFrame.

2. **Text Preprocessing**
   - Lowercased text, removed punctuation and special characters.
   - Removed stopwords using NLTK.
   - Tokenized and lemmatized the tweets.

3. **Sentiment Classification**
   - Used either VADER or TextBlob to assign sentiment scores.
   - Classified tweets into `Positive`, `Neutral`, or `Negative` categories based on polarity scores.

4. **Visualization**
   - Created a pie chart for sentiment distribution.
   - Generated **word clouds** for each sentiment category.
   - Created bar plots showing frequency of entities by sentiment.

5. **Insights**
   - Determined overall public sentiment toward certain brands or entities.
   - Identified most common words and topics in each sentiment class.

## 📊 Output

- Sentiment distribution (positive/neutral/negative)
- Word clouds for each sentiment category
- Bar plots of entity sentiment trends

## 📷 Sample Visuals
*(Optional: Include `sentiment_pie_chart.png`, `positive_wordcloud.png`, `negative_wordcloud.png`, etc.)*

## ✅ Learnings

- Gained hands-on experience in text preprocessing techniques such as tokenization, stopword removal, and lemmatization.
- Learned to apply sentiment analysis using TextBlob or VADER.
- Explored visual techniques like word clouds and sentiment plots to summarize large volumes of text data.
- Understood the role of NLP in extracting opinions from social media.

## 📂 Folder Structure

