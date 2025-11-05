# 💼✨ AI Resume Builder (MERN + OpenAI)

A full-stack **AI-powered Resume Builder App** built using the **MERN stack** and **OpenAI API** 🤖.  
This app lets users **create, edit, enhance, download, and share** professional resumes with ease.  
You can also **generate AI-enhanced summaries**, **switch templates**, and **share your resume via a unique link** 🌐.  

---

## 🚀 Features

✨ **AI-Powered Enhancements** — Instantly improve your professional summary and job descriptions using OpenAI.  
🎨 **Multiple Resume Templates** — Switch between elegant templates and preview in real time.  
📄 **Download as PDF** — Export your resume in a clean, professional format.  
🔗 **Shareable Resume Link** — Share your resume with a unique public link.  
🔐 **Authentication** — Secure login/signup using JWT and bcrypt encryption.  
🖼️ **File Uploads** — Upload profile images or documents with ImageKit and Multer.  
📱 **Responsive UI** — Built with Tailwind CSS and Lucide Icons for a sleek and modern design.  
🔔 **Smart Notifications** — Get instant feedback with React Hot Toast alerts.  

---

## 🧠 Tech Stack

### 💻 **Frontend**
- ⚛️ React 19  
- 🧩 Redux Toolkit  
- 🚏 React Router DOM 7  
- 🎨 Tailwind CSS 4  
- 🖋️ Lucide React Icons  
- 🌐 Axios  
- 🔥 React Hot Toast  
- 🖨️ React to Print  
- 📘 React PDFToText  
- ⚡ Vite  

### 🛠️ **Backend**
- 🟢 Node.js  
- 🚀 Express.js  
- 🍃 MongoDB + Mongoose  
- 🤖 OpenAI API  
- 🖼️ ImageKit  
- 📂 Multer  
- 🔐 Bcrypt  
- 🔑 JSON Web Token (JWT)  
- ⚙️ Dotenv  
- 🌍 CORS  
- ♻️ Nodemon  

---

## 🧾 How It Works
1. **Sign Up / Log In** securely using JWT-based authentication.  
2. **Create or upload** your resume details easily.  
3. Use **AI enhancement** to polish your professional summary & job description.  
4. **Preview** and **switch templates** to fit your style.  
5. **Download** your resume or **share** it via a unique link.  

---

🔐 Authentication Flow

User signs up → password hashed with bcrypt → saved in MongoDB

User logs in → JWT token generated → stored in localStorage

Protected routes validated using JWT on backend

User logs out → JWT token removed from client

---

🤖 AI Integration

Enhance Professional Summaries and Job Descriptions using OpenAI API.

Context-aware AI suggestions tailored for industry standards.

Saves AI-enhanced content in MongoDB for each user.

---
