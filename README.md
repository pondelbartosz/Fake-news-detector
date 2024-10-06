# Fake_news_detector

## Description

The goal of the project was to build and train several machine learning models used for fake news detection. After installing and importing the necessary libraries, the data was loaded and analyzed. The data was properly cleaned (removal of unnecessary columns, duplicates, text normalization, removal of links, mentions, symbols, stopwords, and lemmatization) to feed the ML models. Then, the textual data was converted into numerical data using the Word2Vec library. Three ML models were used for fake news detection: logistic regression, random forest, and SVM. After training these models, a hyperparameter analysis was conducted using GridSearch. The models were then retrained using the best parameters. The final step was comparing the model results before and after hyperparameter optimization.


## Files
- 'data.csv' - source file with data used in the project
- 'Fake_news_detector.ipynb' - Python notebook with the analysis

## Technologies
- Python
- Vord2Vec
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine
- Grid Search
