# AI-Powered Resume & Job-Match Analyzer

An end-to-end deep learning–powered tool to analyze resumes and match them to job roles.  
Upload your CV and instantly get a **job-fit score** with actionable insights.

---

## Features

- **Resume Classification (ML + DL):**
  - Classifies resumes into relevant job-fit roles.
  - Computes a **job-fit score** based on:
    - Skills
    - Experience
    - Education
    - Role alignment

- **LLM-Powered Insights (Hugging Face Transformers):**
  - Identifies **missing skills** compared to the target role.
  - Highlights **weak sections** in the CV.
  - Generates **personalized recommendations** for improvement.

- **Deployment:**
  - Web app interface
  - Upload a PDF/Docx resume
  - Get job-fit score + actionable recommendations in real time

---

## Tech Stack

- **Deep Learning:** [PyTorch](https://pytorch.org/)
- **NLP & LLMs:** [Hugging Face Transformers](https://huggingface.co/transformers)
- **Data Handling:** Pandas, Scikit-learn
- **Web Framework:** (Streamlit / FastAPI / Flask) ← choose depending on your deployment
- **Environment:** Conda (exported via `environment.yaml`)

---

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Sandeep20013/ai-job-matcher.git
   cd ai-job-matcher
