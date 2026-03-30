# VCFiananceAnalyzer
VCFiananceAnalyzer   Automated Financial Intelligence System that extracts, analyzes, and generates actionable insights from transaction PDFs using Python, FastAPI, and MongoDB.

# 💰 Financial Transaction Analyzer & Intelligence System

This project is a full-stack financial analysis system that processes transaction PDFs (Paytm/UPI statements), extracts structured data, and generates actionable financial insights.

## 🚀 Features

### 🔍 Data Extraction
- Parses transaction PDFs using `pdfplumber`
- Extracts:
  - Sender/Receiver
  - Amount
  - Transaction Type (Sent/Received)
  - Tags/Categories

### 📊 Data Analysis
- Tag-wise spending and income breakdown
- Person-wise financial flow (Received, Sent, Net)
- Top spending sources detection
- Category percentage distribution

### 🧠 Financial Intelligence Engine
- Calculates savings rate and financial health
- Detects:
  - High transaction frequency
  - Micro-spending behavior
  - Money leakage through transfers
- Generates personalized financial insights and warnings

### 📉 Advanced Insights
- Spending vs Income comparison
- Top 5 financial drains
- Budget-based recommendations
- Financial risk detection

### 🌐 Full Stack System
- **Backend:** FastAPI (REST API for processing)
- **Frontend:** HTML + JavaScript (file upload interface)
- **Database:** MongoDB (for storing transaction history)

---

## 🏗️ Tech Stack

- Python
- FastAPI
- Pandas
- pdfplumber
- MongoDB
- HTML / JavaScript

---

## ⚙️ How It Works

1. User uploads transaction PDF
2. Backend extracts structured transaction data
3. Analyzer processes data using Pandas
4. Insight engine generates financial recommendations
5. Results displayed on frontend

---

## 📊 Example Output

- Tag-wise spending analysis
- Person-wise money flow
- Financial health score
- Actionable financial advice

---

## 🎯 Key Highlights

- Converts unstructured PDF data into structured insights
- Combines data engineering + financial analytics
- Focuses on behavioral finance patterns, not just numbers
- Designed as a scalable system for real-world financial tracking

---

## 🚧 Future Improvements

- Monthly trend analysis with visualization
- AI-based financial prediction
- User authentication system
- Interactive dashboard (React)
- Automated budgeting system

---

## 📌 Use Case

This system helps individuals:
- Track spending behavior
- Identify financial leaks
- Improve savings discipline
- Make better financial decisions

---

## ⚠️ Note

This is an educational project focused on financial data analysis and system design.

---

## 👨‍💻 Author

Dhanush V C
