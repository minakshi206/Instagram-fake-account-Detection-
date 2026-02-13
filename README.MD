# 📊 Instagram Fake / Spammer Account Detection System

---

## 🚀 Project Overview

Social media platforms face increasing challenges due to fake accounts, spam bots, and fraudulent users.

This project builds a Machine Learning-based classification system to detect whether an Instagram account is:

- ✅ Genuine Account  
- ❌ Fake / Spammer Account  

The solution combines:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Random Forest Classification
- Risk Scoring System
- Interactive Tableau Dashboard

The objective is to provide a data-driven behavioral analysis framework for fake account detection.

---

## 📁 Dataset Information

Two datasets were used:

- `train.csv` → Model training dataset  
- `test.csv` → Model evaluation dataset  

### 📌 Key Features Included:

- Profile Picture Availability  
- Username Length  
- Full Name Word Count  
- Description Length  
- Number of Posts  
- Number of Followers  
- Number of Following  
- External URL Presence  
- Private Account Status  
- Target Variable → `fake` (0 = Genuine, 1 = Fake)

---

## 🛠 Technologies & Tools Used

### 👨‍💻 Programming & ML
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### 📊 Data Visualization
- Tableau Desktop

---

## 📊 Exploratory Data Analysis (EDA)

The project includes advanced visual exploration:

✔ Fake vs Genuine Distribution (Pie Chart)  
✔ Followers Distribution Analysis  
✔ Following Behavior Comparison  
✔ Posts Activity Comparison  
✔ Engagement Ratio Feature  
✔ Correlation Heatmap  
✔ Multi-feature Distribution Analysis  

EDA revealed strong behavioral differences between fake and genuine accounts.

---

## 🧠 Feature Engineering

### 🔥 Engagement Ratio

```
Engagement Ratio = Followers / (Following + 1)
```

This helps identify suspicious accounts that:

- Follow too many users
- Have low follower strength
- Show imbalanced engagement behavior

---

## 🤖 Machine Learning Model

### ✅ Model Used:
Random Forest Classifier

### 📌 Why Random Forest?

- Handles non-linear relationships
- Reduces overfitting
- Works well with structured tabular data
- Provides Feature Importance insights
- High robustness in classification tasks

---

## 📈 Model Evaluation Metrics

The model performance was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Analysis

The model demonstrated strong capability in distinguishing fake and genuine accounts.

---

## ⭐ Advanced Feature: Risk Scoring System

A probability-based Risk Score (0–100) was developed using:

```python
model.predict_proba()
```

Accounts were categorized into:

- 🟢 Low Risk (0–30)
- 🟡 Medium Risk (30–70)
- 🔴 High Risk (70–100)

This adds a real-world fraud monitoring perspective to the project.

---

## 📊 Tableau Dashboard

An interactive dashboard was built using Tableau Desktop to visualize:

- Account Distribution (Fake vs Genuine)
- Average Followers Comparison
- Average Posts Comparison
- Engagement Ratio Analysis

The dashboard provides clear visual differentiation between fake and genuine account behavior.

![Dashboard Preview](dashboard.png)

---

## 💼 Real-World Applications

- Social Media Fraud Detection  
- Influencer Authenticity Verification  
- Spam Bot Detection Systems  
- Cybersecurity Monitoring  
- Digital Marketing Risk Analysis  

---

## 🔥 Unique Value Additions

✔ Engagement Ratio Feature Engineering  
✔ Risk Categorization Framework  
✔ Separate Train/Test ML Pipeline  
✔ Behavioral Pattern Interpretation  
✔ Interactive Tableau Visualization Layer  

---

## 📂 Project Structure

```
Instagram-Fake-Detection/
│
├── train.csv
├── test.csv
├── Instagram_Fake_Detection.ipynb
├── Instagram_Fake_Detection_Dashboard.twbx
├── dashboard.png
└── README.md
```

---

## 🏁 Conclusion

This project successfully demonstrates how Machine Learning and Data Visualization can be combined to detect fake Instagram accounts based on behavioral analysis.

The Random Forest model effectively classifies accounts, while the Risk Scoring system enhances real-world applicability.

The addition of an interactive Tableau dashboard strengthens the business intelligence and reporting aspect of the solution.

This project is suitable for:

- Internship Portfolios  
- Data Science Projects  
- Fraud Detection Prototypes  
- Social Media Monitoring Systems  

---

## 👩‍💻 Author

**Minakshi**  
Data Analysis & Machine Learning Enthusiast



