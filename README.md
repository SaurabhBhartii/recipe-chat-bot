# 🍽️ AI Recipe Telegram Chatbot (n8n Workflow)

An AI-powered Recipe Assistant built using **n8n workflow automation** and Telegram Bot integration. The chatbot interacts with users in a natural conversation, recommends different recipe varieties, checks ingredient availability, and provides complete cooking instructions using AI.

This project demonstrates how **AI Agents, LLMs, and workflow automation** can be combined to create an intelligent kitchen assistant without building a traditional backend application.

---

# 🚀 Features

* 🤖 AI-powered Telegram Recipe Assistant
* 💬 Natural language conversation with users
* 🍲 Suggests multiple recipe options based on user preferences
* 🥗 Checks ingredient availability before preparing a dish
* 📝 Provides detailed cooking instructions
* 🔄 Automated multi-step conversational workflow
* ⚡ Real-time responses through Telegram

---

# 🧠 Workflow Architecture

**User → Telegram Bot → n8n Workflow → AI Agent/LLM → Recipe Processing → Response Generation → Telegram User**

### Workflow Steps

1. User sends a message to the Telegram bot.
2. n8n receives the message using a Telegram Trigger.
3. AI Agent analyzes the user's food preference.
4. The workflow suggests multiple recipe varieties.
5. The user selects a recipe.
6. The chatbot checks ingredient availability.
7. AI generates the final recipe instructions.
8. The response is automatically sent back to the user through Telegram.

---

# 🛠️ Tech Stack

## Automation Platform

* n8n Workflow Automation

## AI Integration

* OpenAI / LLM API
* AI Agent Node
* Prompt Engineering

## Communication

* Telegram Bot API

## Data & Storage

* JSON
* External Recipe APIs (optional)
* Database Integration (optional)

---

# 📂 n8n Workflow Components

* Telegram Trigger Node
* AI Agent Node
* LLM Model Node
* Memory Node (Conversation History)
* Conditional Logic Nodes
* HTTP Request Nodes (Recipe APIs)
* Telegram Send Message Node

---

# ⚙️ Setup Instructions

## Prerequisites

* n8n account (Cloud or Self-hosted)
* Telegram Bot Token
* OpenAI API Key

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/AI-Recipe-Telegram-Chatbot.git
```

2. Import the provided `workflow.json` file into n8n.

3. Configure the credentials:

* Telegram Bot API Token
* OpenAI API Key

4. Activate the workflow.

5. Start chatting with your Telegram bot.

---

# 💬 Example Conversation

**User:** I want to eat Paneer.

**Bot:** Great! Here are some Paneer recipes:

* Paneer Butter Masala
* Kadai Paneer
* Shahi Paneer

**User:** Kadai Paneer.

**Bot:** Do you have Paneer, onion, tomato, capsicum, and spices available?

**User:** Yes.

**Bot:** Perfect! Here is your Kadai Paneer recipe with ingredients and step-by-step cooking instructions.

---

# 🔮 Future Enhancements

* Voice-based recipe assistant
* Image-based ingredient recognition
* Personalized meal recommendations
* Grocery list automation
* Multi-agent AI kitchen assistant
* WhatsApp integration

---

# 👨‍💻 Author

**Saurabh Bharti**

AI Automation Engineer | Agentic AI Developer

Passionate about building AI-powered automation workflows using n8n, AI Agents, and LLMs.

---

⭐ If you like this project, consider giving it a star on GitHub!
