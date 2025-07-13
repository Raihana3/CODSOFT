# Task 1 - Spam SMS Detection
# Spam SMS Detection 

A machine learning model that identifies whether an SMS is spam or legitimate, using text processing and classification techniques.

##  Objective

Classify SMS messages as **spam** or **not spam**, based on their content.

##  Dataset

- **Source**: [SMS Spam Collection Dataset by UCI / Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Description**: Contains 5,572 SMS messages in English, with 747 labeled as spam and 4,825 as ham 
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

1. Clone the Repository:
   
   git clone https://github.com/Raihana3/CODSOFT.git
   
   cd CODSOFT/Task1_SPAM_SMS_DETECTION

2. Install Required Libraries
   
   Make sure the following Python packages are installed:
   ```bash
       pip install pandas scikit-learn nltk
       pip install matplotlib seaborn

3. Open jupyter Notebook
   
     Then open the file: 'spam_sms_detection.ipynb'

4. Run the Notebook
   
      Step through each cell to:
      - Preprocess the data
      - Train the model
      - Evaluate the results

