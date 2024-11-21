
# Task 4: Spam Classification Using SVM

This project focuses on classifying SMS messages into two categories: spam or not spam (ham). The classification is performed using a Support Vector Machine (SVM) model and TF-IDF vectorization for text feature extraction.

## Features
- **Data Preprocessing**:
  - Handle missing values and combine redundant columns in the dataset.
  - Rename columns for better readability.
  - Encode the message category (`spam` as 1, `ham` as 0).
- **Text Vectorization**:
  - Convert text messages into numerical features using `TfidfVectorizer`.
- **Model Training**:
  - Train a **Support Vector Machine (SVM)** classifier on the transformed data.
- **Model Evaluation**:
  - Evaluate the model using accuracy, a classification report, and a confusion matrix.
 
## Dataset
The dataset used is spam.csv, which contains the following columns:
- v1: The category of the message (spam or ham).
- v2: The message body.
- Additional columns (Unnamed: 2, Unnamed: 3, Unnamed: 4) with redundant data are merged into the message body and then dropped.

## Results
### Model Performance:
- Displays the accuracy score.
- Prints a detailed classification report.
### Confusion Matrix:
- Visual heatmap representation of classification accuracy.
