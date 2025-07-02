# 🛒 NLP Sentiment Analysis & Topic Modeling on BigBasket App Reviews

A full-stack NLP project built to analyze customer reviews of the BigBasket Android app. This project applies a range of machine learning and lexicon-based techniques to extract sentiment, identify dominant emotions, and uncover hidden topics from unstructured user feedback.

> 📍 Built as an end-term academic project for NLP coursework.

---

## 🔍 Problem Statement

BigBasket, one of India’s leading grocery delivery platforms, receives thousands of reviews on its mobile app. These reviews contain valuable feedback about product quality, delivery speed, app experience, and customer service. However, being unstructured text, this information remains largely underutilized.

This project answers:
- What are the most common sentiments expressed in reviews?
- What emotions drive positive or negative feedback?
- What topics do customers care most about?
- How accurately can we classify user sentiment using machine learning?

---

## 🧪 Project Highlights

| Task | Description |
|------|-------------|
| **Text Preprocessing** | Cleaning, tokenization, stopword removal, stemming, lemmatization |
| **Sentiment Classification** | Supervised models: Naive Bayes, Logistic Regression, Random Forest, SVM |
| **Lexicon-Based Sentiment** | NRClex, SentiWordNet, VADER |
| **Vectorization** | CountVectorizer & TF-IDF |
| **Topic Modeling** | Latent Dirichlet Allocation (LDA) to uncover 5 dominant topics |
| **Visualization** | Confusion matrices, sentiment distributions, emotion bars, WordClouds, n-grams |

---

## 🛠 Tools & Libraries

- **Languages**: Python
- **NLP Libraries**: `NLTK`, `TextBlob`, `VADER`, `nrclex`, `SentiWordNet`
- **ML Models**: `MultinomialNB`, `LogisticRegression`, `RandomForestClassifier`, `SVC`
- **Vectorizers**: `CountVectorizer`, `TfidfVectorizer`
- **Visualization**: `Matplotlib`, `Seaborn`, `WordCloud`
- **Model Evaluation**: `Confusion Matrix`, `Classification Report`

---

## 📂 Project Structure

bigbasket-nlp-analysis/
│
├── bigbasket_nlp_sentiment_analysis.ipynb # Main notebook
├── README.md # This file
├── requirements.txt # Python dependencies (optional)
├── visuals/ # WordClouds, confusion matrices, etc. (optional)
└── Big Basket App REVIEWs.xlsx # Raw review data

yaml
Copy
Edit

---

## 📊 Model Results

| Model               | Accuracy |
|--------------------|----------|
| Naive Bayes        | 87%      |
| Logistic Regression| 92%      |
| Random Forest      | 93%      |
| Support Vector Machine | 93%  |

✅ **SVM and Random Forest** were the top performers in multi-class sentiment classification.

---

## 🧠 Lexicon-Based Sentiment Methods

| Lexicon     | Output Type         | Highlights |
|-------------|---------------------|------------|
| **NRClex**  | Dominant emotion per review | Captured 10 core emotions like trust, anger, sadness |
| **SentiWordNet** | Scored words using synsets | Derived an overall polarity score |
| **VADER**   | Compound sentiment score | Real-time, rule-based classification into pos/neg/neutral |

---

## 🔍 Topic Modeling (LDA)

Extracted **5 latent topics** from the reviews:
1. **Delivery & timing**
2. **Product quality & packaging**
3. **Offers & pricing**
4. **App performance (bugs/UX)**
5. **Customer support**

Each topic was visualized using WordClouds for better interpretability.

---

## 📈 Visualizations

- ✅ Confusion Matrices for all models  
- ✅ Sentiment distribution (bar chart)  
- ✅ NRClex emotion count chart  
- ✅ Top 20 1-gram and 2-gram terms by sentiment  
- ✅ Topic WordClouds (5 topics from LDA)

> All visuals available inside the notebook or `/visuals` folder.

---


