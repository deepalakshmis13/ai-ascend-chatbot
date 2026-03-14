# 🤖 Multilingual Government Scheme Chatbot
## 🎥 Demo Video

You can watch the project demo below:

[Watch Demo Video]

### AI Ascend 2026 Hackathon Project

## 📌 Problem Statement

Many citizens struggle to access **government schemes and public service information** due to:

* Language barriers
* Complex government portals
* Lack of awareness about available schemes

This often prevents people from benefiting from important government programs.

---

## 💡 Proposed Solution

We developed a **Multilingual AI Chatbot** that helps users easily understand government schemes in **Tamil and English**.

The chatbot allows users to:

* Ask questions in **natural language**
* Use **text or voice input**
* Receive **simple explanations of government schemes**

The goal is to make **government information accessible, simple, and inclusive** for everyone.

---

## ⚙️ Tech Stack (AWS)

* **Amazon EC2** – Hosts the chatbot backend
* **Amazon S3** – Stores scheme datasets and resources
* **Amazon RDS** – Manages the chatbot database
* **Telegram Bot (BotFather)** – Deployment platform for chatbot interface

---

## 🏗️ System Architecture

```
User
   ↓
Telegram Bot
   ↓
Backend (EC2)
   ↓
Database (RDS)
   ↓
Scheme Data (S3)
   ↓
Response to User
```

The chatbot processes user queries, retrieves relevant scheme information from the database and dataset, and responds in the user's preferred language.

---

## ✨ Key Features

🌐 **Multilingual Support**
Supports both **Tamil and English** queries.

🎤 **Voice + Text Input**
Users can interact with the chatbot using **voice messages or text**.

🤖 **Natural Language Understanding**
The bot understands **natural language questions** and returns relevant scheme information.

📄 **Government Scheme Information**
Provides simplified explanations of schemes and benefits.

⚡ **Cloud-based Deployment**
Built using **AWS cloud infrastructure for reliability and scalability**.

---

## 👤 Example Use Case

A user asks in Tamil:

```
"எனக்கு அரசு உதவி திட்டங்கள் என்ன கிடைக்கும்?"
```

The chatbot processes the request and responds with relevant government schemes and details in **Tamil or English**.

---

## 📂 Project Structure

```
/frontend      → Telegram bot interface
/backend       → Backend logic and API handling
/docs          → Documentation and project details
```

---

## 🚀 Future Enhancements

* 📱 **WhatsApp Chatbot Integration** for wider accessibility
* 🎙️ **Advanced Voice Interaction**
* 📍 **Location-based Scheme Recommendations**
* 📊 **Analytics Dashboard for Government Insights**

---

## 👥 Team

* **S. Deepalakshmi**
* **B. Devadharshani**
* **B. Ambigai**
* **A. Binita**

Panimalar Engineering College

---

## ☁️ Why AWS?

AWS provides:

* **Reliable cloud infrastructure**
* **Scalable computing resources**
* **Secure data storage**
* Easy deployment for **AI-driven applications**

Using **EC2, S3, and RDS**, we built a **simple yet scalable cloud architecture** suitable for prototyping real-world solutions.

---

## 🛠️ Project Status

✅ **Prototype Completed during AI Ascend 2026 Hackathon**

Current capabilities:

* Telegram bot deployment
* Tamil & English **text input support**
* Tamil & English **voice input support**
* Natural language understanding
* Cloud backend on AWS

Future versions will expand the chatbot into a **WhatsApp-based public service assistant**.
