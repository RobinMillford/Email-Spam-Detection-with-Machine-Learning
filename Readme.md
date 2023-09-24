# Project Title: Email Spam Detection with Machine Learning

Project Summary:

In this project, I undertook the task of developing an email spam detection system using machine learning. Here's a summary of what I accomplished:

1. **Data Loading and Preprocessing:**
   - I successfully loaded a dataset containing email messages labeled as either "spam" or "ham" (non-spam).
   - I addressed and resolved a UnicodeDecodeError while reading the CSV file.
   - To ensure data cleanliness, I removed duplicate entries from the dataset.

2. **Text Data Transformation:**
   - I implemented a text preprocessing function that converted text to lowercase, tokenized it, removed stopwords and punctuation, and applied stemming.

3. **Exploratory Data Analysis (EDA):**
   - I visualized the distribution of the number of characters and words in both spam and ham emails.
   - I created word clouds to visually depict the most frequent words in spam and ham emails.

4. **Feature Engineering:**
   - I utilized CountVectorizer and TF-IDF Vectorizer to convert the text data into numerical features.

5. **Model Selection and Evaluation:**
   - I selected a variety of classifiers, including Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Multinomial Naive Bayes, Decision Tree, Logistic Regression, Random Forest, AdaBoost, Bagging, Extra Trees, Gradient Boosting, and XGBoost.
   - I trained and evaluated these classifiers using accuracy and precision scores.
   - I also compared the performance of these classifiers through bar plots.

6. **Ensemble Methods:**
   - I explored ensemble methods like the Voting Classifier and Stacking Classifier to combine the predictions of multiple base classifiers.

7. **Conclusion:**
   - After extensive experimentation and evaluation, I found that certain classifiers and ensemble methods performed well for email spam detection.
   - I used the Voting Classifier and Stacking Classifier to combine the strengths of multiple classifiers, achieving high accuracy and precision.
   - The choice of the best model depends on specific project requirements and trade-offs between accuracy and precision.

This project showcases the end-to-end process of email spam detection, from data preprocessing to model evaluation and ensemble techniques. It serves as a foundation for building a robust spam detection system and can be further improved and extended for real-world applications.
