<h1 align="center">
🚀✨ SMARTQUIZZER  
Adaptive AI-Based Quiz Generator
</h1>

<p align="center">
<b>An AI-powered adaptive quiz platform that personalizes learning using intelligent question generation, real-time evaluation, and dynamic difficulty adjustment.</b>
</p>

<p align="center">
🌐 <a href="https://smartquizzer-adaptive-ai-based-quiz-7shn.onrender.com/" target="_blank"><b>Live Preview</b></a>
</p>

---

## 🧠 Overview

**SmartQuizzer** is an intelligent quiz and learning platform powered by **Large Language Models (LLMs)**.  
It generates quizzes from **topics, text, or documents**, evaluates answers using AI, and adapts difficulty based on user performance.

Unlike static quiz apps, SmartQuizzer works as a **guided learning system**, helping users understand *what to learn next*.

---

## 📌 Table of Contents

1. Introduction  
2. Tech Stack  
3. Target Users  
4. Complete System Flow (Mermaid)  
5. Architecture Diagram (Mermaid)  
6. Adaptive Quiz Logic (Mermaid)  
7. Application Flow (Mermaid)  
8. User Journey Flow (Mermaid)  
9. AI Evaluation & Feedback Flow (Mermaid)  
10. Key Features  
11. Learning Outcomes  
12. Future Enhancements  

---

## 🧠 Introduction

SmartQuizzer uses AI to:

- Generate context-aware quiz questions  
- Evaluate answers semantically  
- Adapt difficulty dynamically  
- Provide personalized learning recommendations  

This converts **assessment into continuous learning**.

---

## 🛠 Tech Stack

| Layer | Technology |
|-----|-----------|
| Frontend | React, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas |
| AI / LLM | OpenAI GPT Models |
| Logic Engine | Adaptive Difficulty Engine |
| Deployment | Render |

---

## 🎯 Target Users

- Students  
- Teachers & Trainers  
- Interview Preparation  
- E-learning Platforms  
- Corporate Training Programs  

---

## 🔄 Complete System Flow

```mermaid
flowchart TD

U[👤 User]
--> |Select Topic / Upload Text|
F[💻 React Frontend]

F
--> |Quiz Config Request|
B[🛠 Node.js / Express Backend]

B
--> |Prompt + Context|
AI[🤖 OpenAI GPT API]

AI
--> |Generated Questions|
Q[🧠 Adaptive Quiz Engine]

Q
--> |Store Quiz & Answers|
DB[(🗄 MongoDB Atlas)]

Q
--> |Evaluate Responses|
E[📊 AI Evaluation Engine]

E
--> |Performance Metrics|
L[📈 Learning Insights Engine]

L
--> |Feedback & Recommendations|
F
```
# 🧩 Adaptive Quiz Logic
flowchart TD

A[User Answer]
--> B[AI Answer Evaluation]

B
--> C[Performance Score]

C
--> D{Difficulty Decision}

D
-->|High Score| E[Increase Difficulty]

D
-->|Low Score| F[Simplify Question]

E --> G[Next Question]
F --> G


