#  ML-Resume-Assessment-System

An **ML-Resume-Assessment-System** built using Python, Machine Learning, and Streamlit.

The system analyzes resumes or user-entered skills to:

* Predict the most suitable career role
* Recommend top matching jobs
* Evaluate resume quality
* Provide ATS improvement suggestions
* Analyze real-time job market trends

# Homepage
![Home Page](https://github.com/Malateshgouda813/ML-Resume-Assessment-System/blob/36cec5ddbb0405db75fbf28fa5dd9ec8a0de366a/out_put.png)


# Features

## 1️⃣ Career Role Prediction

Predicts the most suitable job role based on skills or resume text using:

* TF-IDF Vectorization
* Logistic Regression

Displays model confidence score.

---

## 2️⃣ Job Recommendation System

Recommends **Top 5 relevant job roles** using:

* TF-IDF
* Cosine Similarity

Matches resume content with job dataset.

---

## 3️⃣ Resume Analyzer

Evaluates resume quality using ML model ridge and tf-idf and generates a **score out of 100** based on:

* Skills
* Projects
* Experience
* Education
* Tools
* Certifications
* Resume structure
---

### 4️⃣  AI-Powered ATS Improvement Suggestions 
Uses **Groq LLM API (Llama 3)** to analyze resumes and provide personalized suggestions:
* Specific skill gap identification
* Missing section detection
* ATS keyword recommendations
* Project improvement tips
* Resume formatting advice

> Powered by Llama 3 via Groq API — not rule-based, actual AI analysis of your resume content.

---

## 5️⃣  Job Market Trends 

Analyzes real-world demand for job roles using **Google Trends (Pytrends)**:

* Enter any job role (e.g., AI Engineer, Data Scientist)
* Displays **trend graph over last 12 months**
* Shows market direction:

  * 📈 Increasing
  * 📉 Decreasing
  * ➖ Stable

👉 Includes:

* Smart trend direction detection
* Fallback mechanism (prevents API failure crashes)
* Real-time visualization using Streamlit

---

## Machine Learning Techniques

| Technique | Purpose |
|---|---|
| TF-IDF Vectorization | Convert text to numerical features |
| Logistic Regression | Career role prediction |
| Ridge Regression | Resume score prediction |
| Cosine Similarity | Job recommendation |
| Groq LLM (Llama 3) | AI-powered ATS suggestions |
| Pytrends | Job market trend analysis |

# 📁 Project Structure

```
Job-Recommendation-System
│
├── app.py
├── prediction.py
├── helper.py
├── resume_score.py
├── trend.py
├── main.py
├── requirements.txt
├── README.md
└── Final_Specialized_Dataset.csv
└── Final_Fixed_Dataset.csv
```

---

# 📊 Dataset

The dataset contains:

* User_Skills
* Job_Requirements
* Job_Role

These columns are combined to create training text for the ML models.

---

# 📂 Application Pages

* 📄 Resume Analyzer
* 🧠 Career Prediction
* 💼 Job Recommendation
* 📊 Job Market Trends

---

## 🛠 Tech Stack
* Python
* Scikit-learn
* Streamlit
* Pandas
* NumPy
* PyPDF2
* Groq API (Llama 3)
* TF-IDF + Cosine Similarity
* Pytrends (Google Trends API)


---



