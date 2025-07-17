# Twitter Sentiment Analysis

This project analyzes the sentiment of tweets as positive, negative, or neutral using machine learning.

## Project Structure

- `notebooks/1-data-cleaning.ipynb`: Jupyter notebook for data cleaning and preprocessing.
- `src/text_preprocessing.py`: Python module for text preprocessing (tokenization, stopword removal, stemming).
- `requirements.txt`: List of required Python packages.

## Getting Started

1. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

2. **Download NLTK data:**
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

3. **Run the notebook:**
   Open `notebooks/1-data-cleaning.ipynb` in Jupyter and execute the cells.

## Preprocessing

The [`preprocess_text`](src/text_preprocessing.py) function in [src/text_preprocessing.py](src/text_preprocessing.py) performs:
- Lowercasing
- Punctuation removal
- Tokenization
- Stopword removal
- Stemming

## Data

The notebook expects a CSV file at `../data/sentiment140.csv` with tweet data.
