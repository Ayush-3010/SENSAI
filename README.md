# 🚀 SensAI

**SensAI** is an AI-powered career growth & interview preparation platform designed to help users sharpen their technical skills, track performance, and build job-ready resumes — all in one place.

From AI-generated quizzes to industry insights and resume building, SensAI acts as a personal career assistant.

---

## ✨ Features

👥 **User Authentication** – Secure login using Clerk.  
🧠 **AI Industry Insights** – Salary trends, demand level, skills & market outlook powered by Gemini AI.  
🎯 **AI Interview Quizzes** – Industry & skill-based technical quizzes (10 questions).  
📊 **Performance Tracking** – Visual performance trends over time using interactive charts.  
💡 **AI Improvement Tips** – Personalized feedback based on quiz mistakes.  
📄 **Resume Builder** – Markdown-based editor with live preview and PDF export.  
⏱️ **Rate Limiting** – Built-in protection against excessive AI API usage.  
⚙️ **Background Jobs** – Automated industry insight updates via Inngest.  
🛡️ **Protected Routes** – Secure server actions and user-specific data.  

---

## 🛠️ Tech Stack

### **Frontend**
- Next.js 15 (App Router)
- React
- Tailwind CSS
- shadcn/ui
- Recharts
- @uiw/react-md-editor
- Lucide React
- Sonner (Toasts)

### **Backend**
- Next.js Server Actions
- Prisma ORM
- PostgreSQL
- Clerk Authentication
- Inngest (Background jobs)

### **AI**
- Google Gemini (`gemini-2.5-flash`)

---

## 🚀 Live Demo

👉 **Production URL:** https://sensai-rosy-beta.vercel.app

---

## 🧩 Getting Started

### **Clone the Repository**
```bash
git clone https://github.com/your-username/sensai.git
cd sensai
```

---

⚙️ Installation
```bash
npm install
```

👉 App runs at: **http://localhost:5173**

---

## 🔑 Environment Variables
```
DATABASE_URL=postgresql://username:password@host:port/dbname

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

GEMINI_API_KEY=your_gemini_api_key

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key
```

---

## 🗄️ Database Setup
```
npx prisma generate
npx prisma migrate dev
```

---

## 📂 Project Structure
```
sensai/
│── app/
│   ├── (auth)/
│   ├── (main)/
│   │   ├── dashboard/
│   │   ├── interview/
│   │   ├── resume/
│   │   ├── onboarding/
│── actions/
│── lib/
│── prisma/
│── public/
│── hooks/
│── components/
│── README.md
│── .env
```

---

## 🚀 Deployment

Deploy using:
- Vercel

Build:
```bash
npm run build
npm run start
```

---

## 🤝 Contributing

Contributions are welcome! Open issues or PRs anytime.

---

## 📜 License

MIT License