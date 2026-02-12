# 📊 Instagram Fake / Spammer Account Detection
### Machine Learning | Data Analysis | Feature Engineering
### Internship Project – Unified Mentor

---

## 🚀 Project Overview

Social media platforms face increasing issues of fake accounts, spam bots, and fraudulent users.  
This project builds a Machine Learning model to classify Instagram accounts as:

- ✅ Genuine Accounts  
- ❌ Fake / Spammer Accounts  

The system uses advanced data analysis, feature engineering, and Random Forest classification to detect suspicious behavior patterns.

---

## 📁 Dataset Used

This project uses two datasets:

- `train.csv` → Used for training the machine learning model  
- `test.csv` → Used for evaluating model performance  

The dataset contains account-level features such as:

- Profile picture availability  
- Username length  
- Full name words  
- Description length  
- Number of posts  
- Number of followers  
- Number of following  
- External URL presence  
- Private account status  
- Target variable: `fake`

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

✔ Pie Chart – Fake vs Genuine Distribution  
✔ Correlation Heatmap  
✔ Followers Distribution Histogram  
✔ Following Distribution Histogram  
✔ Posts Comparison Boxplot  
✔ Engagement Ratio Analysis  
✔ Multi-feature Histogram Grid  

---

## 🤖 Machine Learning Model

Model Used:

> Random Forest Classifier

Why Random Forest?

- Handles non-linearity
- Reduces overfitting
- Works well on structured tabular data
- Provides feature importance insights

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score  
- Classification Report  
- Confusion Matrix  
- Feature Importance Analysis  

The model achieved strong performance in distinguishing fake and genuine accounts.

---

## ⭐ Advanced Feature: Risk Scoring System

A probability-based **Risk Score (0–100)** was created using:

```python
model.predict_proba()
Accounts are categorized into:

🟢 Low Risk (0–30)

🟡 Medium Risk (30–70)

🔴 High Risk (70–100)

This adds a real-world business intelligence layer to the project.

💼 Real-World Applications

Social Media Fraud Detection

Influencer Authenticity Verification

Spam Bot Detection Systems

Cybersecurity Monitoring

Digital Marketing Analysis

🔥 Unique Concepts Added

✔ Engagement Ratio Feature Engineering
✔ Risk Categorization System
✔ Separate Train/Test Pipeline
✔ Multiple Advanced Visualizations
✔ Business-Oriented Interpretation

📌 Project Structure
Instagram-Fake-Detection/
│
├── train.csv
├── test.csv
├── Instagram_Fake_Detection.ipynb
└── README.md

📊 Conclusion

This project successfully demonstrates the application of Machine Learning in detecting fake Instagram accounts.

The Random Forest model effectively classifies accounts based on behavioral patterns and profile characteristics.

The addition of a Risk Scoring System enhances the project's real-world usability, making it suitable for:

Internship portfolios

Production-level enhancement

Fraud detection system prototypes

👩‍💻 Author

Minakshi
Data Analysis & Machine Learning Enthusiast