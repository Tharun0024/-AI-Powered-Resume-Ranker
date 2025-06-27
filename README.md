# 🧠 AI-Powered Resume Ranker

This project leverages Natural Language Processing (NLP) techniques to rank resumes based on their relevance to a specific job description.

## 🎯 Objective

To automate the resume shortlisting process by ranking candidates based on how well their resumes match the job description using TF-IDF vectorization and cosine similarity.

---

## 🛠️ Tools & Technologies

- **Python**  
- **Flask** (Web Framework)  
- **SpaCy** (NLP Preprocessing)  
- **Scikit-learn** (TF-IDF, Cosine Similarity)  
- **PDFMiner / PyMuPDF** (PDF Text Extraction)  
- **HTML/CSS** (Frontend UI)  

---

## 📘 How It Works

### 🗂️ Step-by-Step Workflow

1. **Extract** text from uploaded PDF resumes.
2. **Preprocess** the extracted text (tokenization, stopword removal) using **SpaCy**.
3. **Vectorize** the processed resumes and the job description using **TF-IDF**.
4. **Score** resumes based on **cosine similarity** with the job description.
5. **Rank** resumes from most to least relevant.
6. **Display** results in a simple **Flask web UI**.
7. **Export** rankings into a downloadable HR report.

---

## 🚀 Setup Instructions

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/resume-ranker.git
    cd resume-ranker
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask server:
    ```bash
    python app.py
    ```

4. Open the app in your browser:
    ```
    http://localhost:5000
    ```

---

## 📦 Deliverables

- Flask web app with resume upload feature
- NLP pipeline for preprocessing and scoring
- Resume ranking engine using cosine similarity
- Downloadable HR report
- Sample test resumes and job descriptions

---

## 📁 Folder Structure

