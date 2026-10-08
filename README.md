# 🛡️ AI Financial Fraud Detection

An AI-powered financial fraud detection project that generates structured conversational training data from financial transaction records.

## 📌 Project Overview

Financial fraud detection is an important application of machine learning and artificial intelligence in the fintech industry.

This project takes financial transaction information and converts it into structured conversational examples that can be used for AI/LLM-based fraud detection and analysis.

The generated dataset contains **1,000 training conversations**.

## 🎯 Objectives

- Generate structured fraud-detection training data
- Identify potentially fraudulent transactions
- Handle transaction-level financial information
- Create conversational examples for AI systems
- Prepare data for future LLM/AI applications

## 🧠 Approach

The project follows this workflow:

Financial Transaction Data  
↓  
Data Processing  
↓  
Dataset Balancing  
↓  
Conversation Generation  
↓  
Fraud Risk Classification  
↓  
JSONL Training Dataset

## 📊 Dataset Features

The transaction examples include information such as:

- Transaction type
- Transaction amount
- Sender balance before transaction
- Sender balance after transaction
- Recipient balance before transaction
- Recipient balance after transaction
- Fraud classification

## 💬 Example

Example transaction information:

```text
Transaction Type: TRANSFER
Amount: $10,000
Sender Balance Before: $12,000
Sender Balance After: $2,000
Recipient Balance Before: $5,000
Recipient Balance After: $15,000
