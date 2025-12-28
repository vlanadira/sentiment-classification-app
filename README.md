### Welcome to the Steam Review Sentiment Analysis project!

This repository contains the complete implementation of my undergraduate thesis: **"IMPLEMENTATION OF CRISP-DM FOR SENTIMENT ANALYSIS ON STEAM GAME REVIEWS"**,
designed to classify game reviews into Positive or Negative sentiments. The project utilizes the CRISP-DM methodology and compares four Deep Learning architectures (LSTM, GRU, BiLSTM, BiGRU) with various imbalance handling techniques.

# Step 1: Install Python
Make sure Python is installed on your system

Recommeded version: Python 3.10-3.12
### Python : [![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org)

After installation, verify it by running:
```
python --version
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
```
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

> Results may slightly vary when using different library versions, especially for deep learning models.

# Step 2: Clone Repository & Create Virtual Environment
Using a virtual environment is highly recommended to avoid dependency conflicts.
Clone this repository or download it as ZIP
Open terminal / command prompt inside the project folder
Create a virtual environment:

```
python -m venv venv
```

Activate the environment:
### Windows

```
venv\Scripts\activate
```

### macOS / Linux

```
source venv/bin/activate
```

# Step 3: Install Dependencies
Install all required libraries using the provided requirements.txt:

```
pip install -r requirements.txt
```

If you are using **macOS with VS Code**, you can also install dependencies manually

```
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install streamlit tensorflow scikit-learn numpy pandas matplotlib
streamlit run app.py
```

# How to Use the App
## 1. Choose the Model
This project provides two Deep Learning models:
### 1. Best Performance Model
- Selected from 12 trained models
- Optimized based on evaluation metrics
### 2. Best General Model
More stable and balanced performance across different inputs

👉 Users can choose which model to use directly in the application.

## 2. Prepare Model Files
Make sure the following files exist in the project root directory
- sentiment_model.h5 – trained Deep Learning model
- tokenizer-3.pkl – tokenizer for text preprocessing

## 3. Run Streamlit

```
streamlit run app.py
```

## 4. Access the Web App
The app will automatically open in your browser:

```
http://localhost:8501
```

If not, copy the URL from the terminal and open it manually.

Enter any game review text and click **“Analyze Sentiment”**.

If you have any questions or issues running this project, feel free to reach out.

**Author:** Vladdifka Nadira Adha Adrian

**Email:** vladdifkandr13@gmail.com

**LinkedIn:** www.linkedin.com/in/vladdifka-nadira

Happy Coding & Gaming! 🎮
