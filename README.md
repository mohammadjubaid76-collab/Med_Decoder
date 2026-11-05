# 🏥 Med-Decoder — AI-Powered Vernacular Healthcare Intelligence Platform

> **"अब मेडिकल रिपोर्ट पढ़ना होगा आसान!"**  
> *Empowering patients across India to understand complex medical reports in simple Hindi, Marathi, and English.*

--

<p align="center">
  <p align="center">
  <img src="PASTE_LOGO_IMAGE_URL_HERE" 
       alt="Build The AI For YOU Hackathon Logo" 
       width="260" />
</p>
  <img src="https://img.shields.io/badge/AI-HEALTHCARE-1677FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/STATUS-LIVE-16A34A?style=for-the-badge" />
</p>

<p align="center">
  <strong>Making Medical Reports Understandable for Everyone.</strong>
  <br />
  <em>Breaking language barriers. Simplifying healthcare. Empowering patients.</em>
</p>

<p align="center">
  <a href="https://med-decoder-i14o.onrender.com/">
    <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-Visit_Med--Decoder-0D9488?style=for-the-badge" />
  </a>
  <a href="https://github.com/mohammadjubaid76-collab/Med_Decoder">
    <img src="https://img.shields.io/badge/GITHUB-Source_Code-181717?style=for-the-badge&logo=github" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-Enabled-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Integrated-FFCA28?logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?logo=nodedotjs&logoColor=white" />
</p>

---

## 🌐 EXPERIENCE MED-DECODER

Explore the deployed application and its healthcare-focused interface.

