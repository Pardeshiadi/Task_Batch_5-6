# NLP Tasks - Krutika Borase

This folder contains 4 NLP (Natural Language Processing) tasks demonstrating various concepts and techniques.

## Files

1. **introduction_nlp.py** - Task 1: Sentiment Analysis
   - Analyzes movie reviews and classifies them as positive or negative
   - Uses Logistic Regression with TF-IDF features
   - Achieves ~82% accuracy on test data

2. **text_data_basics.py** - Task 2: Text Data Basics
   - Demonstrates text tokenization and analysis
   - Extracts sentences, tokens, and paragraph counts
   - Shows basic text structure understanding

3. **text_preprocessing.py** - Task 3: Text Preprocessing
   - Covers 6 preprocessing techniques:
     - Tokenization (NLTK vs spaCy)
     - Stopwords removal
     - Lemmatization & Stemming
     - Special character and emoji cleaning
     - Lowercasing & normalization
     - Regex patterns

4. **bow_tfidf.py** - Task 4: Feature Extraction
   - Demonstrates Bag-of-Words (BoW) and TF-IDF vectorization
   - Compares word importance scores
   - Shows how text is converted to numerical features

## How to Run

Activate the virtual environment:
```bash
.\venv311\Scripts\activate
```

Run any task:
```bash
python introduction_nlp.py
python text_data_basics.py
python text_preprocessing.py
python bow_tfidf.py
```
