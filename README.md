# SENTIMENT_ANALYSIS

📝 Sentiment Analysis on Twitter Data

💼 Internship Task 4 – NLP Project

This project performs **sentiment analysis** on real Twitter data using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques. The dataset used contains 2,034 tweets labeled as positive or negative.

📁 Dataset

- Source: STS-Gold Tweet Dataset
- File Used: `sts_gold_tweet.csv`
- Columns:
  - `id`: Tweet ID
  - `tweet`: Raw tweet text
  - `polarity`: Sentiment label (0 = negative, 4 = positive)

🎯 Project Objective

- Preprocess raw tweets using NLP techniques
- Train an ML model to classify tweets as positive or negative
- Visualize word frequency using WordClouds
- Evaluate model performance using accuracy and classification metrics

🔧 Tools & Technologies

- Python
- Jupyter Notebook
- Libraries: `pandas`, `nltk`, `scikit-learn`, `wordcloud`, `matplotlib`

🧪 Project Workflow

1. Load Dataset
2. Text Preprocessing
   - Remove punctuation, links, mentions
   - Tokenize, remove stopwords, lemmatize
3. Label Encoding
4. Train-Test Split
5. TF-IDF Vectorization
6. Logistic Regression Model
7. Evaluation Metrics
8. WordCloud Visualizations
   
📊 Model Evaluation

- Model: Logistic Regression
- Accuracy: 0.7985257985257985
- Classification Report: Includes precision, recall, F1-score

🌥️ WordCloud Insights

- Separate WordClouds were generated for:
  - Positive Tweets
  - Negative Tweets

These highlight the most frequent terms used per sentiment class.


✅ Outcomes

- Learned real-world application of NLP in classifying social media text
- Developed end-to-end pipeline from raw data to model evaluation
- Built resume-ready project demonstrating data science skills

📌 How to Run

1. Clone the repository
2. Open `sentiment_analysis_task4.ipynb` in Jupyter Notebook
3. Run all cells to see outputs
