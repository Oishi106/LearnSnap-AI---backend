# LearnSnap AI - backend
# ⚙️ LearnSnap AI Backend

<p align="center">
<img src="./assets/banner.png" width="100%">
</p>

<p align="center">
AI Processing Engine powered by Gemma 4 Vision
</p>

---

## 🌐 API

https://learnsnap-ai-backend.onrender.com/

---

# 🧠 What Does This Backend Do?

This backend is the intelligence layer behind LearnSnap AI.

It receives uploaded images, communicates with **Gemma 4 Vision**, processes the AI responses, stores analysis history in MongoDB, and returns structured JSON responses to the frontend.

Unlike a traditional chatbot backend, every endpoint is designed around **single-shot AI workflows**.

---

# 🔥 Supported AI Workflows

## 📚 Whiteboard Analysis

Input

```
Whiteboard Image
```

Output

- Markdown Notes
- Summary
- Flashcards
- Quiz
- Key Concepts

---

## 💊 Prescription Analysis

Input

```
Prescription Image
```

Output

- Medicine List
- Bangla Explanation
- Schedule Interpretation
- Confidence Flags
- Safety Disclaimer

---

# 🤖 How Gemma Works

Gemma 4 Vision acts as the reasoning engine.

Instead of extracting text only, it:

✔ Understands image layout

✔ Recognizes educational context

✔ Reads handwritten prescriptions

✔ Reorganizes information

✔ Generates new educational content

✔ Flags uncertain text instead of guessing

---

# ⚡ API Endpoints

| Method | Endpoint |
|---------|----------|
| POST | /api/whiteboard/analyze |
| POST | /api/prescription/analyze |
| GET | /api/history |

---

# 🏗 Tech Stack

Backend Framework

- Node.js
- Express.js

Database

- MongoDB
- Mongoose

Image Upload

- Multer

AI

- Gemma 4 Vision
- Gemini API

Deployment

- Vercel

---

# 📂 Architecture

```
Client

↓

Express API

↓

Upload Validation

↓

Gemma 4 Vision

↓

Structured Response

↓

MongoDB

↓

Frontend
```
---

# 🔐 Environment Variables

```
PORT=

MONGODB_URI=

GEMMA_API_KEY=
```

---

# 🚀 Deployment

Frontend

https://learnsnap-ai.vercel.app/

Backend

https://learnsnap-ai-backend.onrender.com

---

# 👥 Team

**UIU Infyra**

---

Built for **Build with Gemma @ Bangladesh Hybrid Hackathon 2026**
