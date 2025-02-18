Toxic Comment Classification
Project Description
This repository contains the Python implementation for a text classification project designed to identify toxic comments. Utilizing data from the Jigsaw Toxic Comment Classification Challenge, the project employs a range of machine learning models such as Random Forest, Decision Trees, Linear SVC, XGBoost, and a deep learning model using TensorFlow. The project leverages various natural language processing (NLP) techniques to analyze and classify the text data effectively.

Data Source
The dataset used in this project is sourced from the Jigsaw Toxic Comment Classification Challenge, which features a large number of user comments annotated based on their toxicity.

NLP Techniques
The code incorporates the following NLP techniques:

Text Preprocessing: Normalization, tokenization, and removal of special characters.
Feature Extraction: Lexical features such as character count, word count, and sentence length; syntactic features using POS tagging; domain-specific features identifying toxic keywords.
Sentiment Analysis: Employing NLTK’s SentimentIntensityAnalyzer to derive sentiment scores.
Vectorization: Using TF-IDF to convert text data into a format suitable for machine learning model input.
Undersampling: Balancing the dataset using RandomUnderSampler to handle class imbalance.
Installation
Install the required Python libraries specified in the project files to set up the project environment.

Usage
Execute the script new_fea.py to process the dataset and train the models. Ensure the dataset train.csv is present in your project directory.

Contributing
Contributions are welcome to enhance the project's functionality and accuracy. Please fork the repository and submit pull requests for any improvements.
