# Support Ticket Classification and Priority Prediction using NLP

## Project Overview

This project is a Machine Learning and Natural Language Processing (NLP) based system developed to automatically classify customer support tickets and predict their priority levels. The system helps organizations reduce manual ticket sorting and improve customer support operations.

The model analyzes customer ticket descriptions and predicts:

* Ticket Category
* Ticket Priority

This project demonstrates the practical application of NLP and Machine Learning in real-world customer support systems.

---

## Features

* Text preprocessing and cleaning
* Stopword removal and tokenization
* TF-IDF feature extraction
* Ticket category classification
* Ticket priority prediction
* Machine Learning model training
* Model evaluation using accuracy and classification report
* Custom ticket prediction support

---

##  Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TF-IDF Vectorizer
* Logistic Regression

---

##  Dataset

Dataset Used:
Customer Support Ticket Dataset from Kaggle

Dataset contains:

* Ticket Description
* Ticket Type
* Ticket Priority
* Customer Information
* Ticket Status

---

##  Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Vectorization
5. Train-Test Split
6. Logistic Regression Model Training
7. Ticket Category Prediction
8. Ticket Priority Prediction
9. Model Evaluation

---

##  Model Used

* Logistic Regression

---

## Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Example Prediction

### Input Ticket

"My payment failed and money was deducted"

### Predicted Output

* Category: Billing Inquiry
* Priority: High

---

# Business Impact

This project helps organizations:

* Reduce manual ticket sorting
* Improve customer support efficiency
* Prioritize urgent issues faster
* Improve response time
* Enhance customer satisfaction

#How to Run the Project

1. Install required libraries:
   pip install -r requirements.txt

2. Open Jupyter Notebook:
   jupyter notebook

3. Run the notebook:
   support_ticket_classifier.ipynb
