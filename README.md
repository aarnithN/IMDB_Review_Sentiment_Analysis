# Sentiment Analysis on IMDB Reviews

This project uses NLP techniques such as tokenization and stemming to classify IMDB movie reviews as positive or negative based on each review's content.

## Dataset
- Public IMDB Dataset consisting of 50K movie reviews on Kaggle.

## Project Steps
- Text-preprocessing pipeline(regex,tokenization,stopword removal, stemming)
- Feature transormation using CountVectorizer
- Training multiple models (Logistic Regression, Naive Bayes, Decision Tree, Random Forest)
- Achieved ~85% accuracy utlizing over 9,000+ reviews


## Setup Instructions
```bash 
pip install -r requirements.txt

jupyter notebook imdb-review-sentiment-analysis.ipynb
```

## Results
- Logistic Regression performed the best with large amounts of data
- Model can be tuned to other sentiment analysis tasks







