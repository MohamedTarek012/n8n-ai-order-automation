# 🤖 AI-Powered Order Aggregation & Reporting Automation

## 🏢 Client Project – Taze Store

This project is a **real-world automation solution** developed for Taze Store based on direct business requirements from management.

The main objective was to solve a critical operational problem:
> Aggregating and consolidating order items across multiple customer orders by product type to support daily kitchen operations.

---

## 🚀 Overview

The system automates the full workflow of:
- Extracting orders from Shopify
- Aggregating items by product/category
- Generating structured operational reports
- Delivering insights automatically
-  Bonus Producing AI-generated instructions for execution teams

---

## 🎯 Problem Solved

Before automation:
- Orders were scattered across multiple entries  
- Manual aggregation was time-consuming and error-prone  
- Kitchen teams lacked clear, structured instructions  

After automation:
- Orders are **grouped by product (Order Aggregation)**  
- Clear reports generated for each operational role  
Decision-making is faster and easier, and manual labor is significantly reduced.

## ⚙️ Key Features

- 🔗 Integration with Shopify (REST & GraphQL APIs)
- 🧮 Order aggregation by product across multiple orders
- ⚡ Custom data transformation using JavaScript in n8n
- 📊 Automated report generation (Chef / Butcher / Orders)
- 📁 Google Sheets & Google Drive integration
- ⏰ Scheduled workflows (cron-based automation)
- 📧 Automated email delivery with reports
- 🧠 AI Agent (LLM) generates actionable instructions in Arabic

---

## 🧠 AI Component 

An AI Agent analyzes aggregated order data and generates:
- Daily preparation instructions
- Operational insights for kitchen teams
- Structured, human-readable output in Arabic

---

## 🛠 Tech Stack

- n8n (Workflow Automation)
- Shopify API (REST & GraphQL)
- JavaScript (Data Transformation)
- Google Sheets API
- Google Drive API
- Email Automation
- LLM (Google Gemini / OpenAI) 

---

## 🔐 Security Notice

All credentials (API keys, tokens, OAuth secrets) have been removed for security reasons.

To run this workflow:
1. Import the JSON file into n8n
2. Configure your own credentials:
   - Shopify API
   - Google Services
   - Email account

---

## ▶️ How to Use

1. Import the workflow into n8n
2. Connect required APIs and credentials
3. Run manually or via scheduler
4. Monitor generated reports and outputs

---

## 📈 Impact

- Reduced manual order processing effort significantly  
- Improved accuracy in order aggregation  
- Enabled data-driven decision making  
- Delivered a production-ready automation system used in daily operations  

---

## 📌 Notes

This project reflects a real business use case and demonstrates:
- Data Engineering concepts (ETL, pipelines, transformation)
- Workflow automation
- API integration
- AI-powered decision support systems

---

## 👤 Author

Developed by Mohamed Kosba
