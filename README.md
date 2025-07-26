# 📧 Email Spam Classifier

A machine learning project to detect spam emails using natural language processing (NLP) techniques. This project was built as part of my internship at **Afame Technologies**, and it demonstrates end-to-end development of a spam detection model with deployment on Heroku.

---

## 🚀 Project Highlights

- **Model**: Logistic Regression with TF-IDF vectorization  
- **Accuracy**: Achieved 92% precision on test data  
- **Tech Stack**: Python, scikit-learn, NLP, Flask, Heroku  
- **Deployment**: Fully deployed with user-friendly web interface

---

## 🛠️ Features

- Preprocessing: Stop-word removal, lemmatization, token normalization  
- Feature Extraction: TF-IDF vectorization  
- Model Training: Logistic Regression (can be extended to Naive Bayes/SVM)  
- Web UI: Input email text and classify as "Spam" or "Not Spam"  
- Deployment: Hosted on Heroku for real-time access

---

## 🧠 Technologies Used

| Category         | Tools/Libraries            |
|------------------|-----------------------------|
| Programming      | Python 3.8+                 |
| ML/NLP           | scikit-learn, NLTK          |
| Web Framework    | Flask                       |
| Deployment       | Heroku                      |
| Data Preprocessing | Pandas, NumPy             |

---

## 🗃️ Dataset

- Based on a public spam dataset with **5,000+ labeled messages**
- Labels: `spam` and `ham` (non-spam)
- Preprocessed using NLP techniques for feature quality improvement

---

## 🧪 How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/kshitiz078/Email-spam-classifier-Afame-.git
   cd Email-spam-classifier-Afame-
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
3. **Run the App**
   ```bash
   python app.py

🤝 Credits

Built during internship at Afame Technologies
Created by Kshitiz Mathur
