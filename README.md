# 28_KhanJarjish_Assignment2
README.md

📊 Text Analytics – Sentiment Analysis
(1) Problem Statement

Social media platforms generate a massive amount of textual data every day. Understanding user sentiment from this data is crucial for decision-making in industries such as entertainment, marketing, and product development.

The challenge is to automatically classify tweets related to a movie into positive, neutral, or negative sentiments using machine learning techniques.

(2) Objective
Perform sentiment analysis on movie-related tweets
Classify tweets into positive, neutral, and negative categories
Implement and compare different machine learning models:
Naïve Bayes
Support Vector Machine (SVM)
Logistic Regression
Evaluate model performance using precision and recall
(3) Dataset

Source: Manually created dataset (simulated tweets)

Features:

tweet_id → Unique identifier for each tweet
text → Tweet content
sentiment → Sentiment label (positive / neutral / negative)

Dataset Size:

Total: 100 tweets
Training: 80 tweets
Testing: 20 tweets
(4) Methodology
1. Data Preprocessing
Loaded dataset using Pandas
Split data into training (80%) and testing (20%) sets
Converted text into numerical features using TF-IDF Vectorization
Removed stopwords for better text representation
2. Exploratory Data Analysis (EDA)
Analyzed distribution of sentiment classes
Verified dataset balance across positive, neutral, and negative labels
3. Model Building

Implemented the following machine learning models:

Naïve Bayes (MultinomialNB)
Support Vector Machine (LinearSVC)
Logistic Regression
4. Evaluation Metrics
Precision
Recall
Classification Report
Confusion Matrix
Visualization using bar charts
(5) Results
Model	Precision	Recall
Naïve Bayes	~0.55	~0.55
SVM	~0.65	~0.65
Logistic Regression	~0.47	~0.47
Key Insights
SVM achieved the best performance among all models
Naïve Bayes performed moderately well
Logistic Regression showed comparatively lower performance
Misclassification mainly occurred between neutral and positive tweets
Performance is limited due to the small dataset size
(6) How to Run
pip install -r requirements.txt
python main.py
(7) Conclusion

This project demonstrates how machine learning techniques can be used to perform sentiment analysis on textual data. Among the implemented models, Support Vector Machine (SVM) performed the best.

The results can be further improved by:

Using a larger dataset
Incorporating real-world noisy data
Applying advanced techniques such as deep learning models
(8) Student Details
Name: Khan Jarjish
Roll No: 28
UIN: 231A034
Year: TE-AIDS 2026


