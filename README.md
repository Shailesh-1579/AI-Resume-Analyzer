Project Summary: AI Resume Analyzer

The AI Resume Analyzer is a Streamlit-based web application that uses Google Gemini AI to analyze resumes and provide professional insights.

Key Features:

1. Resume Upload – Users can upload resumes in PDF format.


2. Text Extraction –

Uses pdfplumber for text-based PDFs.

Falls back to OCR (pytesseract + pdf2image) for scanned PDFs.



3. AI-Powered Analysis –

Evaluates skills, strengths, and weaknesses.

Suggests skills to improve and relevant courses.

Optionally compares the resume against a job description.



4. Google Gemini AI Integration – Uses Gemini 1.5 Flash for analysis.


5. Streamlit UI – User-friendly interface with resume upload, job description input, and result display.



Technology Stack:

Frontend: Streamlit

Backend: Python

Libraries: pdf2image, pdfplumber, pytesseract, google.generativeai, dotenv

AI Model: Google Gemini API
