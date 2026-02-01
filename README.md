Hate Speech and Offensive Language Detection

A machine learning based text classification system that detects hate speech, offensive language, and neutral text using classical NLP techniques and multiple models on a public labeled dataset. The project explores text preprocessing, vectorization techniques, and model comparison to find the best performing classifier.

Features

Preprocessing of textual data (cleaning, normalization)
Vectorization with TF-IDF / CountVectorizer
Train and compare multiple ML models (Logistic Regression, SVM, Naive Bayes, etc.)
Performance evaluation and accuracy comparison
Analysis of model results

Project Structure

Machine-Learning-Approach-for-Hate-Speech-and-Offensive-Language-Detection/
│
├── Hate Speech Detection.ipynb
├── Hate_Speech_Data.csv
├── Model Accuracies.xlsx
├── PPT.pptx
├── Project Report.pdf
├── Poster.pdf
├── Vectorization.docx
└── README.md

Tech Stack

Python, Jupyter Notebook, scikit-learn, pandas, NumPy, Matplotlib (for analysis if present)

How It Works

Dataset is loaded from Hate_Speech_Data.csv
Text cleaning and preprocessing steps are performed
Text is transformed into numeric features using TF-IDF or CountVectorizer
Multiple models are trained and evaluated
Model accuracy scores are recorded and compared
Best model is identified based on performance
