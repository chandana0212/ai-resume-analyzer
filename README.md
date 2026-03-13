🤖 AI Resume Analyzer

An AI-powered Resume Analyzer that evaluates resumes by comparing them with job descriptions and provides a similarity score and insights to help candidates improve their chances of getting shortlisted.

This project uses Natural Language Processing (NLP) techniques to analyze resume content and measure how well it matches a specific job role.

🚀 Features

📄 Upload resume in PDF format

🧠 Extracts text automatically from resumes

📊 Compares resume with job description

📈 Calculates similarity score

💡 Provides feedback for improvement

⚡ Simple and user-friendly interface

🛠️ Tech Stack

Frontend

HTML

CSS

JavaScript

Backend

Python

Flask

AI / NLP

Scikit-learn

TF-IDF Vectorizer

Cosine Similarity

Other Tools

PyPDF2

Git & GitHub

🧠 How It Works

The user uploads their resume (PDF).

The system extracts text from the resume.

The user enters a job description.

The system converts both texts into TF-IDF vectors.

Cosine similarity is used to calculate the match score.

The result shows how well the resume matches the job role.

📊 Example Workflow
Resume Upload → Text Extraction → NLP Processing → Similarity Calculation → Score Output
📂 Project Structure
ai-resume-analyzer
│
├── app.py
├── templates
│   └── index.html
├── uploads
├── static
│   ├── css
│   └── js
├── README.md
└── requirements.txt
▶️ Installation & Setup

Clone the repository:

git clone https://github.com/yourusername/ai-resume-analyzer.git
