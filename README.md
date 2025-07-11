# Email Spam Detection with Machine Learning

This project uses Natural Language Processing (NLP) and Machine Learning to classify emails as **Spam** or **Ham** (not spam). It's a beginner-friendly project built using Python and Scikit-learn, and implemented in Google Colab.

## Tech Stack

- Python 
- Pandas, NumPy 
- Scikit-learn (CountVectorizer, Naive Bayes) 
- Matplotlib, Seaborn (for visualization) 
- WordCloud 
- Google Colab 

## Dataset

- [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Contains over 5,500 messages labeled as `ham` (legit) or `spam`.

## Features

- Data Cleaning (duplicates, nulls)
- Word Frequency Visualization (WordCloud)
- Text Vectorization using CountVectorizer
- Spam Classification using Multinomial Naive Bayes
- Performance evaluation with Confusion Matrix & Classification Report
- Custom prediction for user input messages

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run each cell step by step
3. Try your own message in the custom function:
```python
check_spam("Congratulations! You've won a free iPhone!")
