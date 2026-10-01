# AI-powered-mental-health-risk-prediction-and-analysis-system.

> An Explainable Machine Learning Framework for Context-Aware Depression Screening and Personalized Student Support among University Students in Bangladesh”
---

## 📌 Overview

Depression is one of the most underdiagnosed mental health conditions globally. This project builds an **explainable, context-aware ML framework** that:

- Screens University Students in Bangladesh for depression risk using **PHQ-9 validated questionnaire data**
- Incorporates **contextual factors** (financial stress, social events, lifestyle) beyond clinical scores
- Provides **transparent, human-interpretable predictions** using explainability techniques (SHAP, LIME)

---

## 🗂️ Project Structure

```
An-Explainable-ML-Framework-for-Context-Aware-Depression-Screening/
│
├── Notebooks/
│   └── 1_fatching_data.ipynb       # Data ingestion from Google Sheets → raw CSV
│
├── data/
│   └── raw/                        # Raw CSV files (git-ignored, not pushed)
│       └── depression_screening_raw.csv
│
├── .env                            # Environment variables (git-ignored)
├── .gitignore                      # Git ignore rules
├── requirements.txt                # Python dependencies
└── README.md
```


## 🔬 Methodology

```
Google Sheets Data
        ↓
  1. Data Fetching       →  Notebooks/1_fatching_data.ipynb
        ↓
  2. Preprocessing       →  (coming soon)
        ↓
  3. Feature Engineering →  (coming soon)
        ↓
  4. Model Training      →  (coming soon)
        ↓
  5. Explainability      →  SHAP + LIME (coming soon)
        ↓
  6. Evaluation          →  (coming soon)
```

---

## 🔒 Privacy & Ethics

- All data is collected with **explicit participant consent**
- Raw data is **excluded from version control** via `.gitignore`
- No personally identifiable information (PII) is stored beyond anonymous submission IDs

---

## 👤 Author

**GMK Emon**
📧 business.gmkemon@gmail.com

---

## 📄 License

This project is intended for academic and research purposes only.