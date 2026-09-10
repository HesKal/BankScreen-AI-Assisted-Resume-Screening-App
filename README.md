# 🏦 BankScreen - AI-Assisted Résumé Screening App
<p align="center">
  <img src="https://img.shields.io/badge/AI%20Integration-Enabled-blue?style=for-the-badge" alt="AI Integration">
  <img src="https://img.shields.io/badge/Platform-Lovable%20No--Code-orange?style=for-the-badge" alt="Lovable">
  <img src="https://img.shields.io/badge/Database-Supabase-green?style=for-the-badge" alt="Supabase">
</p>

This repository contains the documentation and details for **BankScreen**, an AI-assisted web application designed specifically for the banking sector. This project was built using the Lovable no-code platform as part of the "Artificial Intelligence Foundations" course.

<p align="center">
  <img width="947" alt="BankScreen Dashboard" src="https://github.com/user-attachments/assets/42fff2da-9559-45ab-831f-197f8c2dbd6b" />
</p>

---

## 🚀 Project Overview

The banking sector faces a unique challenge during recruitment due to strict regulatory requirements and the need for highly specialized roles (e.g., Compliance Officer, AML Analyst ). Manually reviewing hundreds of résumés for specific certifications and clearances is time-consuming and error-prone. 

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

## 💡 My Role & Contributions (Hessa Khalfan)

As a core team member, my primary responsibilities focused on data management, workflow logic, and ensuring the transparency of the AI system:

*   **Data Architecture & Form Logic:** Designed and configured the "Add New Candidate" form, implementing strict validation rules and conditional logic for accurate HR data entry.
*   **Data Management & State Synchronization:** Managed applicant records and database state, ensuring real-time synchronization between candidate statuses (e.g., Shortlisted, Rejected), the main dashboard, and applicant tables.
*   **Algorithmic Transparency:** Configured the dynamic **Score Breakdown panel**. This was a critical feature to ensure the AI's point-by-point calculation was fully transparent, explainable, and trustworthy for HR users.
*   **Quality Assurance (UAT):** Conducted rigorous User Acceptance Testing (UAT) across all screens, specifically validating the AI Assistant's responses against real-world banking compliance scenarios.

This project demonstrated how AI-powered no-code tools can be leveraged to build functional, real-world business applications, emphasizing the importance of logic, data validation, and AI explainability.

---

## 💻 User Interface & Screens

The UI is designed with a professional Navy Blue and White color palette to convey trust and reliability. 

<p align="center">
  <img width="346" alt="Screen 1" src="https://github.com/user-attachments/assets/d220f8d0-514f-4723-ba37-34abf760748e" />
  <img width="339" alt="Screen 2" src="https://github.com/user-attachments/assets/ac3a4c95-dc5b-4b77-87cd-9713a0521faf" />
</p>
<p align="center">
  <img width="514" alt="Screen 3" src="https://github.com/user-attachments/assets/62ef2c62-a127-4c03-8896-5ef835d710d0" />
  <img width="510" alt="Screen 4" src="https://github.com/user-attachments/assets/e906de33-a4a3-45a0-921f-049432b5ce9d" />
</p>

---

## 🔗 Live Demo & Documentation

You can view a live interactive demo of the BankScreen application here: 
**[🚀 BankScreen Live Demo](https://bankscreen.lovable.app/ )**

### 📂 Project Files:
* **[📄 Read the Full Project Report](BankScreen-Report.pdf)**
* **[📊 View the Presentation Slides](BankScreen-Presentation.pdf)**
* **[📁 Download the Synthetic Dataset (Excel)](ResumeScreeningApp_Data_120.xlsx)**

