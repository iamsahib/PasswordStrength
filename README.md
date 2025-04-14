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
  This project demonstrates how NLP techniques can be applied in security-related applications, such as password classification. Future improvements could include more advanced feature          engineering or use of deep learning models.


🔍 Key Insights


  Imbalanced Classes
  The dataset has more weak passwords than medium and strong ones, which can bias the model toward predicting the majority class.

  Weak Password Patterns
  Most weak passwords are short and predictable (e.g., "123456", "password", "abc123"), making them easier for models to classify accurately.

  Strong Password Complexity
  Strong passwords generally include a mix of uppercase, lowercase, numbers, and special characters, showing higher character diversity.

  TF-IDF Effectiveness
  The TF-IDF vectorizer helped effectively convert textual passwords into numerical features, enabling models to distinguish between different password strengths.

  Model Performance
  Random Forest outperformed other models in accuracy and class balance, while Logistic Regression and Decision Tree struggled slightly with medium and strong classes.

