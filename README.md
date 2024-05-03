# PDSFinal_Project
PDS Final Project Source Files ( Fake news Detection )
Fake News Detection Using Machine Learning


**Overview**


This repository contains the code and resources for a machine learning project aimed at detecting fake news articles. The project utilizes natural language processing techniques and supervised learning algorithms to classify news articles as either genuine or fake based on their content and features.

**Features**

**Data preprocessing:** Cleaning and preprocessing of raw text data, including tokenization, removal of stopwords, and feature extraction.
**Feature engineering:** Generation of informative features, such as text length, word count, punctuation count, capitalization ratio, and sentiment score, to capture linguistic and stylistic characteristics.
**Model training:** Training and evaluation of multiple classifiers, including Random Forest, XGBoost, Logistic Regression, and Decision Trees, to identify the most effective model for fake news detection.
**Real-time prediction:** Implementation of a real-time prediction functionality using the trained XGBoost classifier, enabling users to verify the credibility of news statements interactively.


**Requirements**

Python 3.x
Libraries: scikit-learn, XGBoost, nltk, matplotlib, seaborn

Clone the repository:
https://github.com/MallikarjunChalla/PDSFinal_Project.git
Install the required libraries

Place raw data files in the raw_data/ folder and preprocessed data files in the clean_data/ folder.

Run the main script to train the models and perform real-time predictions:
python main.py
File Structure
raw_data/: Directory containing the raw data files provided for the project.
clean_data/: Directory containing the preprocessed data files.
PDSFinal.ipynb: Jupyter Notebook file for data preprocessing. Main script for training models and performing real-time predictions.
Results/: Contains all the result screenshots
README.md: This file providing an overview of the project and instructions for usage.


**Contributors**

Bhavana Chunduri
Mallikarjun Challa
Risheet Yalamanchili
Yashwanth Katikaneni
