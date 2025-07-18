# AI Resume Analyzer

> **🤖 AI-powered resume analyzer with ATS scoring, job matching, and detailed feedback. Built with React, Puter.js, and Tailwind CSS. Get instant insights on your resume's performance!**

[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-6.3.3-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)


---

## 🚀 **Transform Your Resume with AI-Powered Insights!**

> **"Stop guessing if your resume will pass the ATS. Start knowing."**

Build an AI-powered Resume Analyzer with React, React Router, and Puter.js! Implement seamless auth, upload and store resumes, and match candidates to jobs using smart AI evaluations. Get custom feedback and ATS scores tailored to each listing—all wrapped in a clean, reusable UI.

### 🎯 **What You'll Get:**
- ✅ **ATS Score Analysis** - Know exactly how well your resume performs
- ✅ **AI-Powered Feedback** - Get detailed improvement suggestions
- ✅ **Job-Specific Matching** - Tailored analysis for each position
- ✅ **Modern UI/UX** - Beautiful, responsive interface
- ✅ **Zero Backend Setup** - Everything runs in the browser


## ⚙️ Tech Stack

### 🎯 **Core Technologies**
[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

- **React 19** - A popular open‑source JavaScript library for building user interfaces using reusable components and a virtual DOM, enabling efficient, dynamic single-page and native apps.

### 🛣️ **Routing & State Management**
[![React Router](https://img.shields.io/badge/React%20Router-v7.7.0-CA4245?style=for-the-badge&logo=react-router)](https://reactrouter.com/) [![Zustand](https://img.shields.io/badge/Zustand-State%20Management-764ABC?style=for-the-badge)](https://github.com/pmndrs/zustand)

- **React Router v7** - The go‑to routing library for React apps, offering nested routes, data loaders/actions, error boundaries, code splitting, and SSR support—all with a smooth upgrade path from v6.
- **Zustand** - A minimal, hook-based state management library for React. It lets you manage global state with zero boilerplate, no context providers, and excellent performance through selective state subscriptions.

### ☁️ **Backend as a Service**
[![Puter.js](https://img.shields.io/badge/Puter.js-Auth%20%26%20Storage-00D4AA?style=for-the-badge)](https://puter.com/)

- **Puter.com** - An advanced, open-source internet operating system designed to be feature-rich, exceptionally fast, and highly extensible. Puter can be used as: A privacy-first personal cloud to keep all your files, apps, and games in one secure place, accessible from anywhere at any time.
- **Puter.js** - A tiny client‑side SDK that adds serverless auth, storage, database, and AI (GPT, Claude, DALL·E, OCR…) straight into your browser app—no backend needed and costs borne by users.

### 🎨 **Styling & Build Tools**
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/) [![Vite](https://img.shields.io/badge/Vite-6.3.3-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)

- **Tailwind CSS** - A utility-first CSS framework that allows developers to design custom user interfaces by applying low-level utility classes directly in HTML, streamlining the design process.
- **Vite** - A fast build tool and dev server using native ES modules for instant startup, hot‑module replacement, and Rollup‑powered production builds—perfect for modern web development.

## 🔋 Features

### 🔐 **Authentication & Security**
[![Puter.js](https://img.shields.io/badge/Puter.js-Auth%20%26%20Storage-00D4AA?style=flat-square&logo=javascript)](https://puter.com/)
- **Zero Backend Setup** - Handle authentication entirely in the browser using Puter.js
- **Secure File Storage** - All resumes stored safely in the cloud
- **Privacy First** - Your data stays private and secure

### 📄 **Resume Management**
[![PDF Support](https://img.shields.io/badge/PDF%20Support-Upload%20%26%20Convert-red?style=flat-square)](https://mozilla.github.io/pdf.js/)
- **Drag & Drop Upload** - Easy resume upload with visual feedback
- **PDF to Image Conversion** - Automatic conversion for AI analysis
- **Multiple Resume Storage** - Keep all your resumes organized in one place

### 🤖 **AI-Powered Analysis**
[![AI Analysis](https://img.shields.io/badge/AI%20Analysis-GPT%20%26%20Claude-blue?style=flat-square)](https://openai.com/)
- **ATS Score Analysis** - Know exactly how well your resume performs with Applicant Tracking Systems
- **Job-Specific Matching** - Get feedback tailored to each job description
- **Comprehensive Feedback** - Detailed analysis across multiple categories:

| Category | Description | Score Range |
|----------|-------------|-------------|
| **ATS Compatibility** | How well your resume passes through automated screening | 0-100 |
| **Tone & Style** | Professional presentation and writing quality | 0-100 |
| **Content Quality** | Relevance and impact of your content | 0-100 |
| **Structure** | Organization and layout effectiveness | 0-100 |
| **Skills Match** | Alignment with job requirements | 0-100 |

### 🎨 **Modern UI/UX**
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-Utility%20First-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![Responsive](https://img.shields.io/badge/Responsive-All%20Devices-green?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
- **Reusable Components** - Clean, consistent UI components
- **Cross-Device Compatibility** - Works seamlessly across all devices
- **Modern Design** - Beautiful, responsive interface built with Tailwind CSS
- **Interactive Feedback** - Visual score indicators and progress bars

## 🏗️ Project Structure

```
ai_resume_analyzer/
├── app/
│   ├── components/          # Reusable UI components
│   │   ├── Accordion.tsx   # Collapsible content sections
│   │   ├── ATS.tsx         # ATS score display component
│   │   ├── Details.tsx     # Detailed feedback display
│   │   ├── FileUploader.tsx # Drag & drop file upload
│   │   ├── Navbar.tsx      # Navigation component
│   │   ├── ResumeCard.tsx  # Resume preview cards
│   │   ├── ScoreBadge.tsx  # Score indicator badges
│   │   ├── ScoreCircle.tsx # Circular score display
│   │   ├── ScoreGauge.tsx  # Gauge-style score display
│   │   └── Summary.tsx     # Summary statistics
│   ├── constants/          # Application constants
│   ├── lib/               # Utility libraries
│   │   ├── PdfToImage.ts  # PDF to image conversion
│   │   ├── puter.ts       # Puter.js integration
│   │   └── utils.ts       # Helper functions
│   ├── routes/            # Application routes
│   │   ├── auth.tsx       # Authentication page
│   │   ├── home.tsx       # Dashboard/home page
│   │   ├── resume.tsx     # Individual resume view
│   │   ├── upload.tsx     # Resume upload page
│   │   └── wipe.tsx       # Data cleanup utility
│   └── types/             # TypeScript type definitions
├── public/                # Static assets
│   ├── icons/             # SVG icons
│   ├── images/            # Image assets
│   └── pdf.worker.min.mjs # PDF.js worker
└── package.json           # Dependencies and scripts
```

## 🚀 Quick Start

> **"Get up and running in under 5 minutes!"**

Follow these steps to set up the project locally on your machine.

### 📋 Prerequisites

[![Node.js](https://img.shields.io/badge/Node.js-v18%2B-339933?style=flat-square&logo=node.js)](https://nodejs.org/)
[![Git](https://img.shields.io/badge/Git-Required-F05032?style=flat-square&logo=git)](https://git-scm.com/)
[![npm](https://img.shields.io/badge/npm-Package%20Manager-CB3837?style=flat-square&logo=npm)](https://www.npmjs.com/)

Make sure you have the following installed on your machine:

- **Git** - For version control
- **Node.js** (v18 or higher) - JavaScript runtime
- **npm** (Node Package Manager) - Package manager

### 🎯 **Step-by-Step Setup**

#### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/adrianhajdin/ai-resume-analyzer.git
cd ai-resume-analyzer
```

#### 2️⃣ **Install Dependencies**
```bash
npm install
```

#### 3️⃣ **Start Development Server**
```bash
npm run dev
```

#### 4️⃣ **Open Your Browser**
Navigate to [http://localhost:5173](http://localhost:5173) to view the project.

> ⚡ **Pro Tip:** The development server includes hot module replacement (HMR) for instant updates as you code!

## 🚀 Available Scripts

[![Development](https://img.shields.io/badge/Development-Hot%20Reload-00D4AA?style=flat-square)](https://vitejs.dev/)
[![Production](https://img.shields.io/badge/Production-Build%20%26%20Deploy-646CFF?style=flat-square)](https://vitejs.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Type%20Checking-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)

| Command | Description | Environment |
|---------|-------------|-------------|
| `npm run dev` | Start the development server with HMR | Development |
| `npm run build` | Build the project for production | Production |
| `npm run start` | Start the production server | Production |
| `npm run typecheck` | Run TypeScript type checking | Development |

## 🔧 Key Components

### Authentication
The app uses Puter.js for seamless authentication without requiring a backend. Users can sign in with their Puter account to access the resume analyzer.

### File Upload
- Supports PDF resume uploads
- Drag and drop interface
- Automatic PDF to image conversion for AI analysis
- Secure file storage using Puter's file system

### AI Analysis
The AI analysis provides comprehensive feedback across five key areas:

1. **ATS Score** - How well your resume performs with Applicant Tracking Systems
2. **Tone & Style** - Professional presentation and writing quality
3. **Content Quality** - Relevance and impact of your content
4. **Structure** - Organization and layout effectiveness
5. **Skills Match** - Alignment with job requirements

### Data Storage
- Resumes and analysis results are stored using Puter's key-value store
- Each resume gets a unique ID and comprehensive metadata
- Analysis results include detailed scores and improvement tips

## 🎨 UI Components

The project includes a comprehensive set of reusable UI components:

- **ScoreBadge** - Visual score indicators with color coding
- **ScoreCircle** - Circular progress indicators for scores
- **ScoreGauge** - Gauge-style score displays
- **ResumeCard** - Card-based resume previews
- **FileUploader** - Drag and drop file upload interface
- **Accordion** - Collapsible content sections for detailed feedback

## 🔗 Assets

Assets and snippets used in the project can be found in the video kit.

## 🚀 More

Advance your skills with Next.js Pro Course

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning adventure. They're packed with detailed explanations, cool features, and exercises to boost your skills. Give it a go!

## 📝 License

[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg?style=for-the-badge)](CONTRIBUTING.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=for-the-badge)](https://github.com/adrianhajdin/ai-resume-analyzer/pulls)

> **"Every contribution makes this project better!"**

Contributions are welcome! Please feel free to submit a Pull Request. We love seeing new features, bug fixes, and improvements.

### 🎯 **How to Contribute:**
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


---

<div align="center">

**Built with ❤️ using React, React Router, Puter.js, and Tailwind CSS**

[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![React Router](https://img.shields.io/badge/React%20Router-v7.7.0-CA4245?style=flat-square&logo=react-router)](https://reactrouter.com/)
[![Puter.js](https://img.shields.io/badge/Puter.js-Auth%20%26%20Storage-00D4AA?style=flat-square)](https://puter.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.4-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

</div>
