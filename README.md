#Sentiment Analysis of Movie Reviews

Overview
This project performs sentiment analysis on movie reviews using machine learning classifiers. It involves importing libraries, data preprocessing, feature extraction, model training, evaluation, and visualization.

Importing Libraries and Setup
Libraries such as pandas, numpy, nltk, and scikit-learn are imported to handle data processing and machine learning tasks. The movie_reviews dataset from NLTK is used, and a utility function is defined to convert reviews into string format.

Data Preprocessing
Reviews are collected from positive and negative categories and converted into string format. Labels are created where positive reviews are marked as 1 and negative reviews as 0.

Data Visualization
Distribution of Sentiments: A count plot visualizes the distribution of positive and negative reviews.
Word Clouds: Separate word clouds are generated for positive and negative reviews to showcase frequently used words.
Feature Extraction
Two methods are used to extract features from the review texts: Count Vectorizer and TF-IDF Vectorizer. These methods transform the text data into a format suitable for machine learning models.

Model Implementation and Evaluation
Three classifiers are applied: Multinomial Naive Bayes, Logistic Regression, and Support Vector Machine (SVM). Each model is evaluated using accuracy scores and confusion matrices.

Results and Visualization
Confusion Matrix: A heatmap visualizes the confusion matrix for the Naive Bayes model using TF-IDF.
Model Accuracies: A bar plot compares the accuracies of all classifiers.
ROC Curve: The ROC curve is plotted for Naive Bayes (TF-IDF) to assess its performance.
