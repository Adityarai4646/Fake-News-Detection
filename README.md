Fake News Detection using NLP and Machine Learning:

A machine learning project to classify news articles as **real** or **fake** using Natural Language Processing (NLP) techniques. This beginner-friendly project demonstrates the full ML pipeline: from data cleaning and vectorization to model training and evaluation.


 Overview

-  Problem: Fake news spreads rapidly and misleads readers.
-  Goal: Build a model to accurately detect fake news based on article content.
-  Solution: Use TF-IDF + Naive Bayes classifier.

---

Technologies Used:

- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Google Colab

 Dataset:

- Source: [Kaggle - Fake News](https://github.com/Adityarai4646/Fake-News-Detection.git)
- File Used**: `train.csv`
- Contains news article text and corresponding labels: `REAL` or `FAKE`.


Workflow:

1. Load and explore dataset
2. Handle missing/null values
3. Text preprocessing and cleaning
4. Convert text to numeric vectors using **TF-IDF**
5. Split data into training/testing sets
6. Train a Multinomial Naive Bayes model
7. Evaluate model (Accuracy, Confusion Matrix)
8. Build a function to manually check your own news


Example Output:

python
check_news("NASA discovers a new black hole near Earth!")
