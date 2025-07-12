# Task 1 - Spam SMS Detection
# Spam SMS Detection 

A machine learning model that identifies whether an SMS is spam or legitimate, using text processing and classification techniques.

##  Objective

Classify SMS messages as **spam** or **not spam**, based on their content.

##  Dataset

- **Source**: [SMS Spam Collection Dataset by UCI / Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Description**: Contains 5,574 SMS messages in English, with 747 labeled as spam and 4,827 as ham 
- **Format**: Two-column CSV:
  - label: spam or ham
  - message: the text content of the SMS

##  Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK for preprocessing
- TF-IDF Vectorizer
- Models: Multinomial Naive Bayes and/or Logistic Regression

##  Workflow

1. Load and clean the dataset (spam.csv)
2. Preprocess text: remove punctuation, lowercase, remove stopwords
3. Convert text to numerical features with TF-IDF
4. Train classifiers to label spam vs ham
5. Evaluate using accuracy, precision, recall, F1-score

##  How to Run

```bash
git clone <repo-url>
cd Task_1
pip install -r requirements.txt
python main.py

