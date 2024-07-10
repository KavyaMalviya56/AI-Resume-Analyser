# AI-Resume-Analyser
# Resume Analyzer Using Gemini

## Overview

The Resume Analyzer is a web application that leverages the power of Google's Gemini AI to evaluate resumes against specific job descriptions. It provides detailed feedback, including strengths, weaknesses, missing keywords, skill improvement suggestions, and a percentage match to help job seekers optimize their resumes for better job prospects.

## Features

- **Resume Analysis:** Evaluates the resume against the provided job description.
- **Skill Improvement Suggestions:** Offers advice on how to enhance the candidate's skills.
- **Missing Keywords Identification:** Lists keywords missing from the resume that are critical for the job description.
- **Match Percentage Calculation:** Provides a percentage match indicating how well the resume aligns with the job description.
- **Interactive Query Handling:** Allows users to ask specific questions about their resume and get tailored responses.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-repo/resume-analyzer.git
   cd resume-analyzer

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   
4. **Set Up Environment Variables:**
   GOOGLE_API_KEY=your-google-api-key

## Usage

1. **Run the Application:**
  ```sh
  streamlit run app.py
  ```

2. **Upload Your Resume:**
  Upload a PDF version of your resume using the file uploader.

3. Enter the Job Description:
  Paste the job description in the provided text area.

4. Choose an Action:

- **Tell Me About the Resume:** Provides a professional evaluation of your resume.
- **How Can I Improve My Skills:** Offers suggestions on enhancing your skills.
- **What Are the Keywords That Are Missing:** Lists missing keywords critical for the job.
- **Percentage Match:** Gives a percentage match of how well your resume fits the job description.
- **Answer My Query:** Allows you to ask specific questions about your resume.
