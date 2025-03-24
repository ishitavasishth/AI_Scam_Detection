# ScamSentry – AI-Powered Scam Detection

 ScamSentry: AI-Powered Scam Message Classifier
Helping users detect suspicious or scam-like messages using NLP, machine learning, and transformer-based AI models — built 100% in Google Colab.

💡 Problem Statement
Scam messages cost individuals and businesses billions each year. Many look deceptively legitimate and are hard to detect with rule-based systems.

🧠 Can AI be trained to understand subtle manipulation, urgency, and threat in short messages to flag scams before users fall for them?

🎯 What This Project Does
✅ Classifies short messages as SPAM (scam) or HAM (safe)
✅ Uses both traditional ML (TF-IDF + Logistic Regression) and advanced BERT transformers
✅ Provides a real-time visual interface where users can test messages
✅ Stores inputs + predictions for feedback loops
✅ Entirely built in Google Colab – no APIs, no keys needed

📊 Tech Stack
Layer	Tools
Data	Kaggle – SMS Spam Collection
NLP	TF-IDF, stopwords removal, lemmatization
ML Models	Logistic Regression, XGBoost
Transformers	DistilBERT from Hugging Face
UI	ipywidgets in Google Colab
Logs	Python lists, pandas DataFrame
Deployment	GitHub + Colab Link
🧪 Sample Inputs
Message	Prediction (TF-IDF)	Prediction (BERT)
Congratulations! You won a free iPhone. Claim now!	SPAM	NEGATIVE (SPAM-like)
Hey, just checking in to see how your day’s going.	HAM	POSITIVE
Urgent! Your account is at risk. Verify info.	❌ HAM (TF-IDF fails)	✅ NEGATIVE (Correctly flagged)
🔍 What Makes It Stand Out (2025-Ready)
Context-aware spam detection using transformer models

Combines sentiment cues (e.g., urgency, fear) with pattern-based detection

Lightweight and fully reproducible in Colab

Logs predictions for feedback and retraining

💼 Business Impact
For Companies / SaaS Platforms:

Integrate into customer messaging platforms to pre-flag suspicious inbound or outbound messages

Reduce fraud, phishing, and account takeovers

Add a layer of brand trust and user protection

For Users:

Protects vulnerable populations from scams (students, seniors)

Understands context beyond keyword-matching

Promotes digital safety + awareness


🧠 Inspiration
Built by a data-driven marketing analyst & AI explorer who believes in using machine learning for real-world safety & impactful storytelling.

