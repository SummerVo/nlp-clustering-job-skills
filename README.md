# Data Science Skills Analysis from Job Postings

## Overview
This project analyses **data science job postings** to explore **skill requirements and role differentiation** within the data science job market.  
Using **NLP-based clustering**, the analysis identifies meaningful job categories and highlights the core and specialized skills associated with each category.

The project demonstrates how **unsupervised NLP techniques and visual analytics** can be used to extract actionable insights from real-world labour market data.

---

## Objectives
- Identify **core skills** commonly required across data science roles
- Cluster job postings into **distinct job categories** using NLP embeddings
- Analyze **skill differences** between identified job clusters
- Support job seekers in understanding **skill priorities for different roles**

---

## Data
The analysis uses the **Data Science Job Postings & Skills (2024)** dataset from Kaggle, containing over **12,000 job postings** collected from LinkedIn.

The dataset includes:
- Job title and company information
- Job descriptions
- Pre-extracted lists of required skills

Preprocessing was applied to clean and standardize skill keywords and reduce noise.

---

## Methods
- Skill keyword preprocessing and lemmatization  
- SentenceTransformer embeddings  
- Unsupervised clustering with **HDBSCAN**  
- Exploratory analysis and cluster interpretation using word clouds  

---

## Key Insights
- **Python, SQL, and communication skills** are the most common requirements across data science roles
- A large proportion of roles share overlapping core skills, indicating a strong **common foundation** in the field
- Clustering reveals distinct job categories, including:
  - Data engineering and analytics infrastructure roles
  - Medical data science roles
  - Data governance and cybersecurity-related roles
- Advanced and specialized roles require **domain-specific skills** in addition to core data science competencies

---

## Tools
- Python (pandas, NumPy, matplotlib)
- NLP: SentenceTransformers, spaCy
- Clustering: HDBSCAN
- Jupyter Notebook for analysis and visualization

---

## Output
- 📄 **[Read the full paper](./Exploring_Skill_Requirement_in_Data_Science_Job_Postings_using_NLPBased_Clustering.pdf)**
- 📓 **[npl_clustering_job_skils.ipynb](./npl_clustering_job_skils.ipynb)** containing full analysis and experiments

---

## Author
**Summer Vo**
