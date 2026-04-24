# FUTURE_ML_03 — Resume / Candidate Screening System

**Future Interns | Machine Learning Track | Task 3**

---

## 📌 Project Overview

An ML-powered resume screening system that automatically ranks 55 candidates based on a job description using TF-IDF similarity, skill matching, and experience scoring.

---

## 🎯 What It Does

- **Screens** 55+ resumes against a job description
- **Extracts** matched and missing skills for each candidate
- **Ranks** candidates by final weighted score
- **Shortlists** qualified candidates automatically
- **Visualizes** results with dashboard + skill heatmap

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.10+ | Programming language |
| NLTK | Text preprocessing |
| Scikit-learn | TF-IDF, Cosine Similarity |
| Pandas | Data management |
| Matplotlib / Seaborn | Dashboard + Heatmap |
| Pickle | Save vectorizer |

---

## 📊 Scoring Formula

```
Final Score = (Similarity × 50%) + (Skill Match × 35%) + (Experience × 15%)
```

---

## 📁 Project Structure

```
FUTURE_ML_03/
├── data/
│   ├── resumes.csv               ← 55 candidate resumes
│   ├── ranked_candidates.csv     ← All candidates ranked
│   ├── shortlisted.csv           ← Shortlisted candidates
│   ├── screening_dashboard.png   ← Analysis dashboard
│   └── skill_heatmap.png         ← Skills heatmap top 10
├── model/
│   └── tfidf_vectorizer.pkl      ← Saved TF-IDF vectorizer
├── notebook/
│   └── resume_screening.py       ← Main project code
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/FUTURE_ML_03.git
cd FUTURE_ML_03
mkdir data model
pip install -r requirements.txt
cd notebook
python resume_screening.py
```

---

## 👤 Author

**Bharati Kumari Gupta** | CIN: FIT/APR26/ML7054
Future Interns — ML Track
