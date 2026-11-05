# 🏥 Med-Decoder — AI-Powered Vernacular Healthcare Intelligence Platform

> **"अब मेडिकल रिपोर्ट पढ़ना होगा आसान!"**  
> *Empowering patients across India to understand complex medical reports in simple Hindi, Marathi, and English.*

---

<p align="center">
  <strong>Making Medical Reports Understandable for Everyone.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hackathon-Build%20The%20AI%20For%20YOU-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-AI%20%7C%20Healthcare-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Live-success?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-Enabled-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Integrated-FFCA28?logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?logo=nodedotjs&logoColor=white" />
</p>

---

## 🌐 Live Application

<p align="center">
  <a href="https://med-decoder-i14o.onrender.com/">
    <img src="https://img.shields.io/badge/🚀_Visit_Live_Website-Med--Decoder-success?style=for-the-badge" />
  </a>
</p>

| Resource | Link |
|---|---|
| 🌐 Live Website | https://med-decoder-i14o.onrender.com/ |
| 🔐 Patient Login | https://med-decoder-i14o.onrender.com/login |
| 💻 GitHub Repository | https://github.com/mohammadjubaid76-collab/Med_Decoder |

**Hosting Platform:** Render

---

## 📌 1. Project Overview

**Med-Decoder** is an AI-powered healthcare report simplification platform designed to make complex medical laboratory reports easier to understand.

Medical reports often contain technical terminology, abbreviations, numerical values, and clinical reference ranges that are difficult for ordinary patients to interpret.

Med-Decoder aims to bridge this healthcare literacy gap by helping patients and caregivers understand laboratory reports through simplified explanations, multilingual support, and structured health information.

The platform focuses on making medical information more accessible in:

- English
- Hindi
- Marathi

### 🎯 Our Mission

To make healthcare information more understandable, accessible, and patient-friendly through AI-powered technology.

---

## 🚨 2. Problem Statement

Medical reports are essential for understanding a person's health condition, but many patients face difficulties interpreting them.

### Major Challenges

1. **Complex Medical Terminology:** Laboratory reports contain technical words that ordinary patients may not understand.
2. **Language Barriers:** Many people are more comfortable understanding health information in their native language.
3. **Reference Range Confusion:** Patients often struggle to understand whether a laboratory value is normal, high, low, or borderline.
4. **Prescription Readability:** Handwritten prescriptions can be difficult to read and interpret.
5. **Limited Health Literacy:** Patients may not know which questions to ask their doctors after receiving their reports.

### 💡 Our Approach

Med-Decoder transforms complex medical information into understandable, structured, and multilingual explanations.

---

## 💡 3. Our Solution

Med-Decoder provides a patient-friendly platform that helps users interpret laboratory reports and understand medical information.

Our solution focuses on:

- Uploading laboratory reports.
- Extracting and organizing report information.
- Explaining medical terms in simpler language.
- Presenting clinical reference-range indicators.
- Providing multilingual explanations.
- Generating suggested questions for doctor consultations.
- Supporting prescription handwriting interpretation.

The objective is to improve patient understanding without replacing professional medical advice.

---

## ✨ 4. Key Features

| Feature | Description |
|---|---|
| 📄 Report Upload | Upload supported laboratory report documents and images. |
| 🧠 AI-Powered Report Decoding | Simplify complex medical information. |
| 🌐 Multilingual Support | English, Hindi, and Marathi explanations. |
| 📊 Clinical Range Indicators | Display Normal, High, Low, and Borderline statuses. |
| 💊 Prescription Decoder | Support interpretation of handwritten prescription information. |
| 🩺 Doctor Question Assistant | Generate three suggested questions for doctor consultations. |
| 📚 Report History | Access previously decoded reports. |
| 🔐 Authentication | Firebase-based authentication and role-aware access. |
| 📱 Responsive Dashboard | Modern healthcare dashboard interface. |
| 🔔 Notifications | User-friendly notification and toast messages. |

---

## 🧠 5. AI Integration & Intelligence Workflow

Med-Decoder uses an AI-oriented report interpretation workflow to simplify medical information.

### Report Processing Workflow

```mermaid
flowchart TD
    A["Patient Uploads Report"] --> B["Frontend Interface"]
    B --> C["Backend API"]
    C --> D["Report Processing"]
    D --> E["Extract Medical Information"]
    E --> F["Identify Test Values and Ranges"]
    F --> G["AI-Assisted Explanation"]
    G --> H["Multilingual Presentation"]
    H --> I["Patient-Friendly Dashboard"]
```

### Intelligence Capabilities

- Medical terminology simplification.
- Interpretation of structured laboratory values.
- Clinical reference-range status presentation.
- Multilingual explanation generation.
- Handwritten prescription interpretation.
- Contextual questions for doctor consultations.

### AI Technology

**Google Gemini API**

The backend is designed to integrate Google's Gemini API for AI-powered processing. A valid server-side Gemini API key is required to enable Gemini functionality.

---

## 🏗️ 6. System Architecture

Med-Decoder follows a modular frontend-backend architecture.

```mermaid
flowchart TB
    U["Patient / User"] --> F["React Frontend"]
    F --> A["Express Backend"]
    A --> R["Report Processing"]
    R --> AI["AI Processing Layer"]
    A --> FB["Firebase Admin SDK"]
    A --> D["Application Data Layer"]
    AI --> A
    FB --> A
    D --> A
    A --> F
    F --> U
```

### Architecture Components

| Layer | Technology | Responsibility |
|---|---|---|
| Frontend | React 19 | User interface and dashboard |
| Language | TypeScript | Application logic and type safety |
| Build Tool | Vite | Development and production builds |
| Styling | Tailwind CSS v4 | Responsive design system |
| Backend | Node.js + Express | API handling and server logic |
| AI Integration | Google Gemini API | AI-powered interpretation |
| Authentication / Admin | Firebase | Authentication and server-side administration |
| Deployment | Render | Application hosting |
| Version Control | GitHub | Source code management |

---

## 📁 7. Complete Project Folder Structure

Med-Decoder follows a modular and scalable project structure that separates application pages, reusable components, services, translations, shared state, datasets, and backend configuration.

```text
Med_Decoder/
│
├── index.html
│   └── HTML entry point with Plus Jakarta Sans & JetBrains Mono
│
├── metadata.json
│   └── AI Studio application metadata
│
├── package.json
│   └── Project dependencies and npm scripts
│
├── package-lock.json
│   └── Locked dependency versions
│
├── vite.config.ts
│   └── Vite configuration with Tailwind CSS v4
│
├── server.ts
│   └── Node.js and Express backend server
│
├── .env.example
│   └── Environment variable template
│
├── .gitignore
│   └── Git ignored files and directories
│
├── README.md
│   └── Project documentation
│
├── firebase-applet-config.json
│   └── Firebase application configuration
│
├── firestore.rules
│   └── Firestore security rules
│
├── scripts/
│   └── set-admin.ts
│       └── Firebase admin role configuration script
│
├── public/
│   └── assets/
│       └── Static application assets
│
├── data/
│   └── lab_report_interpretation_sft
---

## ⚖️ Safety & Medical Disclaimer

> **Med-Decoder is an educational health-literacy tool.** It does not provide medical diagnosis, treatment recommendations, or dosage instructions. Always consult a qualified healthcare professional before taking any clinical action.
