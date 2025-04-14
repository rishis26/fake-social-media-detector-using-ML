# Fake Account Detection on Instagram using Machine Learning

## 📌 Abstract
This project addresses the growing challenge of fake social media accounts, especially on Instagram. Fake accounts are often used for spamming, misinformation, and fraudulent activities. We examine three ML models: **Random Forest**, **Logistic Regression**, and **Decision Tree** to detect these fake accounts with a focus on accuracy and real-time detection.

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

## 🚀 How to Run the Project (Flask)

### 🧰 Prerequisites
- Python 3.x
- Git (optional)
- Internet connection to install dependencies

---

### 📦 Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 📂 Step 2: Create a Virtual Environment

#### 🪟 For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

#### 🍎 For Mac/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 📥 Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

> Or install manually:

```bash
pip install flask pandas scikit-learn matplotlib seaborn numpy
```

---

### 🏃 Step 4: Run the Flask App

#### 🪟 Windows:
```bash
python app.py
```

#### 🍎 Mac/Linux:
```bash
python3 app.py
```

Open your browser and go to:  
`http://127.0.0.1:5000`

---

### 🌐 Step 5: Using the App
- 🔍 Predict whether an Instagram account is fake or real  
- 📊 Compare accuracy of models (Random Forest, Logistic Regression, Decision Tree)  
- 📈 View results and dataset insights  

---

### 📁 Project Structure
```
├── app.py
├── templates/
│   ├── home.html
│   ├── about.html
│   ├── view.html
│   ├── model_selection.html
│   ├── prediction.html
├── static/
│   └── css/
│   └── js/
├── models/
│   └── random_forest.pkl
├── dataset/
│   └── instagram_data.csv
├── requirements.txt
├── README.md
```


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
