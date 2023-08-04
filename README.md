# Fake News Detection Using  Machine Learning



# Overview
This project aims to identify false news using machine learning algorithms. I implemented four different classifiers: Decision Tree, Logistic Regression, Random Forest, and Passive Aggressive Classifier. By comparing the performance of each method, I selected the one with the highest accuracy, which turned out to be the Passive Aggressive Classifier.

# Dataset
I used a dataset containing labeled news articles, where each article was categorized as either REAL or FAKE news. The dataset was loaded using the pandas library from a CSV file. This data set was downloaded from Kaggle’s official website. This dataset is also small in size and requires a memory space of only 29.2 MB. It has a size of 7796*4.

# Technology Used
Python

Pandas

Scikit-learn

NumPy

Matplotlib

# Methodology
Data Preprocessing: I used the Tf-Idf vectorization technique to preprocess the text data, making it suitable for classification.

## Classifier Selection: 
The four classifiers were trained and evaluated on the preprocessed data. The Passive Aggressive Classifier showed the best performance and was chosen as the primary model.

## Model Evaluation:
 I assessed the performance of the selected model using various performance metrics to ensure its effectiveness in detecting false news.

## Results
The Passive Aggressive Classifier demonstrated superior performance compared to other classifiers, achieving an accuracy of 93%. The model's precision, recall, and F1-score were also high, indicating its effectiveness in identifying false news.

# Usage
To run the project, make sure you have Python and the required libraries installed. Then, clone the repository and run the main script to see the model in action.