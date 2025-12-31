# Telegram-Bot---AI-Agent-Workflow-Project


## 🤖 AI Agent–Powered Telegram Bot

This project is an **AI-powered Telegram Bot** built using an **AI Agent workflow**.
It receives user messages from Telegram, processes them using an AI agent powered by **Google Gemini Chat Model**, maintains conversation context using **memory**, and sends intelligent replies back to the user.

---

## 🔧 Tech Stack

* **Telegram Bot API**
* **AI Agent Workflow**
* **Google Gemini Chat Model**
* **Memory Module (Context Retention)**
* **Workflow Automation Platform** (trigger → agent → response)

---

## ✨ Features

* ✅ Real-time Telegram message handling
* ✅ AI Agent–based intelligent responses
* ✅ Context-aware conversations using memory
* ✅ Modular and scalable workflow design
* ✅ Easy to extend with tools and APIs

---

## 🧠 Workflow Architecture

1. **Telegram Trigger**
   Listens for incoming messages from users.

2. **AI Agent**

   * Processes user queries
   * Uses Google Gemini Chat Model
   * Maintains conversation memory

3. **Send Message Action**
   Sends AI-generated responses back to the user on Telegram.

---

## ⚙️ Working Steps (How It Works)

1. A user sends a message to the Telegram Bot.
2. The **Telegram Trigger** captures the message.
3. The message is forwarded to the **AI Agent**.
4. The AI Agent:

   * Understands the query using **Google Gemini**
   * Retrieves relevant context from **memory**
   * Generates a response
5. The response is sent back to the user via **Telegram Send Message**.
6. The conversation context is stored for future interactions.

---

## 🚀 Setup Steps

### 1️⃣ Create a Telegram Bot

* Open **@BotFather** on Telegram
* Create a new bot and copy the **Bot Token**

---

### 2️⃣ Configure the Workflow

* Add **Telegram Trigger**
* Connect your Telegram Bot Token
* Set trigger type to `message`

---

### 3️⃣ Add AI Agent

* Configure **Google Gemini Chat Model**
* Connect the model to the AI Agent
* Enable **Memory Module** for contextual replies

---

### 4️⃣ Send Message Action

* Add Telegram **Send Message** node
* Map the AI Agent response to the message field

---

### 5️⃣ Test the Bot

* Send messages from Telegram
* Verify intelligent and context-aware responses

---

## 📌 Future Improvements

* 🔹 Add external tools (APIs, databases)
* 🔹 Improve memory handling
* 🔹 Add command-based responses
* 🔹 Deploy multi-language support

---

## 👨‍💻 Author

**Om Bankar**
AI & Machine Learning Enthusiast

