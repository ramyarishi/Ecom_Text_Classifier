📦 Product Category Classification using NLP
Build a machine learning model to automatically classify product descriptions into one of four categories using Natural Language Processing techniques.

💼 Problem Statement
Businesses often have thousands of product listings. Manually tagging them into categories like Books, Electronics, Clothing & Accessories, and Household is inefficient and prone to errors.

The goal of this project is to:

Automatically classify product descriptions based on their textual content

Enable faster cataloging and better search optimization

Improve user experience through accurate product categorization

🧾 Dataset Overview
📄 4,000 records × 2 columns


Column	Description
message	Product description (text)
label	Product category (target: 4 classes)
🎯 Target Categories:

0 → Books

1 → Clothing & Accessories

2 → Electronics

3 → Household

✅ Balanced dataset: 1000 records per category
✅ No missing values

🧠 Techniques Used
📚 Supervised Learning – Text Classification
🔡 Natural Language Processing (NLP)

Text Cleaning (Regex, Lowercasing, Stopword Removal)

Stemming using NLTK's PorterStemmer

Vectorization using CountVectorizer

🤖 Model Used

Multinomial Naive Bayes Classifier

📈 Evaluation

Accuracy on Train & Test sets

Cross-validation scores

Misclassification checks

🔍 Project Workflow
Data Preprocessing

Clean raw text (remove punctuation, lowercase, stopwords, stemming)

Convert text to numerical features using CountVectorizer

Model Building

Split dataset into training and testing

Train MultinomialNB classifier

Evaluation

Check train/test accuracy

Cross-validation for generalization

Prediction Interface

Built using Flask to allow real-time prediction of new product descriptions

🧪 Sample Prediction
Input:
"This 4K smart TV with voice control and wireless connectivity offers an immersive viewing experience."

Predicted Category:
Electronics

🧰 Tech Stack
Python

Pandas, NumPy

NLTK, Scikit-learn

Flask (for web deployment)

Jupyter Notebook (for training & analysis)

🖼️ Web App Screenshot
(📸 Add your Flask app UI screenshot here)
