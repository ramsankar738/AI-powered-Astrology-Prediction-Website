# 🌌 AI-powered Astrology Prediction Website

A modern, interactive astrology portal that collects user birth details and automatically sends personalized AI-generated predictions directly to the user's email.  
Built using **HTML, CSS, JavaScript** and powered by **n8n automation + OpenAI**.

---

## ✨ Features

- Beautiful astrology-themed UI with glassmorphism
- Collects detailed birth information:
  - Full Name
  - Date & Time of Birth
  - Place of Birth
  - Gender
  - Focus Area (Relationships, Career, Health, etc.)
  - User Question for AI
  - Email Address
- Sends form data securely to an **n8n Webhook**
- n8n generates a personalized prediction using **OpenAI GPT**
- n8n emails the result to the user automatically
- Fully automated workflow using:  
  `Website → Webhook → OpenAI → Gmail → Email`
- Mobile-friendly and fast UI
- Clean client-side validation

---

## 🧠 How It Works

1. User fills the form on the website  
2. Website sends a JSON payload to the n8n Webhook  
3. n8n workflow:
   - Creates a custom AI prompt
   - Sends it to OpenAI Chat Model
   - Receives the astrology prediction
   - Sends the prediction to the user's email via Gmail
4. User receives a personalized astrology reading in their inbox

---

## 🚀 Technologies Used

### **Frontend**
- HTML5  
- CSS3 (Glassmorphism + Dark UI + Astrology theme)  
- JavaScript (Form handling + Validation + Fetch API)

### **Backend / Automation**
- n8n Cloud  
- Webhook Trigger  
- Set Node  
- OpenAI Chat Model (gpt-4o / gpt-4o-mini)  
- Gmail Node
  
---

## **Check our Website here**

https://ai-astrology-prediction.netlify.app/

---


