# AI-Based Resume Screening and Application Tracking System

## Project Overview

This project is an AI-assisted Resume Screening and Application Tracking
System developed using n8n.

The system automates the initial resume processing by accepting a resume,
extracting information from the PDF, analyzing the resume using an AI
model, checking predefined screening criteria, storing the results in
Google Sheets, and sending automated email notifications.

## Technologies Used

- n8n
- OpenAI / LLM
- Google Sheets
- Gmail
- PDF Text Extraction
- Workflow Automation

## Workflow

Candidate Resume
        ↓
Form Submission
        ↓
PDF Text Extraction
        ↓
AI Resume Analysis
        ↓
Structured Output
        ↓
Screening Criteria
        ↓
Google Sheets
        ↓
Email Notification

## Main Features

- Resume submission through a form
- PDF resume text extraction
- AI-assisted resume analysis
- Candidate skill identification
- Job requirement matching
- Application tracking
- Google Sheets integration
- Automated email notification

## How It Works

1. The candidate submits a resume through the form.
2. n8n receives the submitted resume.
3. The PDF content is extracted.
4. The extracted resume information is sent to an AI model.
5. The AI analyzes the candidate information.
6. The structured result is passed to the screening condition.
7. The result is stored in Google Sheets.
8. Email notifications can be sent automatically.

## Future Improvements

- Batch processing of thousands of resumes
- Job-description-based matching
- Duplicate resume detection
- Database integration
- Recruiter dashboard
- Error handling and retry mechanism
- Human review stage

## Important Note

This is an AI-assisted screening system. The AI output is intended to
support the recruitment process, while final recruitment decisions
should be made by a human reviewer.
