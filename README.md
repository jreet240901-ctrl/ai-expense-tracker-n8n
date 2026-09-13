# 🤖 AI-Powered Expense Management & Automation System

An AI-powered expense tracking workflow built with **n8n, OpenAI, and Google Sheets** that converts natural-language financial transactions into structured expense records automatically.

## 📌 Project Overview

Traditional expense tracking requires users to manually enter and categorize transactions.

This project automates that process.

Users can enter a transaction in natural language, and the AI workflow identifies the **Credit/Debit, Type of Expense, Amount, and Total**, before automatically recording the transaction in Google Sheets.

## ⚙️ How It Works

**User Input → n8n Chat Trigger → AI Agent → OpenAI → Google Sheets**

### 1. User Input

The workflow starts when a user enters a transaction through the chat interface.

### 2. AI Processing

The AI Agent analyzes the user's message and identifies:

* Credit/Debit
* Type of Expense
* Amount
* Total

### 3. Financial Logic

Debit transactions reduce the total amount, while credit transactions increase the total amount.

### 4. Automated Data Storage

The structured transaction is automatically appended to a Google Sheets expense tracker.

## 💡 Example

**User Input:**

> I spent ₹500 on groceries.

**AI Interpretation:**

| Field           | Result                |
| --------------- | --------------------- |
| Credit/Debit    | Debit                 |
| Type of Expense | Groceries             |
| Amount          | ₹500                  |
| Total           | Updated automatically |

The transaction is then recorded in Google Sheets.

## 🛠️ Technology Stack

* **n8n** — Workflow automation
* **OpenAI GPT-4o-mini** — AI processing
* **AI Agent** — Transaction analysis
* **Simple Memory** — Conversation context
* **Google Sheets** — Transaction storage

## ✨ Key Features

* Natural-language expense entry
* AI-powered transaction classification
* Automatic credit/debit identification
* Expense categorization
* Automatic total calculation
* Google Sheets integration
* Conversation memory
* End-to-end workflow automation

## 🎯 Skills Demonstrated

* AI Automation
* n8n Workflow Development
* AI Agent Implementation
* OpenAI Integration
* Google Sheets Automation
* Financial Process Automation
* Prompt Engineering
* Workflow Design

## 📊 Project Impact

This project demonstrates how **AI and workflow automation can simplify repetitive financial data-entry and expense-management tasks**, reducing manual effort and creating a more structured way to track transactions.

## 🖼️ Project Infographic

The project architecture and workflow are illustrated below.

![AI Expense Tracker Infographic](expense-tracker-infographic.png)

## 📂 Project Files

| File                              | Description                    |
| --------------------------------- | ------------------------------ |
| `expense-tracker-n8n.json`        | Importable n8n workflow        |
| `expense-tracker-infographic.png` | Visual overview of the project |

## 🚀 Future Improvements

Potential future enhancements include:

* Monthly expense reports
* Spending dashboards
* Budget alerts
* Expense trend analysis
* Automated financial summaries
* Integration with additional finance and accounting tools

---

### Built With

**n8n • OpenAI • Google Sheets**

**AUTOMATE • ANALYZE • TAKE CONTROL**
