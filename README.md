# NLP Recommendation System (TF-IDF)

Content-based recommendation system using NLP preprocessing and TF-IDF vectorization to recommend similar items based on text.

## What it does
- Cleans text (stopword removal, normalization)
- Builds TF-IDF vectors
- Computes similarity (cosine similarity)
- Returns top-N recommendations for a given item

## Tech stack
- Python
- Pandas / NumPy
- scikit-learn (TF-IDF)
- WordCloud (EDA)

## Project structure
nlp-recommendation-system/
├── data/
│   └── movies.csv              # your dataset (local)
├── src/
│   ├── preprocess.py
│   ├── vectorizer.py
│   ├── recommender.py
│   └── __init__.py
├── main.py
├── requirements.txt
└── README.md
