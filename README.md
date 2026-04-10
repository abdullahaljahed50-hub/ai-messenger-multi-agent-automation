🤖 AI Messenger Multi-Agent Automation System

A production-ready AI-powered Messenger chatbot system built with n8n, designed to automate customer interactions using multiple intelligent agents.

🚀 Overview

This project demonstrates a multi-agent architecture where different AI agents handle different types of user inputs:

💬 Conversational queries
🖼️ Image analysis
🔍 Smart responses using memory & tools

The system intelligently routes incoming messages and responds in real-time.

🧠 Key Features
✅ Multi-Agent System
Conversational AI Agent
Image Analyzer Agent
Smart routing based on message type
✅ AI Capabilities
Natural language understanding
Context-aware responses (memory enabled)
Image understanding
✅ Automation
Fully automated message handling
Webhook-based real-time processing
Seamless API communication
✅ Advanced Integrations
OpenAI (Chat + Embeddings)
Vector Database (Pinecone)
Google Search Tool
⚙️ Workflow Architecture
Webhook → Message Extractor → Message Type Router
        → (Image → Image Analyzer Agent)
        → (Text → Conversational Agent)
        → HTTP Request → Response to User
🛠️ Tech Stack
n8n (Workflow Automation)
OpenAI API (LLM + Embeddings)
Pinecone (Vector Database)
HTTP APIs
Messenger Webhook
📸 Workflow Preview

📂 Project Structure
├── workflow.json        # n8n workflow export
├── README.md            # Documentation
├── .env.example         # Environment variables
└── workflow.png         # Screenshot
🔑 Environment Variables

Create a .env file:

OPENAI_API_KEY=your_key
PINECONE_API_KEY=your_key
WEBHOOK_URL=your_webhook
🚀 How to Use
Import workflow.json into n8n
Set environment variables
Connect your Messenger webhook
Activate workflow
Start receiving automated replies
🎯 Use Cases
Customer support automation
Lead qualification
AI chatbot for businesses
Image-based query handling
💼 Why This Project Matters

This project showcases:

Real-world AI automation
Multi-agent system design
API integrations
Production-level workflow thinking


👨‍💻 Author : 
Abdullah Al Jahed
AI Automation Engineer
