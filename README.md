# PasswordStrength

**Title: Password Strength Classification using NLP**

**Objective:**
This project aims to classify the strength of passwords (e.g., weak, medium, strong) using Natural Language Processing (NLP) techniques. By analyzing password text data and applying feature extraction (like TF-IDF) and machine learning models (Logistic Regression, Random Forest, etc.), we can predict the security level of a given password. This can be useful for improving authentication systems and user password guidelines.

🛡️ Password Strength Classification using NLP
📌 Objective
To develop a machine learning model that predicts the strength of passwords based on their textual features using Natural Language Processing techniques.

🔍 Dataset
Contains a list of passwords labeled as Weak, Medium, or Strong.

Target column: strength

Features: password

🧪 Technologies Used
Python

Pandas, Numpy

Matplotlib, Seaborn (for EDA)

Scikit-learn

NLP (TF-IDF Vectorizer)

🧭 Workflow
Data Loading and Exploration

Read CSV dataset.

Visualized the distribution of password strengths.

Data Cleaning

Checked and handled missing/null values.

Mapped numerical labels (0,1,2) to Weak, Medium, Strong.

Text Preprocessing

Applied TF-IDF vectorization to transform password text into numerical features.

Model Building

Split the data into training and test sets.

Trained multiple classification models:

Logistic Regression

Random Forest

Decision Tree

K-Nearest Neighbors

Model Evaluation

Compared model performance using accuracy score and classification report.

Displayed confusion matrix for the best-performing model.

📊 Results
Achieved high accuracy in predicting password strength using text-based features.

Random Forest Classifier performed best (you can update this if another model wins).

✅ Conclusion
This project demonstrates how NLP techniques can be applied in security-related applications, such as password classification. Future improvements could include more advanced feature engineering or use of deep learning models.

💡 Recommendations
Try using n-grams in TF-IDF vectorizer to capture patterns like abc, 123, @!#.

Evaluate using cross-validation instead of a single train-test split.

You can explore LSTM models using Keras for sequential learning (optional advanced task).

Add an interactive Streamlit app that lets users input a password and see the strength prediction.



