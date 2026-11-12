# AI Career Coach & Interview Preparation Assistant 🚀

An AI-powered career guidance and interview preparation assistant built using **n8n, Google Gemini, Google Sheets, and Gmail**.

## 📌 Project Overview

This project helps students and freshers receive personalized career guidance and interview preparation reports based on their educational qualifications, technical skills, career goals, and job descriptions.

The workflow uses Google Gemini to generate a personalized report, stores the report in Google Sheets, and sends it to the student's email automatically.

## 🎯 Project Objectives

- Automate career guidance using Generative AI.
- Generate personalized interview preparation reports.
- Identify skill gaps and suggest learning roadmaps.
- Store student reports automatically.
- Deliver reports through email.

## 🛠️ Technologies Used

- n8n – Workflow automation
- Google Gemini – AI report generation
- Google Sheets – Report storage
- Gmail – Email delivery
- HTML – Professional email design

## ⚙️ Workflow Process

1. **Form Submission:** Collects student information.
2. **Edit Fields:** Organizes the submitted information.
3. **Basic LLM Chain:** Uses Google Gemini to generate the career report.
4. **Google Sheets:** Stores student details and AI-generated reports.
5. **Gmail:** Sends the personalized report through email.
6. **Error Handling:** Routes Gmail failures to a separate Google Sheets error-log branch.

## ✨ Key Features

- Personalized AI career guidance.
- Skill analysis and development roadmap.
- 10 interview questions with answers.
- Practical project suggestions.
- Daily learning plan.
- Automated report storage.
- Professional HTML email delivery.
- Email error logging configuration.

## 📋 AI Report Sections

1. Career Profile
2. Skill Analysis
3. Skill Development Roadmap
4. Interview Preparation
5. Practical Project Suggestions
6. Daily Learning Plan
7. Career Improvement Tips
8. Final Recommendation

## 🚀 Setup Instructions

1. Download the workflow JSON from this repository.
2. Import it into your n8n instance.
3. Connect your own Google Gemini credentials.
4. Connect your Google Sheets account.
5. Select your own spreadsheet and configure the required columns.
6. Connect your Gmail account.
7. Test the workflow with sample student information.
8. Publish the workflow when everything works.

**Note:** The exported workflow does not include credentials. You must configure your own accounts and spreadsheet before running it.

## 🔮 Future Enhancements

- AI-based resume analysis.
- Personalized mock interview generation.
- Skill-gap analysis.
- Learning resource recommendations.
- Student career progress dashboard.

## 👨‍💻 Author

**Vedanth G T**

BCA Student | Generative AI Enthusiast

- GitHub: [CodeWithVedanth](https://github.com/CodeWithVedanth)
- LinkedIn: [Vedanth G T](https://linkedin.com/in/vedanth-g-t-048581381)

---

⭐ If you find this project useful, feel free to explore and share your feedback!
