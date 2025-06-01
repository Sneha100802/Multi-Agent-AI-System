# 🤖 Multi-Agent AI Chat System (with File Upload & In-Memory Routing)

This project implements a Python-based multi-agent system with a web chat interface using **Gradio**. The system processes user inputs via textbox or file uploads and routes them to specialized agents based on content type and intent.

---

## ✨ Features

- 🔍 **Classifier Agent**: Detects format (JSON, Email) and intent (Invoice, RFQ, Complaint, etc.)
- 🧠 **JSON Agent**: Validates and extracts fields from structured JSON
- ✉️ **Email Agent**: Extracts sender, subject, urgency, and intent
- 📎 **File Upload Support**: Upload `.json` or `.txt` files
- 🗂 **Shared In-Memory Log**: Tracks all classifications and agent outputs
- 💬 **Chat-Style Interface**: Interactive Gradio UI with a Send button

---

## 🧩 Tech Stack

- Python 3.8+
- [Gradio](https://www.gradio.app/)
- Standard libraries: `json`, `re`, `time`, `os`

---

## 🚀 Setup Instructions

1. **Clone or copy this repo**

2. **Install dependencies**  
   In your terminal or notebook:

   ```bash
   pip install gradio
