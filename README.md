# Text-Classification for Authorship Attribution
Text classification is a fundamental task in the field of Artificial Intelligence, particularly in Natural Language Processing (NLP)
This project delves into the methodologies and models employed to achieve optimal accuracy in classifying texts from five Gutenberg books 
The goal is to accurately classify unseen text into the appropriate book category, showcasing the best-performing model's achievements.
### Dataset
The dataset used for this project is sourced from the Gutenberg corpus, which comprises a collection of over 60,000 book texts,along with their authors and titles
The data was extracted from the Project Gutenberg website using a custom script designed to parse bookshelves
The project focuses on five distinct samples of Gutenberg digital books, each authored by different individuals
These books belong to the historical genre and are semantically aligned.
### Methodology
The project follows a comprehensive approach to achieve accurate text classification:
1.	Text Preprocessing: Utilizing NLTK, the text is preprocessed by tokenizing, removing stopwords, and lemmatizingto ensure consistency and meaningful analysis.
2.	Feature Extraction: Various techniques such as Count Vectorization, TF-IDF (Term Frequency-Inverse Document Frequency), and Word2Vec are employed to convert text into numerical features.
3.	Model Selection: A range of classification models is evaluated, including Support Vector Machines (SVM), Random Forest, Naive Bayes, k-Nearest Neighbors (KNN), XGBoost, Stochastic Gradient Descent (SGD), Logistic Regression, Decision Trees, AdaBoost, and CatBoost.
4.	Evaluation: Models are assessed using classification metrics such as accuracy, confusion matrix, and classification report to identify the best-performing model.
### Installation
To run this project, install the required libraries using the following commands:
pip install nltk
pip install scikit-learn
pip install catboost
pip install xgboost

