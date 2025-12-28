## Welcome to the Steam Review Sentiment Analysis project!

This repository contains the complete implementation of my undergraduate thesis: **"IMPLEMENTATION OF CRISP-DM FOR SENTIMENT ANALYSIS ON STEAM GAME REVIEWS"**,
designed to classify Steam game reviews into Positive or Negative sentiments. The project utilizes the CRISP-DM methodology and compares four Deep Learning architectures (LSTM, GRU, BiLSTM, BiGRU) with various imbalance handling techniques. The final deployed model uses BiLSTM with Class Weighting for optimal performance.

## Environment Specifications
# Step 1: Install Python
Make sure Python is installed on your system

Recommeded version: Python 3.10-3.12
### Python : [![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org)

After installation, verify it by running:
```python --version
```

| Library | Minimum Version | Tested Version |
|--------|----------------|----------------|
| pandas | >= 2.0.0 | 2.2.2 |
| numpy | >= 1.26.0 | 2.0.2 |
| matplotlib | >= 3.7.0 | 3.10.0 |
| seaborn | >= 0.13.0 | 0.13.2 |
| scikit-learn | >= 1.3.0 | 1.6.1 |
| nltk | >= 3.8.1 | 3.9.1 |
| tensorflow | >= 2.16.0 | 2.19.0 |
| keras | >= 3.5.0 | 3.10.0 |
| wordcloud | >= 1.9.3 | 1.9.3 |

### NLTK Resources
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')

> *Results may slightly vary when using different library versions, especially for deep learning models.*

