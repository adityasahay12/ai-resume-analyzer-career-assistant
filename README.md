# ai-resume-analyzer-career-assistant

AI-powered Resume Analyzer & Career Assistant built using Java Spring Boot, Ollama, TinyLlama, LangChain4j, and Apache PDFBox.

# 🚀 Overview

AI Resume Analyzer & Career Assistant is an intelligent backend application that analyzes uploaded resume PDFs and generates AI-powered feedback and career suggestions using local Large Language Models (LLMs).

The project integrates Java Spring Boot with Ollama and TinyLlama to provide offline AI inference without relying on paid external APIs.

This system is designed to help users:
- analyze resumes
- extract resume content
- generate intelligent suggestions
- improve ATS compatibility
- build AI-assisted career workflows

---

# ✨ Features

- AI-powered resume analysis
- Resume PDF upload support
- Intelligent career suggestions
- REST APIs for AI interaction
- PDF text extraction using Apache PDFBox
- Local LLM integration using Ollama
- Conversational AI workflows
- Scalable Spring Boot backend architecture
- Designed for future RAG and semantic search integration

---

# 🛠️ Tech Stack

## Backend
- Java
- Spring Boot
- Maven

## AI & LLM
- Ollama
- TinyLlama
- LangChain4j

## PDF Processing
- Apache PDFBox

## Database (Future Scope)
- MySQL

---

# 🧠 Architecture

Frontend (Future)
       ↓
Spring Boot Controller
       ↓
Service Layer
       ↓
LangChain4j Integration
       ↓
Ollama Local AI
       ↓
TinyLlama Model


# 📡 API Endpoints

## 1️⃣ AI Question API

`http
GET /ai/ask?q=your-question


### Example

text
What is Java?

---

Upload a resume PDF file for AI-powered analysis.

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/adityasahay12/ai-resume-analyzer-career-assistant.git
```

---

## 2️⃣ Open Project

Open the project using:
- IntelliJ IDEA
- VS Code
- Eclipse

---

## 3️⃣ Install Dependencies

```bash
mvn clean install
```

---

## 4️⃣ Install Ollama

Download Ollama:

https://ollama.com

Run TinyLlama model:

```bash
ollama run tinyllama
```

---

## 5️⃣ Run Spring Boot Application

```bash
mvn spring-boot:run
```

---

# 🔮 Future Improvements

- JWT Authentication
- React Frontend
- ATS Score Generation
- Job Matching
- Retrieval-Augmented Generation (RAG)
- Vector Database Integration
- Semantic Search
- Resume Skill Extraction
- Cloud Deployment
- Swagger API Documentation

---

# 📚 Learning Outcomes

Through this project, I learned:

- Spring Boot backend development
- REST API architecture
- Local AI model integration
- LangChain4j workflows
- PDF document processing
- AI-assisted backend systems
- Scalable service-layer design

---

# 👨‍💻 Author

## Aditya

LinkedIn:
https://www.linkedin.com/in/aditya21s

GitHub:
https://github.com/adityasahay12

---

# ⭐ Project Goal

The goal of this project is to explore AI-powered backend systems, intelligent document analysis, and local LLM integration while building scalable and privacy-focused AI applications.

---

# 📌 Repository Topics

```text
java
spring-boot
ai
llm
ollama
langchain4j
resume-analyzer
backend
rest-api
pdf-processing
rag
semantic-search
```
