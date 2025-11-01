# 🎓 EDUMATE-AI

> **Your Smart AI Learning Assistant** – Generate study notes, quizzes, summaries, translations, and rewritten content using the power of Gemini AI.

---

## 🚀 Elevator Pitch

**EDUMATE-AI** is a multi-functional AI learning companion designed to help students, educators, and self-learners study efficiently.  
It uses **Google Gemini API** to generate personalized **notes, summaries, quizzes, and translations** instantly — all inside a beautiful, easy-to-use web interface.

---

## 💡 About the Project

Learning should be efficient, interactive, and AI-powered.  
I built **EDUMATE-AI** during a hackathon to simplify how students access and revise information.  

### 🔥 Inspiration
During long study sessions, I often struggled to summarize large topics and create quick revision materials.  
I wanted an AI that could **automatically generate study content** from just a topic — that’s how EDUMATE-AI was born!

### 🧩 What I Learned
- Integrating **Gemini API** with a React frontend  
- Building a clean multi-page web app using **Vite + React Router**  
- Managing API keys securely with **.env**  
- Designing responsive layouts with **CSS Flexbox** and **Grid**

### ⚙️ How I Built It
1. Used **React (Vite)** for the frontend  
2. Integrated **Gemini API** via a backend utility (`src/api/gemini.js`)  
3. Added pages for **Notes**, **Quiz**, **Summary**, **Translator**, and **Rewriter**  
4. Designed responsive UI with a modern minimal theme  

### 🚧 Challenges Faced
- Getting proper structured responses from Gemini API  
- Handling “no result” or empty responses gracefully  
- Aligning the UI to match the hackathon theme screenshots  
- Managing environment variables locally without exposing the API key

---

## 🛠️ Built With

| Category | Technologies |
|-----------|---------------|
| **Frontend** | React, Vite, JavaScript, CSS3 |
| **Backend/API** | Google Gemini API |
| **Routing** | React Router DOM |
| **Styling** | Custom CSS |
| **Version Control** | Git & GitHub |
| **Deployment (optional)** | Vercel / Netlify |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/nidhi071113/EDUMATE-AI.git
cd EDUMATE-AI
