<div align="center">

# 🎓 Learnify AI

### Your Personal AI-Powered Learning Companion

**Learn smarter. Revise faster. Achieve more.**

Transform educational content into structured study notes, quizzes, and flashcards using artificial intelligence.

<br />

[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)
[![React Native](https://img.shields.io/badge/React_Native-Mobile-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-Framework-000020?style=for-the-badge&logo=expo)](https://expo.dev/)
[![AI Powered](https://img.shields.io/badge/AI-Powered-8A2BE2?style=for-the-badge)](https://github.com/HELLBOYSHADOW/Learnify-AI)

<br />

### 📥 [Download Learnify AI for Android](https://github.com/HELLBOYSHADOW/Learnify-AI/releases/latest)

</div>

---

## 📌 Overview

**Learnify AI** is an AI-powered educational application designed to make learning more efficient, interactive, and accessible.

Students often spend hours watching educational videos, reading documents, and preparing revision materials. Learnify AI simplifies this process by bringing AI-assisted learning tools together in one mobile application.

Convert educational content into structured notes, generate practice quizzes, and create flashcards to support revision and knowledge retention.

### 🎯 Project Goals

- Simplify the process of creating study materials.
- Make video-based learning easier to revise.
- Encourage active recall through quizzes and flashcards.
- Provide a convenient mobile learning experience.
- Integrate AI into practical educational workflows.

---

## ✨ Key Features

### 🎥 YouTube Video Summarization

Turn educational videos into structured learning material.

- Extract transcripts from supported YouTube videos.
- Generate AI-powered summaries and study notes.
- Organize information into key concepts, definitions, examples, and takeaways.
- Reduce the time required to prepare revision notes.

### 🧠 AI Quiz Generation

Test your understanding of educational material.

- Generate practice questions from learning content.
- Support self-assessment and active recall.
- Reinforce concepts through question-based learning.
- Help identify topics that need further revision.

### 🗂️ AI Flashcard Generation

Make revision more interactive.

- Generate flashcards from learning material.
- Organize important concepts and definitions.
- Support quick revision sessions.
- Reinforce memorization and knowledge retention.

### 📄 PDF-Based Learning

Turn supported educational documents into useful learning resources.

- Extract text from PDF documents.
- Process document content for AI-assisted learning.
- Generate quizzes from supported study materials.

### 🤖 AI Integration

Use AI services to transform raw educational content into structured learning resources.

The application uses a backend API to process supported requests and communicate with configured AI providers.

*Feature availability depends on the current application build and backend configuration.*

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React Native | Cross-platform mobile application |
| Expo | Mobile development and application builds |
| Expo Router | Application navigation |
| JavaScript / TypeScript | Application development |
| Node.js | Backend runtime |
| Express.js | REST API development |
| Google Gemini | AI-powered content generation |
| Railway | Backend hosting |
| EAS Build | Android application builds |
| Git | Version control |
| GitHub | Source code hosting and release distribution |

---

## 🏗️ System Architecture

Learnify AI follows a client-server architecture in which the mobile application communicates with a backend API to process learning requests.

```text
┌────────────────────────────────┐
│          LEARNIFY AI           │
│       Android Application      │
└───────────────┬────────────────┘
                │
                │ HTTPS Requests
                ▼
┌────────────────────────────────┐
│         BACKEND API            │
│       Node.js + Express        │
└───────────────┬────────────────┘
                │
                │ AI Requests
                ▼
┌────────────────────────────────┐
│        AI PROVIDERS             │
│       Gemini and others        │
└───────────────┬────────────────┘
                │
                │ Generated Content
                ▼
┌────────────────────────────────┐
│       LEARNING RESOURCES       │
│ Notes · Quizzes · Flashcards   │
└───────────────┬────────────────┘
                │
                ▼
┌────────────────────────────────┐
│       MOBILE INTERFACE         │
│      Results and Revision      │
└────────────────────────────────┘