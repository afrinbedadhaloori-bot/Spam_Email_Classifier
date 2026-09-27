# Spam Email Classifier

## Project Overview

This project is a Machine Learning-based Spam Email Classifier developed using Python. The main purpose of this project is to classify email messages into two categories: Spam and Ham (Not Spam).

## Objective

The objective of this project is to automatically identify whether an email message is Spam or Ham using Natural Language Processing (NLP) and Machine Learning techniques.

## Dataset

- Dataset Name: SMS Spam Collection Dataset
- Source: Kaggle / UCI
- File Name: spam.csv
- Labels: Spam and Ham

## Technologies and Tools Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm

The Machine Learning algorithm used in this project is:

- Multinomial Naive Bayes

Multinomial Naive Bayes is suitable for text classification problems. It is used to classify email messages based on the words present in the message.

## Project Methodology

The project follows these steps:

1. Define the objective of the project.
2. Collect the Spam and Ham email dataset.
3. Load the dataset using Pandas.
4. Preprocess the email text using NLP techniques.
5. Convert text into numerical features using TF-IDF Vectorization.
6. Split the dataset into training and testing data.
7. Train the Multinomial Naive Bayes model.
8. Evaluate the model using Accuracy, Precision, Recall, and F1-Score.
9. Test the classifier using new email messages.
10. Analyze and document the results.

## Text Preprocessing

The following preprocessing techniques are used:

- Convert text to lowercase.
- Remove punctuation and special characters.
- Remove stopwords using NLTK.
- Apply stemming using Porter Stemmer.

## Model Evaluation

The model is evaluated using the following performance metrics:

- Accuracy
- Precision
- Recall
- F1-Score

These metrics help measure how effectively the model classifies Spam and Ham messages.

## Testing

The trained model was tested using new email messages.

Example:

**Input:** Congratulations! You have won a free prize. Click now to claim your reward!

**Prediction:** Spam

**Input:** Hi, are we meeting tomorrow for the project?

**Prediction:** Ham

## Conclusion

The Spam Email Classifier successfully classifies email messages as Spam or Ham. The project demonstrates the application of Natural Language Processing and Machine Learning for automatic spam detection. The Multinomial Naive Bayes algorithm is used to train the classifier, and TF-IDF is used to convert text messages into numerical features.

## Project Files

- `Spam_Email_Classifier.ipynb` - Main Jupyter Notebook containing the project code.
- `spam.csv` - Dataset used for training and testing.
- `README.md` - Project documentation.

## Author

Machine Learning with Python - Minor Project