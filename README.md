# Fake Account Detection on Instagram using Machine Learning

## 📌 Abstract
This project addresses the growing challenge of fake social media accounts, especially on Instagram. Fake accounts are often used for spamming, misinformation, and fraudulent activities. We examine three ML models: **Random Forest**, **Logistic Regression**, and **Decision Tree** to detect these fake accounts with a focus on accuracy and real-time detection.

---

## 📁 Table of Contents
1. [Project Description](#project-description)
2. [Problem Statement](#problem-statement)
3. [Project Objectives](#project-objectives)
4. [Related Work](#related-work)
5. [System Design](#system-design)
6. [Technical Stack](#technical-stack)
7. [Algorithms Used](#algorithms-used)
8. [Testing](#testing)
9. [Results](#results)
10. [Conclusion & Scope](#conclusion--scope)

---

## 💡 Project Description
The aim is to identify fake accounts using behavioral and account metadata like followers, post count, account privacy, etc. Machine Learning algorithms are used to predict whether an account is real or fake.

---

## ❗ Problem Statement
> Fake social media accounts and their detection.

The goal is to develop a system that detects fake profiles on social media platforms like Instagram using machine learning techniques.

---

## 🎯 Project Objectives
- Develop advanced ML models to detect fake accounts.
- Evaluate models using metrics like precision, recall, F1 score, AUC-ROC.
- Enable real-time detection with NLP & behavioral analysis.
- Provide recommendations for integration into real platforms.

---

## 🔍 Related Work
The project surveys existing approaches including:
- Rule-based methods
- Machine Learning (Supervised/Unsupervised)
- Deep Learning (CNN, RNN, GNN)
- NLP (Sentiment, Spam detection)
- Behavioral Analysis

---

## 🛠️ System Design

### 📌 Flowchart of Detection Process
1. Data Collection
2. Preprocessing
3. Feature Engineering
4. Model Training
5. Evaluation & Prediction

### 📊 Features Used
- **Metadata**: Follower count, account age, bio
- **Behavioral**: Posting patterns, response time
- **Content**: Sentiment analysis, repetitive spam phrases

---

## 💻 Technical Stack

- **Backend**: Python, Flask
- **IDE**: PyCharm
- **Libraries**: Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib

---

## 🤖 Algorithms Used

### Logistic Regression
- Simple and interpretable
- Best for linear relationships

### Decision Tree
- Tree-based visual model
- Prone to overfitting

### Random Forest
- Ensemble method with high accuracy
- Most effective model used in this project

---

## 🧪 Testing

### Unit Testing Steps:
- Define input/output of the model
- Create test cases for fake/genuine accounts
- Use sample data for validation
- Evaluate results based on test outcomes

---

## 📈 Results
| Algorithm         | Accuracy |
|------------------|----------|
| Logistic Regression | 90.03%   |
| Decision Tree       | 93.59%   |
| Random Forest       | **95.01%**   ✅ |

---

## 🧾 Conclusion & Scope

- Random Forest performed best and is selected for deployment.
- Future improvements include:
  - Real-time detection
  - Larger datasets
  - Deep learning integration
  - Ethical and privacy-compliant data handling

---

## 🔮 Scope for India
- Centralized agency for fake account tracking
- API-based real-time removal coordination
- National-level fake profile prevention systems

