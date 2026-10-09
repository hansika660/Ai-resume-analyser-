# AI Resume Analyzer

An AI-powered tool that compares a resume against a job description and shows how well they match.

## Features
- Upload or paste a resume (PDF/text)
- Paste a job description
- Match score (0-100%)
- Missing keywords and skills
- Suggestions to improve the resume

## Tech Stack
- Python
- Streamlit (UI)
- spaCy / scikit-learn (text processing and similarity)
- PyPDF2 (PDF reading)

## How It Works
1. Extract text from the resume and job description
2. Clean and tokenize the text
3. Compare them using TF-IDF and cosine similarity
4. Show the score and missing keywords

## Run Locally
git clone https://github.com/Hansika uppala/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
pip install -r requirements.txt
streamlit run app.py

## Author
Hansika uppala 
