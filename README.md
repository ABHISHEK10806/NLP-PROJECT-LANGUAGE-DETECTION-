# 📌 NLP Mini Project: Language Detection System-

🎯 Project Overview

Is project ka main goal text se language identify karna hai using Natural Language Processing (NLP) techniques.

Humne ek multilingual dataset use kiya jisme English, French, Spanish, Hindi, Tamil jaise kaafi languages available hain.




📂 Dataset

- Dataset ka naam: Language Detection Dataset
- Columns:
  - Text → Input sentence
  - Language → Target language label




⚙️ Methodology

1. Text Cleaning
- Text ko lowercase kiya
- Special characters aur numbers remove kiye

2. Feature Extraction
- TF-IDF Vectorizer ka use kiya
- Text ko numerical form me convert kiya

3. Model Training
- Logistic Regression model use kiya
- Dataset ko train-test split kiya (80%-20%)

4. Model Evaluation
- Accuracy score calculate kiya




📊 Results
- Model Accuracy: ~73%
- Model multiple languages ko achhi accuracy ke saath predict karta hai




🧪 Sample Prediction
- Input:
Bonjour, comment allez-vous?

- Output:
✅ French




🚀 Conclusion
- NLP techniques se hum successfully language detection kar sakte hain
- TF-IDF + Logistic Regression ek simple aur effective approach hai
- Ye project NLP basics, text preprocessing aur ML workflow ko clearly demonstrate karta hai


🧠 Skills Used
- Python
- NLP
- TF-IDF
- Logistic Regression
- Scikit-learn
