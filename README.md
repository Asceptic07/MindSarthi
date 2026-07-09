# 🧠 MindSarthi — Campus Mental Health & Counseling Platform

[![React](https://img.shields.io/badge/React-19.0-blue.svg?logo=react)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-5.0-646CFF.svg?logo=vite)](https://vitejs.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933.svg?logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47A248.svg?logo=mongodb)](https://www.mongodb.com/)
[![Ollama AI](https://img.shields.io/badge/AI-Ollama%20LLM-black.svg)](https://ollama.ai/)

**MindSarthi** is a modern, privacy-first campus mental health and counseling assistance platform built to bridge the gap between students seeking emotional support and professional campus counselors. Combining confidential nickname-based access, local AI conversational support via **Ollama**, and streamlined appointment scheduling, MindSarthi creates a safe space for mental well-being on campus.

---

## ✨ Key Features

- **🔒 Privacy-First Student Access:** Anonymous/nickname-based profiles allowing students to seek help without fear of stigma.
- **🤖 Local AI Companion (Ollama Integration):** Intelligent conversational support with automated emergency & crisis keyword detection that immediately directs students to campus crisis help lines.
- **🧑‍⚕️ Therapist Directory & Smart Matching:** Explore verified campus counselors and match with therapists suited to individual needs.
- **📅 Seamless Appointment Booking:** Interactive scheduling for confidential counseling sessions.
- **🚨 Urgent Request Handling:** Real-time flagging of urgent counseling requests.
- **📊 Dedicated Counselor Dashboard:** Secure portal for counselors to manage appointments, track student sessions, and respond to urgent requests.
- **🎨 Modern Interactive UI:** Rich animations and responsive aesthetics powered by **Framer Motion** and **Tailwind CSS**.

---

## 🛠️ Tech Stack

### **Frontend (`/client`)**
- **Framework:** React 19 + Vite
- **Styling & UI:** Pure CSS / Tailwind CSS + Framer Motion + Lucide Icons
- **HTTP Client:** Axios

### **Backend (`/server`)**
- **Runtime & Framework:** Node.js + Express.js
- **Database:** MongoDB (via Mongoose)
- **AI Engine:** Local Ollama LLM API (`http://127.0.0.1:11434`)

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher)
- [MongoDB](https://www.mongodb.com/) running locally on `mongodb://127.0.0.1:27017/campusminds`
- [Ollama](https://ollama.ai/) installed and running locally on port `11434`

---

### 1. Clone the Repository
```bash
git clone https://github.com/Asceptic07/MindSarthi.git
cd MindSarthi
