# 🔍 Resume Job Matcher using NLP & Skill Matching


## 📌 Problem Statement

In the rapidly growing job market, job seekers often face challenges in identifying roles that align with their skills, especially when dealing with thousands of job listings spread across various platforms. Simultaneously, recruiters face inefficiencies in manually filtering resumes to find ideal candidates. This mismatch leads to missed opportunities and a time-consuming recruitment process.

There is a pressing need for an intelligent system that can analyze a candidate's resume and accurately recommend the most relevant job opportunities based on their skills.

---

## 🎯 Objective

- To extract skills from a candidate's resume using NLP.
- To analyze and match these skills against a dataset of job descriptions.
- To recommend top job opportunities based on similarity scores.
- To simplify the job hunting process and enhance resume relevance.

---

##  Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy**
- **Scikit-learn**
- **NLTK / SpaCy**
- **PyMuPDF** (for PDF parsing)
- **Cosine Similarity**

---

##  Dataset

https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024

## How It Works
- **Data Loading:** Import job descriptions and related metadata.

- **Resume Parsing:** Extract text from PDF resume using PyMuPDF.

- **Skill Extraction:**  Match resume against a list of top job-related skills.

- **Job Recommendation:** Use cosine similarity between resume skills and job description vectors to rank and recommend top jobs.

- **Output:** A DataFrame showing the top matching jobs based on extracted skills.

---

## Example Extracted Resume Skills

  ['python', 'sql', 'machine learning', 'power bi', 'excel', 'pandas']

---

## ✅ Results

- Extracted relevant skills from resume accurately.

- Recommended top 10 matching job roles from dataset.

- Improved candidate-job alignment using semantic similarity techniques.
