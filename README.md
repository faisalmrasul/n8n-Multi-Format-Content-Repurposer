# 🚀 n8n Multi-Format Content Repurposer

A powerful, production-grade automation workflow that takes long-form articles and automatically generates **platform-optimized content** for LinkedIn, Twitter/X, Email, Instagram, YouTube, and more — using advanced prompt engineering and Groq AI.

---

## ✨ Features

- **6 Platform Formats**:
  - LinkedIn Post (Authority style)
  - Twitter/X Thread (3-part)
  - Email Newsletter Teaser
  - Instagram Caption + Hashtags
  - YouTube Title + Description
  - Short Summary

- Built with **n8n** (self-hosted & free)
- Powered by **Groq** (`llama-3.3-70b-versatile`)
- Clean HTML email delivery
- Robust input sanitization & parsing
- Easy to customize

---

## 🛠️ Tech Stack

- **Orchestration**: n8n (Community Edition)
- **AI Engine**: Groq Cloud API
- **Runtime**: JavaScript (ES6)
- **Delivery**: Gmail API

---

## 📥 Quick Start

### 1. Deploy Locally

```bash
npm install -g n8n
n8n start