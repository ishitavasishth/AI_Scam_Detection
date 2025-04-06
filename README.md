# 🚨 ScamSentry – AI-Powered Scam Detection

ScamSentry is an AI-powered message classifier that detects suspicious or scam-like messages using NLP, machine learning, and transformer-based models. 

---

## 💡 Problem Statement
Scam messages cost individuals and businesses billions annually. Many scams are hard to detect using rule-based systems because they sound legitimate.

**Can AI detect tone, urgency, and manipulation in messages — and protect users from scams before they happen?**

---

## 🎯 What This Project Does
- ✅ Classifies short messages as **SPAM (scam)** or **HAM (safe)**
- ✅ Uses both **traditional ML** (TF-IDF + Logistic Regression) and **advanced transformer models (BERT)**
- ✅ Provides a **real-time interactive UI** in Colab for testing custom messages
- ✅ Stores inputs + predictions for **feedback loop and future improvements**
- ✅ Built **entirely in Google Colab** — fully portable and reproducible

---

## 📊 Tech Stack
| Layer         | Tools                                        |
|--------------|----------------------------------------------|
| Data         | Kaggle – SMS Spam Collection Dataset         |
| NLP          | TF-IDF, stopwords removal, lemmatization     |
| ML Models    | Logistic Regression, XGBoost                 |
| Transformers | DistilBERT via Hugging Face Transformers     |
| UI           | ipywidgets (interactive form in Colab)       |
| Logs         | Python list, pandas DataFrame                |
| Deployment   | Google Colab + GitHub                        |

---

## 🧪 Sample Inputs & Predictions
| Message                                                  | TF-IDF Prediction | BERT Prediction               |
|----------------------------------------------------------|-------------------|-------------------------------|
| "Congratulations! You won a free iPhone. Claim now!"     | SPAM              | NEGATIVE (SPAM-like)         |
| "Hey, just checking in to see how your day’s going."     | HAM               | POSITIVE                     |
| "Urgent! Your account is at risk. Verify info."          | ❌ HAM (TF-IDF)    | ✅ NEGATIVE (Correctly flagged) |

---

---

## 💼 Business Impact
### For Companies / SaaS Platforms:
- 📦 Integrate into messaging pipelines to flag scams in real time
- 🔒 Reduce fraud, phishing, and customer service abuse
- 🛡️ Add a layer of brand trust and proactive user protection

### For Users:
- 👵 Protect vulnerable groups like seniors and students
- 🔍 Recognize subtle manipulation and urgency-based deception
- 🌐 Improve overall **digital safety awareness**

---
---

## 📁 Project Structure
```
ScamSentry/
├── ScamSentry_Colab.ipynb
├── README.md
├── screenshots/
│   ├── scam_ui_demo.png
│   └── confusion_matrix.png
├── data/
│   └── spam.csv
├── logs/
│   └── predictions.csv
```

---

