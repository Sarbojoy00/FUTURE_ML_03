# 📄 Resume Screening & Candidate Ranking System using Machine Learning

## 📌 Project Overview

This project was developed as part of the **Future Interns Machine Learning Internship – Task 3 (2026)**.

The system automates the resume screening process by analyzing resume text, comparing it with a job description, calculating similarity scores, ranking candidates, and identifying missing skills.

It demonstrates how Natural Language Processing (NLP) and Machine Learning can support recruiters and HR teams in making faster and more informed hiring decisions.

---

## 🎯 Objectives

- Preprocess resume text using NLP techniques.
- Parse and clean job descriptions.
- Extract relevant skills from resumes.
- Compare resumes with job descriptions.
- Calculate resume-job similarity scores.
- Rank candidates based on role fit.
- Identify missing skills for each candidate.

---

## 🚀 Features

- ✅ Resume text preprocessing
- ✅ Job description preprocessing
- ✅ Skill extraction using keyword matching
- ✅ TF-IDF Vectorization
- ✅ Cosine Similarity scoring
- ✅ Resume ranking
- ✅ Skill gap identification
- ✅ Candidate comparison
- ✅ Professional visualizations
- ✅ Export results as CSV files

---

## 📂 Dataset

**Dataset Used:**

Resume Dataset (Kaggle)

The dataset contains:

- Resume ID
- Resume Text
- Resume HTML
- Resume Category

Dataset Link:

https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📚 Machine Learning Workflow

### 1. Data Loading

- Load resume dataset

### 2. Text Preprocessing

- Convert text to lowercase
- Remove URLs
- Remove punctuation
- Remove numbers
- Remove stopwords

### 3. Job Description Processing

- Clean the job description
- Convert into machine-readable format

### 4. Feature Extraction

- TF-IDF Vectorization

### 5. Similarity Calculation

- Cosine Similarity between resumes and job description

### 6. Candidate Ranking

- Rank resumes based on similarity score

### 7. Skill Gap Analysis

- Extract skills from resumes
- Compare with required skills
- Identify missing skills

---

## 📊 Output

The project generates:

- Candidate Match Score
- Resume Ranking
- Skills Found
- Missing Skills
- Ranking Results CSV
- Skill Gap Report CSV
- Candidate Ranking Graph
- Similarity Score Distribution Graph

---

## 📈 Sample Output

| Rank | Resume Category | Match Score |
|------|-----------------|------------:|
| 1 | Consultant | 38.58% |
| 2 | Engineering | 34.76% |
| 3 | Automobile | 27.33% |
| 4 | Agriculture | 24.22% |
| 5 | Banking | 20.65% |

---

## 💡 How the System Scores Resumes

1. The resume text is cleaned and preprocessed.
2. The job description undergoes the same preprocessing.
3. TF-IDF converts both texts into numerical feature vectors.
4. Cosine Similarity measures how closely each resume matches the job description.
5. A higher similarity score indicates a better match for the job role.
6. Candidates are ranked from highest to lowest score.

---

## 🔍 How Skill Gaps Are Identified

A predefined list of required skills is compared with the skills detected in each resume.

The system identifies:

- Skills present in the resume
- Skills missing from the resume

This helps recruiters quickly identify areas where candidates may need additional expertise.

---

## 📁 Project Structure

```
Resume-Screening-System/
│── resume_screening.ipynb
│── Resume.csv (optional)
│── ranking_results.csv
│── skill_gap_report.csv
│── candidate_ranking.png
│── similarity_scores.png
│── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Resume-Screening-System.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```
resume_screening.ipynb
```

### 4. Run all notebook cells.

### 5. Enter a job description when prompted.

The system will automatically:

- Calculate similarity scores
- Rank candidates
- Identify missing skills
- Generate graphs
- Save CSV reports

---

## 📊 Business Impact

This project can help organizations:

- Reduce manual resume screening time.
- Improve hiring efficiency.
- Rank applicants objectively.
- Identify candidates with the closest skill match.
- Highlight missing skills for better recruitment decisions.
- Support recruiters in shortlisting candidates more effectively.

---

## 📷 Generated Outputs

- Candidate Ranking Chart
- Similarity Score Distribution
- Ranking Results CSV
- Skill Gap Report CSV

---

## 🔮 Future Improvements

- PDF Resume Parsing
- Named Entity Recognition (NER) using spaCy
- ATS-style resume scoring
- Automatic skill extraction using transformer models
- Semantic matching with BERT or Sentence Transformers
- Interactive web application using Streamlit or Flask

---

## 👨‍💻 Author

**Sarbojoy Ghosal**

Machine Learning Intern – Future Interns

---

## 📜 License

This project is developed for educational and internship purposes only.