<div align="center">

# 🤖 N8N-Ai-Chat-Agent

### 🚀 A Powerful AI Chat Agent | n8n ⚡ Google Gemini 🧠 Memory ⚡SerpAPI 🧮 Calculator

[![n8n](https://img.shields.io/badge/n8n-0.268.0-%23EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io/)
[![Google Gemini](https://img.shields.io/badge/Google%20Gemini-AI-%234285F4?style=for-the-badge&logo=googlegemini&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![License](https://img.shields.io/badge/License-MIT-%23FFD966?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Made with Biggan](https://img.shields.io/badge/Made%20with-❤️-%23ff69b4?style=for-the-badge)](https://github.com/Biggan2003)

</div>

---

<img width="1273" height="783" alt="Screenshot 2025-12-26 014453" src="https://github.com/user-attachments/assets/fc5c03e2-dd9b-4a42-8e6e-c2875928ff43" />

## 📖 Overview

**N8N-Ai-Chat-Agent** is an intelligent chatbot built on the [n8n](https://n8n.io/) automation platform. It combines the power of **Google Gemini AI**, **conversation memory**, and various **tools** (like Calculator) to deliver an interactive chat experience.

> 💡 In simple terms: When you chat with this agent, it remembers your previous messages and can use tools like a calculator when needed!

---

## ✨ Features

| Feature | Description |
|:--------|:------------|
| 🧠 **Conversation Memory** | Remembers entire chat history using Simple Memory node |
| 🤖 **Google Gemini AI** | Generates smart, natural responses using Gemini models |
| 🧮 **Calculator Tool** | Agent can automatically call calculator for math problems |
| 🔧 **Tool-Calling Support** | AI Agent node can decide when to use available tools |
| 💬 **Chat Interface** | Clean "When chat message received" trigger for easy integration |
| 🔌 **Modular Design** | Each node is independent and replaceable |

---

## 📊 Workflow Architecture





---

## 🚀 Setup Guide

### Prerequisites

| Requirement | Description |
|-------------|-------------|
| **n8n** | Self-hosted or n8n.cloud account (v0.268.0 or higher) |
| **Google Gemini API Key** | Get from [Google AI Studio](https://makersuite.google.com/app/apikey) |
| **Node.js** | If self-hosting (v18+ recommended) |

### Installation Steps

1. **Install n8n** (if self-hosting)
   ```bash
   npm install n8n -g
   n8n start
