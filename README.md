# 🏦 BankScreen - AI-Assisted Résumé Screening App

This repository contains the documentation and details for **BankScreen**, an AI-assisted web application designed specifically for the banking sector. This project was built using the Lovable no-code platform as part of the "Artificial Intelligence Foundations (CIS 2603)" course.

---

## 🚀 Project Overview

The banking sector faces a unique challenge during recruitment due to strict regulatory requirements and the need for highly specialized roles (e.g., Compliance Officer, AML Analyst). Manually reviewing hundreds of résumés for specific certifications and clearances is time-consuming and error-prone. 

**BankScreen** addresses this by providing a centralized platform where HR managers can import candidate data, have it automatically scored against a transparent, rule-based AI algorithm, and view the results on an interactive dashboard.

### Key Objectives:
- **Efficiency:** Process and score over 120 CVs in seconds.
- **Automation:** Generate automatic scoring algorithms based on experience, education, and certifications.
- **AI-Assistance:** Embed a conversational AI to answer HR questions and evaluate candidates.
- **Decision Optimization:** Provide a ranked list of candidates on a unified dashboard.

---

## 🛠️ Technologies & Platform Used

- **Lovable:** A modern AI-assisted no-code platform used to generate fully functional web application code from natural language descriptions.
- **Supabase:** Integrated within Lovable for secure database management and real-time data storage.

---

## 🧠 AI Logic & Workflow Automation

BankScreen transforms raw candidate data into actionable hiring intelligence through a 5-step workflow: **Input → Logic → Scoring → Banding → Output**.

### Scoring Formulas (Examples):
*   **Education:** PhD (+14 pts), Master's (+10 pts), Bachelor's (+6 pts).
*   **Experience:** Years of Experience × 2 (Max 25 pts).
*   **Compliance:** AML/KYC Knowledge = "Yes" (+10 pts).

### Automation Features:
*   **Automatic Score Calculation:** Triggered instantly upon candidate data entry.
*   **Conditional Workflow Actions:** Shortlisting a candidate automatically updates their status and triggers notifications.
*   **Email Automation:** Pre-filled, editable approval or rejection emails are generated based on recruiter actions.
*   **AI HR Assistant:** A conversational chatbot that provides tailored interview questions and candidate analysis.

---

## 💻 User Interface & Screens

The UI is designed with a professional Navy Blue and White color palette to convey trust and reliability. The application consists of five main screens:

1.  **Dashboard:** A macro-level overview of the hiring pipeline with summary metrics and top candidates.
2.  **Applicants:** A complete list of candidates with Smart Filters (search, position, status, experience slider).
3.  **Candidate Detail:** Full profile view with a transparent Score Breakdown panel and Recruiter Action buttons.
4.  **AI Assistant:** A conversational interface for HR queries and deep-dive candidate analysis.
5.  **Scoring Criteria:** Displays the transparent rules used by the AI to calculate scores.

---

## 💡 My Role & Key Learnings

As a core team member, my primary responsibilities focused on the AI logic and system automation:
*   **AI Scoring Logic:** Configured the AI scoring rules and point values for all nine scoring criteria using Lovable.
*   **Automation:** Set up the automated notification system triggered when a candidate is shortlisted, and configured the pre-filled Approval/Rejection email templates.
*   **AI Assistant:** Configured the AI Assistant screen and its suggested HR questions.
*   **UI & Testing:** Designed the Scoring Criteria screen layout and conducted overall system testing to ensure accuracy and reliability.

This project demonstrated how AI-powered no-code tools can be leveraged to build functional, real-world business applications without requiring deep programming expertise.

---

## 🖼️ Live Demo & Documentation

You can view a live demo of the BankScreen application here: 
**[BankScreen Live Demo](https://bankscreen.lovable.app/)**

*(Note: A detailed report is available in the project files).*
