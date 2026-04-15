# AI Resume Screening System

## Overview
This project is an AI-powered Resume Screening System that evaluates candidate resumes against a job description using NLP techniques and LangChain.

## Features
- Extracts skills from resumes
- Matches candidate skills with job description
- Calculates match score
- Provides explanation of candidate suitability
- Web interface using Flask
- PDF resume upload support

## Tech Stack
- Python
- LangChain
- Flask
- PyPDF2
- HTML, CSS

## Project Structure
chains/
prompts/
utils/
templates/
main.py
app.py
requirements.txt


## How to Run

### 1. Clone Repo
git clone <your-repo-link>
cd project-folder


### 2. Create Virtual Environment
- python -m venv venv
- venv\Scripts\activate


### 3. Install Dependencies
pip install -r requirements.txt


### 4. Run App
python app.py


## Example Output
- Name
- Skills
- Matched Skills
- Score (with progress bar)
- Explanation

## Future Improvements
- Better scoring logic
- UI enhancements
- Deployment on cloud (Render)

K Rajeshwari
