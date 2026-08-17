# AI Based Employee Wellness Management Platform – MoodMentor

## 📌 Project Overview

**MoodMentor** is an AI-powered Employee Wellness Management Platform designed to understand employee emotional well-being and provide personalized wellness support.

Employees may experience stress, sadness, anger, fear, or other emotional changes during their work life. These changes may not always be visible to HR or managers. MoodMentor provides a privacy-conscious platform where employees can record their moods, write journal entries, upload text/CSV content, interact with an AI wellness chatbot, and optionally analyze facial emotions.

The platform uses multilingual NLP, sentiment analysis, emotion detection, facial emotion recognition, and AI-based wellness assistance to understand employee well-being and provide supportive recommendations.

---

## 🎯 Objectives

- Track employees' daily moods and emotional changes.
- Analyze journal entries and uploaded text using NLP.
- Support multiple languages for wellness analysis.
- Detect sentiment and emotions from employee text.
- Provide optional facial emotion recognition.
- Provide AI-powered wellness conversations.
- Generate personalized wellness recommendations.
- Provide authorized HR/management insights.
- Maintain secure authentication and privacy-conscious data handling.

---

## ✨ Key Features

### 👤 Employee Features

- User registration and login
- Secure password protection
- Daily mood check-ins
- Mood history and recent entries
- Journal entry creation
- Multilingual journal analysis
- Text file upload
- CSV file upload
- Emotion detection from text
- Sentiment analysis
- Optional facial emotion recognition
- AI wellness chat
- Personalized wellness recommendations
- Wellness support based on detected emotional state

### 👨‍💼 HR / Manager Features

- Authorized access to wellness insights
- Mood and emotion analytics
- Employee wellness trends
- Analysis of emotional patterns
- Supportive intervention insights

### 🔐 Security Features

- JWT-based authentication
- Bcrypt password hashing
- Email OTP verification
- Gmail SMTP integration
- Role-based access for employee and HR/management functionality
- PostgreSQL/Neon database
- Privacy-conscious handling of employee wellness information

---

## 🧠 AI & NLP Components

### Multilingual NLP

The platform supports multilingual text processing and wellness analysis.

**Languages tested:**
- English
- Telugu
- Hindi
- Marathi
- Bengali
- Tamil

### Sentiment Analysis

**VADER** is used for sentiment analysis to identify the overall sentiment expressed in text.

### Emotion Detection

**BERT / GoEmotions** is used for detecting emotional categories from text.

The system can identify emotions such as:
- Happiness
- Sadness
- Anger
- Fear
- Stress-related emotional states
- Other supported emotion categories

### Facial Emotion Recognition

**DeepFace** with **OpenCV** is used for optional facial emotion recognition from an uploaded/captured image.

### AI Wellness Chat

**Qwen 2.5 LLM** is used to provide conversational wellness support and personalized guidance based on employee concerns.

---

## 🏗️ System Architecture

The platform follows a layered architecture:

```text
Employee / HR / Manager
          ↓
   Streamlit Frontend
          ↓
      FastAPI
          ↓
   AI / NLP Services
          ↓
PostgreSQL / Neon Database

AI/NLP Services
Multilingual NLP
       ↓
Sentiment Analysis – VADER
       ↓
Emotion Detection – BERT / GoEmotions
       ↓
Facial Emotion – DeepFace / OpenCV
       ↓
AI Wellness Chat – Qwen 2.5
Security Layer
JWT Authentication
Bcrypt Password Hashing
Email OTP
Gmail SMTP

Security mechanisms operate across authentication and data-access operations.

🛠️ Technology Stack
Programming & Application
Python
Streamlit
FastAPI
Database
PostgreSQL
Neon Database
SQLAlchemy
AI & NLP
Multilingual NLP
VADER
BERT / GoEmotions
Qwen 2.5
DeepFace
OpenCV
Authentication & Security
JWT
Bcrypt
Email OTP
Gmail SMTP
Development Tools
Google Colab
GitHub
🔄 Application Workflow
1. User Authentication

The user creates an account and securely logs into the platform.

Sign Up
   ↓
Password Hashing using Bcrypt
   ↓
PostgreSQL / Neon
   ↓
Login
   ↓
JWT Authentication
2. Mood Tracking

Employees can record their current mood through simple mood check-ins.

The platform maintains timestamped mood records that can later be used for understanding wellness trends.

3. Journal Analysis

Employees can write their thoughts or feelings in the journal.

The system performs multilingual preprocessing and emotion/sentiment analysis to understand the emotional state expressed in the entry.

4. Text / CSV Analysis

Employees can upload supported text or CSV files.

The uploaded content is processed using NLP techniques to identify sentiment and emotional patterns.

5. Facial Emotion Recognition

The employee can optionally provide a facial image.

DeepFace/OpenCV processes the image and provides facial emotion recognition results.

6. AI Wellness Chat

Employees can interact with the AI wellness assistant.

Qwen 2.5 provides conversational and supportive wellness guidance.

7. Recommendations

Based on the employee's emotional state and analysis, the platform provides personalized wellness recommendations.

8. HR Analytics

Authorized HR/management users can access wellness insights and understand broader mood and emotional trends while maintaining privacy-conscious access.

📊 Wellness Analytics

MoodMentor can provide insights such as:

Current mood
Mood history
Recent journal emotions
Sentiment trends
Emotion distribution
Facial emotion results
Wellness recommendations
Employee wellness trends for authorized HR users

These insights help organizations understand wellness patterns and identify opportunities for timely supportive interventions.

🔐 Privacy & Security

Employee wellness information is sensitive and therefore the platform follows a privacy-conscious approach.

Security mechanisms include:

JWT authentication
Bcrypt password hashing
OTP-based verification
Gmail SMTP for email delivery
Authorized HR access
Secure PostgreSQL/Neon database storage

The platform is intended to support employee wellness rather than make employment decisions based solely on emotional analysis.


💡 Project Highlights
AI-powered employee wellness platform
Multilingual NLP support
Text sentiment and emotion analysis
Journal-based emotional analysis
Optional facial emotion recognition
AI wellness chatbot
Personalized recommendations
Secure authentication
HR wellness analytics
PostgreSQL/Neon database integration
Privacy-conscious design
🚀 Future Enhancements
Real-time mood trend monitoring
More Indian and international language support
Improved emotion classification
Voice-based wellness interaction
Mobile application
Personalized wellness plans
Advanced HR wellness dashboards
More comprehensive privacy and consent controls
👥 Team Members
Soham Pal
Bharath Reddy
Jeevan
Siddharth
Navaneetha
Dhanusha

Under the Guidance of
Ms. Jayashri

🎓 Program

Infosys Springboard

📜 License

This project is licensed under the MIT License.


