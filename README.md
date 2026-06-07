# IMDB Movie Review Sentiment Analysis

## Project Overview

This project implements a complete Natural Language Processing (NLP) pipeline for sentiment analysis using the IMDB Movie Reviews Dataset. The objective is to preprocess movie reviews and prepare them for training deep learning models that can classify reviews as either positive or negative.

The project covers:

* Dataset download and extraction
* Text preprocessing and cleaning
* Stopword removal
* Tokenization
* Sequence padding
* Dataset splitting into training, validation, and testing sets

---

## Dataset

The project uses the **IMDB Large Movie Review Dataset** developed by Stanford University.

* Total Reviews: 50,000
* Positive Reviews: 25,000
* Negative Reviews: 25,000

Dataset Source:
https://ai.stanford.edu/~amaas/data/sentiment/

---

## Features

### Data Acquisition

* Automatically downloads the IMDB dataset.
* Extracts the compressed dataset.
* Organizes positive and negative reviews.

### Data Preprocessing

* Removes HTML tags.
* Removes special characters and numbers.
* Converts text to lowercase.
* Removes English stopwords using NLTK.

### Text Processing

* Converts text into numerical sequences using Keras Tokenizer.
* Handles out-of-vocabulary words.
* Pads sequences to a fixed length.

### Dataset Preparation

* Creates labels for sentiment classification:

  * Positive = 1
  * Negative = 0
* Splits data into:

  * Training Set (70%)
  * Validation Set (15%)
  * Test Set (15%)

---

## Technologies Used

* Python
* TensorFlow / Keras
* Pandas
* NLTK
* Scikit-Learn
* NumPy

---

## Running the Project

Run the Python script:

```bash
python sentiment_analysis.py
```

The script will:

1. Download the IMDB dataset.
2. Extract dataset files.
3. Clean and preprocess reviews.
4. Tokenize text data.
5. Pad sequences.
6. Split data into train, validation, and test sets.
7. Compare the performance of RNN, LSTM and Transformer

---

## Learning Outcomes

This project demonstrates:

* Natural Language Processing (NLP)
* Text preprocessing techniques
* Sentiment Analysis
* Data preparation for Deep Learning
* TensorFlow/Keras Tokenization and Padding
* Machine Learning workflow

---

## Author

Rafia Arshad

---

## License

This project is intended for educational and research purposes.
