# Resume_Matcher
Resume Matcher is a Flask web application that helps users match resumes to a job description based on text similarity.
It supports PDF, DOCX, and TXT files, using TF-IDF vectorization and cosine similarity to rank resumes by relevance to a given job description.

# Features
. Multi-File Support: Handles .pdf, .docx, and .txt resume files.
. Text Similarity Matching: Uses TF-IDF vectorization and cosine similarity to rank resumes based on their match with the job description.
. Top Matching Resumes: Returns the top 5 resumes with their similarity scores for easy comparison.
. Simple Web Interface: A user-friendly interface for uploading resumes and entering a job description.

# Prerequisites
 . flask 
 . docx2txt
 . PyPDF2 
 . scikit-learn

 # Code Overview
 . app.py: The main Flask app, handles file uploads, text extraction, and matching logic.
 . Text Extraction: Functions to read PDF, DOCX, and TXT files.
 . Similarity Matching: Uses TF-IDF vectorization and cosine similarity to find the most relevant resumes.
 . templates/matchresume.html: HTML template for the front-end interface.

# Improvements & Future Work
. Enhanced Semantic Matching: Implement models like Word2Vec or Sentence-BERT to better understand job descriptions and resume content.
. Improved File Handling: Add file sanitization and automatic deletion of temporary files for better security.
. Keyword Highlighting: Show matching keywords between the job description and resumes.

# Contributing
. Contributions are welcome! Please fork the repository and create a pull request.


