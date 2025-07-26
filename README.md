# Case Study 2 — Machine-Learning Analysis

A concise, end-to-end case study that walks through data preparation, feature engineering and model training for a multi-class classification problem.  
All results and discussion are collected in **Case study2.pdf**, while the full, executable workflow lives in **case_Study_2_final.ipynb**.

---

## Repository layout

.
├── docs/
│ └── Case study2.pdf # Polished report (43 pp.)
├── notebooks/
│ └── case_Study_2_final.ipynb # Jupyter notebook with code & visuals
└── README.md # You are here

## Quick start

1. **Clone the repo**

   ```bash
   git clone https://github.com/<your-username>/case-study-02-ml-analysis.git
   cd case-study-02-ml-analysis
   ```

 2.Create a virtual environment & install requirements
 ``` bash
    python -m venv .venv
    source .venv/bin/activate        # Windows: .venv\Scripts\activate
    pip install -r requirements.txt  # create & maintain this file as needed
```
3.Run the notebook
jupyter notebook notebooks/case_Study_2_final.ipynb
4.Read the report
The PDF version of the write-up is in docs/Case study2.pdf.

### Features
1-Reproducible notebook — all code in a single place, with clear section headers.
2-Comprehensive report — methodology, results, charts and key takeaways bundled as a PDF.
3-Clean project structure — separation of code, docs and data for maintainability.

## How it works (high-level)
Data ingestion — load raw CSV/Excel data into pandas.
Exploration & cleaning — handle missing values, outliers and categorical encoding.
Feature engineering — scaling, PCA dimensionality reduction and manual domain features.
Model training — compare SVM, Random Forest and MLP with GridSearchCV.
Evaluation — precision/recall, confusion matrices and model explanation.
Reporting — compile findings into the PDF for stakeholders.
