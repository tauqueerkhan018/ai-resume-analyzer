# 🤖 AI Resume Analyzer

> AI-powered resume analyzer that evaluates resumes against job descriptions, calculates ATS compatibility, identifies missing skills, and provides actionable suggestions using Google's Gemini AI.

![React](https://img.shields.io/badge/React-19-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8)
![Claude](https://img.shields.io/badge/Claude-3.5_Haiku-orange)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)

---

## 📸 Demo

https://mtk-ai-resume-analyzer-bnrux.puter.site/

![Demo](./public/images/resume-scan.gif)

## 📖 About

Recruiters spend only a few seconds reviewing each resume, and Applicant Tracking Systems (ATS) often filter resumes before a human ever sees them.

AI Resume Analyzer helps candidates improve their resumes by:

- Uploading a PDF resume
- Comparing it against a job description
- Calculating ATS compatibility
- Detecting missing skills
- Providing AI-generated suggestions for improvement


## ✨ Features

- 📄 PDF Resume Upload
- 🤖 AI Resume Analysis
- 🎯 ATS Compatibility Score
- 📊 Resume Score Dashboard
- 🔍 Missing Skills Detection
- 💡 AI Improvement Suggestions
- ⚡ Fast React Router 7 App
- 📱 Responsive UI
- 🐳 Docker Support


## ✨ Features-1

- 📄 **PDF Resume Upload**  
  Upload resumes in PDF format for instant analysis.

- 🤖 **AI-Powered Resume Analysis**  
  Analyze resumes using **Claude 3.5 Haiku** to provide personalized feedback.

- 🎯 **ATS Compatibility Score**  
  Evaluate how well a resume aligns with Applicant Tracking Systems (ATS).

- 🔍 **Job Description Matching**  
  Compare resumes against job descriptions to identify missing skills and keyword gaps.

- 📊 **Detailed Resume Insights**  
  Get section-wise scores, strengths, weaknesses, and improvement suggestions.

- ⚡ **Fast & Responsive UI**  
  Built with React Router, TypeScript, and Tailwind CSS for a smooth user experience.

- 🐳 **Docker Support**  
  Run the application consistently across different environments using Docker.


## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React 19, React Router 7, Vite, TypeScript |
| **Styling** | Tailwind CSS |
| **AI** | Puter.js AI SDK, Claude 3.5 Haiku |
| **PDF Processing** | PDF.js |
| **State Management** | Zustand |
| **Containerization** | Docker |
| **Package Manager** | npm |


## 📂 Project Structure

```text
ai-resume-analyzer/
├── app/
│   ├── components/      # Reusable UI components
│   ├── constants/       # Static values and configuration
│   ├── lib/             # Utility functions and helpers
│   ├── routes/          # Application routes
│   ├── types/           # TypeScript type definitions
│   ├── app.css
│   ├── root.tsx
│   └── routes.ts
│
├── public/
│   ├── images/          # Images and GIFs
│   ├── icons/           # SVG icons
│   └── ...
│
├── Dockerfile
├── package.json
├── tsconfig.json
└── README.md
```



### Directory Overview

- **app/components** – Reusable UI components.
- **app/routes** – Route-based pages powered by React Router.
- **app/lib** – Helper functions and shared utilities.
- **app/constants** – Application constants and configuration.
- **app/types** – Shared TypeScript interfaces and types.
- **public** – Static assets including images, icons, and GIFs.



## 🚀 Getting Started

### Prerequisites

Before running this project, ensure you have the following installed:

- Node.js **18+**
- npm
- Git
- Docker *(optional, for containerized deployment)*

### Installation

1. Clone the repository

```bash
git clone https://github.com/tauqueerkhan018/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Install dependencies

```bash
npm install
```

3. Create a `.env` file

```env
VITE_PUTER_APP_ID=your_puter_app_id
```

4. Start the development server

```bash
npm run dev
```

The application will be available at:

```
http://localhost:5173
```

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
VITE_PUTER_APP_ID=your_puter_app_id
```

> Replace `your_puter_app_id` with your Puter application ID.


## 📦 Available Scripts

| Command | Description |
|----------|-------------|
| `npm run dev` | Start the development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## 📸 Screenshots

### 🏠 Home Page

*Landing page where users can upload their resumes and begin the analysis.*

![Home](./public/images/home.png)

---

### 📄 Resume Upload

*Upload a PDF resume for AI-powered evaluation.*

![Upload](./public/images/upload.png)

---

### 📊 Analysis Dashboard

*View ATS score, resume strengths, weaknesses, and personalized AI recommendations.*

![Analysis](./public/images/analysis.png)


## 🧠 How It Works

1. 📄 Upload your resume in PDF format.
2. 📑 Paste or upload a job description.
3. 🤖 Claude 3.5 Haiku analyzes your resume using the Puter.js AI SDK.
4. 🎯 The application compares your resume against the job description.
5. 📊 An ATS compatibility score is generated.
6. 💡 Receive personalized feedback, missing skills, and actionable improvement suggestions.

7. ## 🔄 Workflow

```mermaid
flowchart LR
    A[Upload Resume PDF] --> B[Extract Resume Text]
    B --> C[Enter Job Description]
    C --> D[Claude 3.5 Haiku via Puter.js]
    D --> E[Analyze Resume]
    E --> F[Generate ATS Score]
    E --> G[Identify Missing Skills]
    E --> H[Provide AI Suggestions]

## 🗺️ Roadmap

### Completed
- ✅ AI-powered resume analysis
- ✅ ATS compatibility scoring
- ✅ Job description matching
- ✅ PDF resume upload
- ✅ Responsive user interface
- ✅ Docker support

### Planned Features
- 🚀 Resume version history
- 🚀 Cover letter generation
- 🚀 Resume comparison
- 🚀 Export analysis as PDF
- 🚀 AI interview question generator
- 🚀 Authentication & cloud sync
- 🚀 Multi-language resume support
