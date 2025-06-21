# 🐬 Dolphin AI Chat Server on Google Colab

This project lets you host your own **Dolphin AI (Mistral finetuned)** chatbot server for free on **Google Colab**.

## Features
- 🧠 Conversational AI (Dolphin 2.5 - Mistral)
- 🐍 Flask REST API
- 🌍 Public URL via ngrok
- 📱 Android HTTP Shortcut integration

## 🚀 Quick Start

1. Open `Dolphin_AI_Colab.ipynb` in Google Colab
2. Run all cells (setup takes 3–5 minutes)
3. Use the generated public `/chat` endpoint from ngrok

## 📱 Android Shortcut Setup

- Method: POST  
- URL: `https://abc123.ngrok.io/chat`  
- Header: `Content-Type: application/json`  
- Body:
```json
{
  "message": "Remind me to journal at 8 PM"
}
