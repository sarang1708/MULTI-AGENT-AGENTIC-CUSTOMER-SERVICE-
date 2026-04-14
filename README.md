# 🤖 Agentic AI Customer Support Bot

## 📌 Project Overview
This project is an **Autonomous Agentic AI Customer Support System** built using machine learning and real-world datasets.  
It simulates a real e-commerce support assistant capable of understanding queries, retrieving relevant information, tracking orders, and escalating issues when required.

Unlike basic chatbots, this system follows an **Agentic AI architecture** where multiple intelligent components collaborate to solve user queries.

---

## 🚀 Key Features

- ✅ Intent Classification using TF-IDF + Logistic Regression  
- ✅ Order Tracking using real dataset (Tool Agent)  
- ✅ Smart Search (by Order ID, Name, Product, City)  
- ✅ Retrieval-Based Response Generation  
- ✅ Confidence-Based Escalation System  
- ✅ Ticket Generation for unresolved queries  
- ✅ Clean and structured terminal UI  

---

## 🧠 Agentic AI Architecture

This project implements multiple agents working together:

| Agent | Function |
|------|--------|
| 🧠 Intent Agent | Detects user intent (billing, refund, etc.) |
| 🔍 Retrieval Agent | Finds relevant records from dataset |
| 🛠 Tool Agent | Handles order tracking and structured queries |
| ⚠️ Escalation Agent | Creates ticket when confidence is low |
| 💬 Response Agent | Generates formatted responses |

---

## 📂 Project Structure
agenticai/
│
├── agent_ai.py # Main chatbot (entry point)
├── train_model.py # Model training script
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
│
├── data/
│ ├── customer_support_tickets.csv
│ └── orders.csv
│
├── config.json
├── knowledge.json
├── feedback.json
├── escalations.json
│
├── requirements.txt
└── README.mdagenticai/
│
├── agent_ai.py # Main chatbot (entry point)
├── train_model.py # Model training script
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
│
├── data/
│ ├── customer_support_tickets.csv
│ └── orders.csv
│
├── config.json
├── knowledge.json
├── feedback.json
├── escalations.json
│
├── requirements.txt
└── README.md                                                                                          ---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/agentic-ai.git
cd agentic-ai                                                                                                       pip install -r requirements.txt                                                                                               python agent_ai.py                                                                             💡 Example Usage
🔹 Input:

refund status ORD1062
🔹 Output:

Bot: ✅ Order ID detected!

📦 Order Details:

👤 Customer: Sneha Kapoor
📌 Product: Running Shoes (Fashion)
💳 Payment: Net Banking
💰 Amount: ₹18091

🚚 Status: Refund Initiated
📅 Delivery: Not Available
💸 Refund: Not Applicable
📍 City: Mumbai
🔹 Input:

arjun mehta
🔹 Output:

Bot: 🔍 Matching order found!

📦 Order Found:

👤 Customer: Arjun Mehta
📌 Product: Mobile Phone (Electronics)
...
📊 Use Cases
Customer Support Automation

E-commerce Order Tracking

AI Helpdesk Systems

Query Classification & Routing

Support Ticket Automation

📈 Future Enhancements
🌐 Web-based UI (Streamlit / React)

☁️ Cloud Deployment (AWS / GCP)

📊 Power BI Dashboard Integration

🎙️ Voice Assistant Integration

🤖 LLM Integration (Hybrid AI system)

🎯 Why This Project Matters
This project demonstrates:

Real-world application of Agentic AI systems

Integration of ML + Data + Automation

Ability to build scalable, production-like AI solutions

It is highly relevant for roles like:

Data Analyst

AI/ML Engineer

Backend Developer

Product Engineer

👨‍💻 Author
SARANG RAMPAL
B.Tech CSE | AI & Data Enthusiast

🤝 Contributing
Contributions are welcome!
Feel free to fork the repository and submit pull requests


