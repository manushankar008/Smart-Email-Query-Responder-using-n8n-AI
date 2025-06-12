# Smart Email Query Responder using n8n & AI

This is a real-world automation project I built during my internship, designed to handle incoming emails related to company policies and respond intelligently using AI and vector-based search.

## 📌 Features
- Automatically triggers when an email is received
- Filters non-work-related emails
- Logs email subject & body into Excel for team reference
- Uses Superbse vector DB to retrieve relevant policy documents
- Generates appropriate responses using an AI chatbot
- Sends personalized reply to the sender

## 🧠 Use Case
Helps organizations save time by automating responses to common employee queries related to company policies.

## ⚙️ Tech Stack
- **n8n** – workflow automation
- **Gmail API** – email trigger and response
- **Superbse** – vector search for document retrieval
- **OpenAI (or other LLM)** – generates response based on policy info
- **Excel (Google Sheets)** – logging incoming queries

## 🔄 Workflow Overview
1. Email received ➡️
2. Check if it's work-related ➡️
3. Log subject & body into Excel ➡️
4. Use vector search on Superbse to find matching policies ➡️
5. Generate response with AI ➡️
6. Send reply via Gmail

## 📸 Screenshots
![Screenshot 2025-06-12 172007](https://github.com/user-attachments/assets/1d3dbebc-f9ba-4c1e-8660-22284257f696)
![Screenshot 2025-06-12 172030](https://github.com/user-attachments/assets/a35dc459-14e9-4b25-b3ae-0db1a72f6a31)


## 📁 Files
- `workflow.json` – exported n8n workflow (optional)
- `sample-email.csv` – dummy input (if you want to include)

## 🚀 Getting Started
To test or deploy this:
- Set up Gmail and n8n credentials
- Upload policy docs to Superbse
- Import workflow into n8n
- Run and monitor workflows

## 👨‍💻 Author
Manu Shankar
