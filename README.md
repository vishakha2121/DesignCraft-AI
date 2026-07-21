# 🚀 DesignCraft-AI - AI Design-to-Code Platform

[![GitHub](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/vishakha2121/DesignCraft-AI)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![React](https://img.shields.io/badge/React-18.x-61DAFB)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104.x-009688)](https://fastapi.tiangolo.com/)
[![Gemini](https://img.shields.io/badge/Gemini-AI-4285F4)](https://ai.google.dev/)

> **Convert wireframes, screenshots, and Figma designs into production-ready frontend code with AI!**

![DesignCraft-AI Banner](https://via.placeholder.com/1200x400/6C63FF/FFFFFF?text=DesignCraft-AI)

---

## 📋 Table of Contents
- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [📸 Screenshots](#-screenshots)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [🔧 Installation](#-installation)
- [⚙️ Configuration](#️-configuration)
- [📚 API Documentation](#-api-documentation)
- [🎨 UI Components](#-ui-components)
- [🧪 Testing](#-testing)
- [📦 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👥 Authors](#-authors)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🌟 Overview

**DesignCraft-AI** is an innovative web application that leverages **Google's Gemini Vision-Language Model** to automatically convert design mockups, wireframes, screenshots, and Figma exports into **production-ready frontend code**.

### 🎯 Problem Statement
- Designers spend hours creating UI mockups
- Developers manually convert designs to code
- Time-consuming and error-prone process
- Design-to-development handoff challenges

### 💡 Our Solution
- **Upload** any design image
- **AI analyzes** the design structure
- **Generates** clean, production-ready code
- **Preview** and **download** the code instantly

### 🎯 Target Users
- 👨‍💻 Developers - Rapid prototyping
- 🎨 Designers - Code generation from designs
- 🏢 Startups - Quick MVP development
- 📚 Students - Learning UI development

---

## ✨ Features

### 🎨 **Design Upload**
- Drag-and-drop image upload
- Click-to-browse file selector
- Paste image from clipboard
- URL import from design tools
- Supports PNG, JPG, SVG, WebP

### 🤖 **AI Code Generation**
- **React** with hooks and functional components
- **Flutter** (Dart widgets)
- **HTML/CSS** (vanilla)
- Component-based architecture
- Responsive design implementation
- Accessibility (a11y) compliance

### 👁️ **Smart Preview**
- Split view: Design + Code
- Syntax highlighting
- Component extraction
- Color palette detection
- Typography hierarchy

### 📂 **Project Management**
- Save projects to database
- Code version history
- Project search and filter
- Batch operations
- Project status tracking

### ⚡ **Interactive Features**
- Copy to clipboard (one-click)
- Download as ZIP archive
- Export as individual files
- Code regeneration
- Component visualization

### 🎨 **UI/UX**
- Dark/Light theme toggle
- Responsive design (mobile-first)
- Smooth animations
- Loading states
- Toast notifications

---

## 📸 Screenshots

### Landing Page
![Landing Page](https://via.placeholder.com/800x400/6C63FF/FFFFFF?text=Landing+Page)

### Upload Page
![Upload Page](https://via.placeholder.com/800x400/6C63FF/FFFFFF?text=Upload+Page)

### Results Page
![Results Page](https://via.placeholder.com/800x400/6C63FF/FFFFFF?text=Results+Page)

### Dashboard
![Dashboard](https://via.placeholder.com/800x400/6C63FF/FFFFFF?text=Dashboard)

---

## 🛠️ Tech Stack

### **Frontend**
| Technology | Version | Purpose |
|------------|---------|---------|
| React | 18.x | UI Framework |
| Vite | 4.x | Build Tool |
| Tailwind CSS | 3.x | Styling |
| Shadcn UI | Latest | UI Components |
| React Router | 6.x | Routing |
| React Query | 5.x | Data Fetching |
| Axios | 1.x | HTTP Client |
| React Hook Form | 7.x | Form Handling |
| React Syntax Highlighter | 15.x | Code Display |
| Lucide React | Latest | Icons |
| React Hot Toast | 2.x | Notifications |

### **Backend**
| Technology | Version | Purpose |
|------------|---------|---------|
| Python | 3.11+ | Programming Language |
| FastAPI | 0.104.x | Web Framework |
| SQLAlchemy | 2.x | ORM |
| Alembic | 1.x | Database Migrations |
| Pydantic | 2.x | Data Validation |
| Python-JOSE | 3.x | JWT Authentication |
| Passlib | 1.x | Password Hashing |
| Pillow | 10.x | Image Processing |
| Google Generative AI | 0.3.x | Gemini API |

### **Database**
- **SQLite** (Development)
- **PostgreSQL** (Production - Optional)

### **DevOps**
| Tool | Purpose |
|------|---------|
| Docker | Containerization |
| Docker Compose | Multi-container setup |
| Git | Version Control |
| GitHub | Repository Hosting |

---

## 📁 Project Structure

---

## 🚀 Quick Start

### **Prerequisites**
- Node.js 18+
- Python 3.11+
- Git
- Gemini API Key ([Get it here](https://ai.google.dev/))

### **Clone Repository**
```bash
git clone https://github.com/vishakha2121/DesignCraft-AI.git
cd DesignCraft-AI

cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload

cd frontend
npm install
npm run dev