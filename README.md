# 🎓 SHIKSHA SETU  
### **AI-Based Dropout Prediction & Counselling System**

SHIKSHA SETU is an advanced AI-powered platform designed to **predict student dropout risks** caused by fees issues, low attendance, poor marks, depression, or other academic/mental challenges.  
It helps institutions by offering **early detection**, automated alerts, and intelligent counselling recommendations.

---

## 🚀 Features

### 🔍 AI & ML
- Student dropout prediction using **XGBoost** & **Scikit-learn**
- ML API wrapped using **FastAPI**
- Risk scoring system
- Analysis of attendance, marks, fees & mental health indicators

### 🧠 Counselling & Support
- AI-driven counselling suggestions
- Voice-based responses via **ElevenLabs**
- Smart behavioural insights

### 📊 Dashboards
- Admin dashboard to track high-risk students
- Student progress analytics
- Attendance and marks visualization

### 📩 Communication
- Bulk SMS alerts via **Twilio**
- Automatic notifications for risk events

### ⚡ Performance & Optimization
- **Redis cache**
- **PM2** multi-process scaling
- **Nginx** reverse proxy

### 🌐 Frontend Experience
- **Next.js**
- **TailwindCSS**
- **GSAP animations**
- **Framer Motion**
- **Spline 3D** elements

---

## 🧱 Tech Stack

### Frontend  
- Next.js  
- Tailwind CSS  
- GSAP  
- Framer Motion  
- Spline  

### Backend  
- Node.js  
- Express  
- FastAPI (ML services)

### Database  
- MongoDB  

### DevOps / Tools  
- Redis  
- PM2  
- Nginx  
- Vercel (Deployment)

---

## 🔐 Environment Variables

Create a `.env` file and include:

```env
MONGO_URI=
TWILIO_ACCOUNT_SID=
TWILIO_AUTH_TOKEN=
REDIS_URL=
FASTAPI_URL=
ELEVENLABS_API_KEY=
JWT_SECRET=
