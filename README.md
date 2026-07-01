# TalentScout: AI-Powered Recruitment Pipeline

TalentScout is an intelligent automation system engineered to assist HR teams in conducting objective, data-driven, and scalable candidate screening using advanced AI technology.

## Problem Statement & Solution
- **Challenge:** Manual CV screening is time-consuming, labor-intensive, and prone to human bias.
- **Solution:** This system automates the extraction of candidate data and performs real-time benchmarking against job description requirements to provide instant, quantified matching scores.

## Tech Stack
- **AI Core:** Gemini Opal (LLM-based inference).
- **Architecture:** Workflow Automation (Input Integration → Logic Scoring Engine → HTML Dashboard Rendering).
- **Scoring Algorithm:** Weighted Scoring Model (40% Hard Skills, 30% Experience, 20% Education, 10% Achievement).

## Workflow Overview
1. **Input:** Candidates upload their CVs, and users input the corresponding Job Description text.
2. **Logic Engine:** The system executes a gap analysis, comparing professional qualifications against specific role requirements to calculate a final suitability score (0-100).
3. **Dashboard:** The system generates an informative Executive Hiring Dashboard, featuring progress bars for scoring metrics, comparative tables, and strategic interview recommendations.

## Scoring Methodology
The system employs a high-precision weighted algorithm to ensure reliable evaluations:
- **Technical Skills Match (40%):** Validates candidate proficiency against mandatory hard skills outlined in the Job Description.
- **Experience Relevance (30%):** Assesses the duration and complexity of the professional background.
- **Education/Certification (20%):** Verifies the relevance of academic qualifications and professional certifications.
- **Impact/Achievement (10%):** Analyzes data-driven achievements and measurable project outcomes within the CV.
- **Guardrail:** An automatic -30 point penalty is applied if mandatory hard skills are absent, ensuring high-quality filtering.

## Dashboard Preview
<img width="1912" height="828" alt="image" src="https://github.com/user-attachments/assets/c631a096-8d83-46be-bcad-1eaa37652e11" />
<img width="1885" height="789" alt="image" src="https://github.com/user-attachments/assets/c74dd9e0-4d27-4cd4-9d24-fe803b3435b4" />
<img width="1887" height="790" alt="image" src="https://github.com/user-attachments/assets/ad343c5a-7e6f-4a67-9dcc-8c5db2acb9f0" />

## Project Access
- **Live Workflow:** https://opal.google/app/1T5BGS6iDRsbVlrHd9nd6nytPtVT0dgSR

## Technical Pipeline
The pipeline architecture follows this flow:
`User Input (CV/JD)` → `Gemini Opal Processor` → `Logic Scoring Engine` → `HTML Dashboard Output`

---
*This project was developed as a final requirement for the AI for Work & Career Readiness course.*