| Platform Resource | Access |
|---|---|
| 🌐 Live Website | [Open Med-Decoder](https://med-decoder-i14o.onrender.com/) |
| 🔐 Patient Login | [Login Portal](https://med-decoder-i14o.onrender.com/login) |
| 💻 Source Code | [GitHub Repository](https://github.com/mohammadjubaid76-collab/Med_Decoder) |
| ⚙️ Backend Status | [Health Check](https://med-decoder-i14o.onrender.com/api/health) |

<sub>Deployment Platform: Render</sub>

---

## 📖 01 — PROJECT OVERVIEW

**Med-Decoder** is an AI-powered healthcare report simplification platform designed to make complex medical laboratory reports easier to understand.

Medical reports often contain technical terminology, abbreviations, numerical values, and clinical reference ranges that can be difficult for ordinary patients to interpret.

Med-Decoder aims to bridge this healthcare literacy gap through simplified explanations, multilingual support, and structured health information.

### 🌍 Our Language Vision

| Language | Support |
|---|---|
| 🇬🇧 English | Supported |
| 🇮🇳 Hindi | समर्थित |
| 🇮🇳 Marathi | समर्थित |

### 🎯 Our Mission

To make healthcare information more understandable, accessible, and patient-friendly through AI-powered technology.

---

## 🚨 02 — THE PROBLEM

### Understanding a medical report should not be complicated.

Patients frequently face difficulties interpreting their medical reports because of:

| Challenge | Problem |
|---|---|
| 🧬 Medical Terminology | Technical medical words are difficult to understand. |
| 🌐 Language Barriers | Patients may not understand medical explanations in another language. |
| 📊 Reference Ranges | Understanding normal, high, low, and borderline values can be confusing. |
| 💊 Prescription Readability | Handwritten prescriptions can be difficult to interpret. |
| 🩺 Health Literacy | Patients may not know what questions to ask their doctors. |

**The Core Problem:** Medical information is available, but understanding it is not always easy.

---

## 💡 03 — OUR SOLUTION

Med-Decoder provides a patient-friendly platform that helps users interpret laboratory reports and understand medical information.

### What We Aim to Deliver

- Upload supported laboratory reports.
- Extract and organize report information.
- Explain complex medical terms in simpler language.
- Present clinical reference-range indicators.
- Provide multilingual explanations.
- Generate suggested questions for doctor consultations.
- Support handwritten prescription interpretation.

Our objective is to improve patient understanding without replacing professional medical advice.

---

## ✨ 04 — KEY FEATURES

| Feature | What It Does |
|---|---|
| 📄 Report Upload | Upload supported laboratory report documents and images. |
| 🧠 Report Decoding | Simplify complex medical information. |
| 🌐 Multilingual Interface | English, Hindi, and Marathi explanations. |
| 📊 Clinical Indicators | Display Normal, High, Low, and Borderline statuses. |
| 💊 Prescription Decoder | Support interpretation of handwritten prescriptions. |
| 🩺 Doctor Question Assistant | Generate three suggested consultation questions. |
| 📚 Report History | Access previously decoded reports. |
| 🔐 Secure Authentication | Firebase-based authentication and role-aware access. |
| 📱 Responsive Dashboard | Modern healthcare dashboard interface. |
| 🔔 Notifications | User-friendly notifications and toast messages. |

---

## 🧠 05 — AI INTELLIGENCE & WORKFLOW

Med-Decoder is designed around an AI-oriented report interpretation workflow.

### Report Processing Pipeline

```mermaid
flowchart TD
    A["📄 Patient Uploads Report"] --> B["💻 Frontend Interface"]
    B --> C["⚙️ Backend API"]
    C --> D["📑 Report Processing"]
    D --> E["🔍 Extract Medical Information"]
    E --> F["📊 Identify Values & Ranges"]
    F --> G["🧠 AI-Assisted Explanation"]
    G --> H["🌐 Multilingual Presentation"]
    H --> I["🏥 Patient-Friendly Dashboard"]

    style A fill:#DBEAFE,stroke:#2563EB,color:#111827
    style G fill:#EDE9FE,stroke:#7C3AED,color:#111827
    style I fill:#DCFCE7,stroke:#16A34A,color:#111827
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

The backend is designed to integrate Google's Gemini API for AI-powered processing.

<sub>Current deployment note: Gemini API is not yet configured on the live deployment. A valid server-side API key is required to enable Gemini functionality.</sub>

---

## 🏗️ 06 — SYSTEM ARCHITECTURE

Med-Decoder follows a modular frontend-backend architecture.

```mermaid
flowchart TB
    U["👤 Patient / User"]
    F["⚛️ React Frontend"]
    A["🖥️ Express Backend"]
    R["📑 Report Processing"]
    AI["🧠 AI Processing Layer"]
    FB["🔥 Firebase Admin SDK"]
    D["🗄️ Application Data Layer"]

    U --> F
    F --> A
    A --> R
    R --> AI
    A --> FB
    A --> D
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
| Programming Language | TypeScript | Application logic and type safety |
| Build Tool | Vite | Development and production builds |
| Styling | Tailwind CSS v4 | Responsive design system |
| Backend | Node.js + Express | API handling and server logic |
| AI Integration | Google Gemini API | AI-powered interpretation |
| Authentication | Firebase | Authentication and administration |
| Deployment | Render | Application hosting |
| Version Control | GitHub | Source code management |

---

## 📁 07 — PROJECT STRUCTURE

```text
Med_Decoder/
│
├── index.html
├── metadata.json
├── package.json
├── package-lock.json
├── vite.config.ts
├── server.ts
├── .env.example
├── .gitignore
├── README.md
├── firebase-applet-config.json
├── firestore.rules
│
├── scripts/
│   └── set-admin.ts
│
├── public/
│   └── assets/
│
├── data/
│   └── lab_report_interpretation_sft.csv
│
└── src/
    ├── main.tsx
    ├── App.tsx
    ├── index.css
    │
    ├── types/
    │   └── index.ts
    │
    ├── translations/
    │   └── index.ts
    │
    ├── services/
    │   └── api.ts
    │
    ├── data/
    │   ├── sampleReports.ts
    │   └── samplePrescriptions.ts
    │
    ├── context/
    │   └── AppContext.tsx
    │
    ├── layouts/
    │   ├── PublicLayout.tsx
    │   └── DashboardLayout.tsx
    │
    ├── components/
    │   ├── common/
    │   ├── dashboard/
    │   ├── report/
    │   └── prescription/
    │
    └── pages/
        ├── LandingPage.tsx
        ├── DashboardPage.tsx
        ├── UploadReportPage.tsx
        ├── ReportAnalysisPage.tsx
        ├── PrescriptionDecoderPage.tsx
        ├── MyReportsPage.tsx
        ├── HowItWorksPage.tsx
        ├── AboutPage.tsx
        ├── SettingsPage.tsx
        └── HelpSupportPage.tsx
```

### Module Responsibilities

| Directory | Purpose |
|---|---|
| `components/` | Reusable UI components |
| `pages/` | Application screens and routes |
| `layouts/` | Public and dashboard layouts |
| `services/` | Backend API communication |
| `context/` | Global application state |
| `translations/` | Multilingual dictionary |
| `types/` | TypeScript interfaces |
| `data/` | Sample reports and prescriptions |
| `scripts/` | Administrative utilities |

---

## 🔄 08 — USER JOURNEY

```mermaid
flowchart LR
    A["Open Platform"] --> B["Register / Login"]
    B --> C["Upload Report"]
    C --> D["Report Processing"]
    D --> E["Review Results"]
    E --> F["Select Language"]
    F --> G["Understand Report"]
    G --> H["Prepare Doctor Questions"]
```

### User Steps

1. Access the Med-Decoder website.
2. Register or log in.
3. Upload a supported laboratory report.
4. Process the uploaded report through the backend.
5. View simplified explanations from the configured processing workflow.
6. Select English, Hindi, or Marathi.
7. Review report values and displayed clinical statuses.
8. Use suggested questions to prepare for a medical consultation.

---

## 🔌 09 — BACKEND API DOCUMENTATION

The frontend communicates with backend services through REST API endpoints.

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/reports/upload` | Uploads a PDF or image document |
| POST | `/api/reports/decode` | Processes a report and generates a simplified interpretation |
| POST | `/api/prescriptions/decode` | Processes handwritten prescription information |
| GET | `/api/reports` | Retrieves user report history |
| GET | `/api/reports/:id` | Fetches a specific report by ID |
| GET | `/api/health` | Checks backend and service configuration |

**Backend Entry Point:** `server.ts`

### Health Check

```http
GET /api/health
```

Example response:

```json
{
  "status": "ok",
  "firebaseAdminConfigured": true,
  "firebaseProjectId": "med-decoder",
  "geminiConfigured": false
}
```

> **Note:** `geminiConfigured` indicates whether an API key is present in the server environment. It does not independently verify whether a live Gemini API request succeeds.

---

## ⚙️ 10 — TECHNOLOGY STACK

### Frontend Technologies

<p>
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white" />
</p>

### Backend Technologies

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
</p>

### AI & Cloud Services

<p>
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=black" />
</p>

### Development Tools

- Visual Studio Code
- Git and GitHub
- npm
- Render

---

## 💻 11 — INSTALLATION & LOCAL SETUP

### Prerequisites

- Node.js 18 or later
- npm
- Git
- Firebase project
- Google Gemini API key (for Gemini functionality)

### Step 1 — Clone Repository

```bash
git clone https://github.com/mohammadjubaid76-collab/Med_Decoder.git
```

### Step 2 — Open Project Directory

```bash
cd Med_Decoder
```

### Step 3 — Install Dependencies

```bash
npm install
```

### Step 4 — Configure Environment Variables

Create a `.env` file in the project root.

```env
GEMINI_API_KEY=your_gemini_api_key

FIREBASE_PROJECT_ID=your_firebase_project_id
GOOGLE_APPLICATION_CREDENTIALS=path/to/firebase-service-account.json

VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
VITE_FIREBASE_MEASUREMENT_ID=your_measurement_id
```

### Step 5 — Run Development Server

```bash
npm run dev
```

### Step 6 — Create Production Build

```bash
npm run build
```

### Step 7 — Start Production Server

```bash
npm run start
```

> **Security:** Never upload `.env` or Firebase service-account JSON files to GitHub. Keep private credentials on the server.

---

## ☁️ 12 — DEPLOYMENT

Med-Decoder is deployed on **Render**.

### Deployment Configuration

| Configuration | Value |
|---|---|
| Runtime | Node.js |
| Build Command | `npm install && npm run build` |
| Start Command | `npm run start` |
| Hosting Platform | Render |
| Source Repository | GitHub |

### Server Environment Configuration

```env
FIREBASE_PROJECT_ID=med-decoder
GOOGLE_APPLICATION_CREDENTIALS=/etc/secrets/firebase-service-account.json
GEMINI_API_KEY=your_gemini_api_key
```

The Firebase Admin service-account JSON file should be stored as a Render Secret File.

Never commit private service-account credentials to GitHub.

---

## 🔐 13 — SECURITY & PRIVACY

Med-Decoder is designed with attention to the sensitive nature of healthcare information.

### Security Considerations

- Firebase-based authentication.
- Firebase Admin SDK for server-side administrative operations.
- Server-side storage of private API credentials.
- Environment-based configuration.
- Git-based exclusion of sensitive local files.
- Educational healthcare disclaimers.

> Actual data protection, storage retention, access-control policies, and regulatory compliance must be validated before production healthcare use.

---

## 🌍 14 — SOCIAL IMPACT

### Technology With a Human Purpose

Med-Decoder aims to contribute to more accessible healthcare information.

**Expected Impact**

- Improves understanding of laboratory reports.
- Reduces confusion caused by complex medical terminology.
- Supports people who prefer regional languages.
- Helps patients prepare meaningful questions for doctors.
- Encourages better healthcare awareness and digital health literacy.

### Our Vision

A future where every individual can understand their medical information, regardless of technical knowledge or language preference.

---

## 🔮 15 — FUTURE ROADMAP

Potential future improvements include:

- 🌐 Additional Indian regional languages.
- 📷 Improved OCR for low-quality and scanned reports.
- ✍️ Enhanced prescription handwriting recognition.
- 📄 Integration with more laboratory report formats.
- 🔐 Secure patient report management.
- 🧠 More advanced AI-assisted health education.
- ♿ Accessibility improvements for elderly users.
- 🏥 Additional healthcare integrations with appropriate privacy and security safeguards.

---

## 👥 16 — MEET THE TEAM

<p align="center">
  <strong>TEAM SOPHOMORE</strong>
  <br />
  <em>Build The AI For YOU Hackathon</em>
</p>

| Role | Team Member |
|---|---|
| 🏆 Team Leader | **Mohammad Jubaid** |
| 👨‍💻 Team Member | **Nagesh Narwariya** |

### Our Objective

To develop practical AI-powered solutions that solve meaningful real-world problems through innovation, technology, and teamwork.

---

## ⚠️ 17 — MEDICAL DISCLAIMER

Med-Decoder is an educational healthcare information platform.

It is not a substitute for professional medical diagnosis, treatment, or clinical decision-making.

AI-generated explanations may contain inaccuracies. Users should always consult qualified healthcare professionals before making medical decisions.

Do not independently start, stop, or change medication based on the platform's output.

---

## ❤️ 18 — ACKNOWLEDGEMENTS

We sincerely thank the organizers of **Build The AI For YOU** for providing an opportunity to develop and present innovative AI-powered solutions.

We also acknowledge the open-source technologies and developer tools that support this project.

---

<p align="center">
  <strong>Built with ❤️ by Team Sophomore</strong>
  <br />
  <strong>MED-DECODER</strong>
  <br />
  <em>AI for Accessible Healthcare</em>
  <br /><br />
  <a href="https://med-decoder-i14o.onrender.com/">
    🌐 EXPLORE MED-DECODER
  </a>
  <br /><br />
  <sub>Breaking Language Barriers • Simplifying Healthcare • Empowering Patients</sub>
</p>
