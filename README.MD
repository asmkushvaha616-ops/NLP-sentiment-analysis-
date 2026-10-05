# NLP Sentiment Analysis

## Overview

This project is a simple **Natural Language Processing (NLP)** project that performs **sentiment analysis** on text data.

The dataset contains short tweet-like text samples classified into three sentiment categories:

* **Positive**
* **Negative**
* **Neutral**

The project demonstrates the basic NLP pipeline, including text preprocessing, lemmatization, feature extraction, and sentiment classification.

## Dataset

The dataset contains **15 text samples**:

* 5 Positive
* 5 Negative
* 5 Neutral

Each sample contains:

* `text` — the input text
* `label` — the sentiment category

## NLP Workflow

The project follows these steps:

1. Create and load the dataset
2. Clean the text
3. Convert text to lowercase
4. Remove unnecessary characters and punctuation
5. Perform text preprocessing
6. Apply **WordNet Lemmatization**
7. Convert text into numerical features using **CountVectorizer**
8. Train a machine learning model
9. Predict the sentiment of new text

## Technologies Used

* Python
* Pandas
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

## Libraries

```python
import pandas as pd
import nltk
from nltk.stem import WordNetLemmatizer
from sklearn.feature_extraction.text import CountVectorizer
```

## Project Structure

```text
nlp-sentiment-analysis/
│
├── sentiment_analysis.ipynb
├── README.md
└── dataset/
```

## Sentiment Classes

| Label    | Meaning                                  |
| -------- | ---------------------------------------- |
| Positive | Expresses a positive opinion or feeling  |
| Negative | Expresses a negative opinion or feeling  |
| Neutral  | Expresses factual or neutral information |

## Example

```text
Input:
"I love this phone"

Output:
Positive
```

```text
Input:
"I hate this phone"

Output:
Negative
```

## Objective

The main objective of this project is to understand the fundamentals of **NLP and text classification** by converting human language into numerical features that can be processed by a machine learning model.

## Future Improvements

* Use a larger real-world dataset
* Apply TF-IDF feature extraction
* Compare different machine learning models
* Improve text preprocessing
* Evaluate model performance using accuracy, precision, recall, and F1-score
* Deploy the sentiment analysis model as a web application

