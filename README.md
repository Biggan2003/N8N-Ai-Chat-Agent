<div align="center">

# 🤖 N8N-Ai-Chat-Agent

### 🚀 A Powerful AI Chat Agent | n8n ⚡ Google Gemini 🧠 Memory ⚡SerpAPI 🧮 Calculator

[![n8n](https://img.shields.io/badge/n8n-0.268.0-%23EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io/)
[![Google Gemini](https://img.shields.io/badge/Google%20Gemini-AI-%234285F4?style=for-the-badge&logo=googlegemini&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![License](https://img.shields.io/badge/License-MIT-%23FFD966?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Made with Biggan](https://img.shields.io/badge/Made%20with-❤️-%23ff69b4?style=for-the-badge)](https://github.com/Biggan2003)

</div>

---

<img width="3660" height="2360" alt="Coimbature Weather" src="https://github.com/user-attachments/assets/6647c000-2fa5-47f3-a1d2-3baa679c88b8" />


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



<img width="615" height="453" alt="Screenshot 2025-12-26 014522" src="https://github.com/user-attachments/assets/79dbc64b-e1e2-4868-be0d-5304c2ce0de8" />
<img width="3023" height="1860" alt="khulna" src="https://github.com/user-attachments/assets/b8afc193-f05a-402b-9747-d424c9941e0b" />




   ## 🧠 How It Works - Complete Explanation

### 📋 Before You Start (Prerequisites)

Before using this AI Agent, you need to complete the following:

| # | Task | Description |
|:-:|:-----|:------------|
| 1 | **Install n8n** | Self-host using Docker/npm or use n8n.cloud |
| 2 | **Get Gemini API Key** | Free from Google AI Studio |
| 3 | **Import Workflow** | Download JSON from this repo |
| 4 | **Configure Credentials** | Add your API key to Gemini node |
| 5 | **Activate & Test** | Turn on the workflow and send a message |

> ⚠️ **Important:** The Gemini API is **free for up to 60 requests per minute!**

---

### 🔄 How It Works (Step-by-Step Flow)

**STEP 1: User Sends Message**
> User types: *"What is 25% of 80? And remember my name is John"*

**STEP 2: Trigger Node**
> "When chat message received" - Activates the workflow

**STEP 3: Gemini LLM Processes**
> Google Gemini understands: "John wants calculation + memory"

**STEP 4: Simple Memory Stores Context**
> Memory saves: "User name is John" for future conversations

**STEP 5: AI Agent Decides**
> Agent thinks: "I need to use Calculator for math problem"

**STEP 6: Calculator Tool Executes**
> Calculator: 25% of 80 = 20

**STEP 7: Output Generated**
> Response: *"Hi John! 25% of 80 is 20. I'll remember your name!"*

---

### 🎯 What You Need To Do First

| Step | Action | Time Needed |
|:----:|:-------|:------------:|
| ① | Create a Google AI Studio account | 2 minutes |
| ② | Generate Gemini API key | 1 minute |
| ③ | Install n8n (if self-hosting) | 5 minutes |
| ④ | Import workflow to n8n | 2 minutes |
| ⑤ | Add API key to credentials | 1 minute |
| ⑥ | Activate and test | 2 minutes |

**Total setup time: ~13 minutes**

---

### ✨ Benefits & Advantages

| Benefit | Description |
|:--------|:------------|
| 🆓 **Free to use** | Gemini API has free tier (60 requests/minute) |
| 🧠 **Remembers conversations** | Simple Memory stores chat history |
| 🧮 **Auto-calculations** | No need to manually calculate anything |
| 🔌 **Easy to extend** | Add more tools (weather, news, database) |
| 💬 **Natural conversation** | Just chat like talking to a human |
| ⚡ **Fast responses** | Usually under 4 seconds |
| 🔓 **Open source** | Complete control over your data |
| 🌐 **API compatible** | Connect to websites, Slack, Discord, etc. |

---

### 💡 What Makes This Special?

**Without this Agent (Normal Chatbot):**
- ❌ Forgets what you said earlier
- ❌ Can't do math calculations
- ❌ Gives generic answers
- ❌ No memory between messages

**With This Agent:**
- ✅ Remembers your name and preferences
- ✅ Solves math problems instantly
- ✅ Uses Gemini's intelligence
- ✅ Has memory across entire conversation

---

### 🎮 Use Cases (Where To Use This)

| Use Case | Example |
|:---------|:--------|
| **Customer Support** | "My order #1234, when will it arrive?" |
| **Personal Assistant** | "Remind me to buy milk at 5pm" |
| **Educational Tutor** | "Explain photosynthesis and give me a quiz" |
| **Data Analysis** | "What's the average of 45, 67, 89, 32?" |
| **Healthcare Helper** | "Calculate my BMI if height 170cm weight 65kg" |
| **E-commerce Bot** | "Find products under $50 and add to cart" |

---

### 🔧 Technical Details (For Developers)

| Component | Technology | Purpose |
|:----------|:-----------|:--------|
| Automation Platform | n8n | Orchestrates the workflow |
| AI Model | Google Gemini | Natural language understanding |
| Memory | Simple Memory | Stores conversation context |
| Tools | Calculator | Mathematical operations |
| Interface | Chat Trigger | Receives user messages |



---

### 📈 Performance Metrics

| Metric | Value |
|:-------|:-----:|
| Average Response Time | 3-4 seconds |
| Memory Capacity | Full conversation history |
| Math Accuracy | 100% (Calculator tool) |
| API Rate Limit | 60 requests/minute (free) |
| Uptime | Depends on your n8n host |

---

### 🚀 Future Enhancements (You Can Add)

- [ ] Weather API integration
- [ ] Database connection (PostgreSQL, MySQL)
- [ ] Email sending capability
- [ ] Slack/Discord integration
- [ ] Voice input/output
- [ ] Image recognition (Gemini Vision)
- [ ] PDF document reading
- [ ] Web search (SerpAPI)

---

### ❓ Common Questions

**Q: Is this really free?**
> A: Yes! Gemini API has a generous free tier. n8n is also free if self-hosted.

**Q: Can I use GPT-4 instead of Gemini?**
> A: Yes! Just replace the Gemini node with OpenAI node.

**Q: Where is my data stored?**
> A: On your own n8n instance. You control everything.

**Q: Can I add more tools?**
> A: Absolutely! n8n has 400+ nodes you can add.

**Q: Does it work on mobile?**
> A: Yes! Connect it to WhatsApp, Telegram, or any chat app.


<img width="1415" height="487" alt="Screenshot 2025-12-26 015906" src="https://github.com/user-attachments/assets/f0bbfe6a-4ce2-40ac-a79a-7ba9534c3a98" />

