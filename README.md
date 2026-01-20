# BankBot – AI Chatbot for Banking FAQs

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![AI](https://img.shields.io/badge/AI-NLP-green)
![LLM](https://img.shields.io/badge/LLM-Transformer--Based-orange)
![Status](https://img.shields.io/badge/Status-Active-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## Project Description

BankBot AI is an AI-powered chatbot system designed to handle frequently asked banking questions efficiently.
The system uses Natural Language Processing (NLP) and a Large Language Model (LLM) to understand user queries and provide accurate, human-like responses through a simple web interface.

The goal of this project is to automate repetitive banking queries, reduce human workload, and provide 24×7 customer support.

---
## Problem Statement

Banks receive a large number of repetitive customer queries related to:
Account services
ATM / card issues

Loans and interest rates

Banking procedures

Handling these manually leads to:

Long waiting times

Increased operational cost

Limited availability
This project addresses these challenges by providing an intelligent chatbot solution.

## Features

AI-powered conversational chatbot
Handles common banking FAQs
User-friendly web interface using Streamlit
Context-aware responses using LLM
Secure and modular project structure

Scalable for multiple users
---

## Techniques Used
Programming Language: Python
Frontend: Streamlit
AI / NLP: LangChain, Transformer-based LLM (via Groq API)
Database: SQLite
Other Libraries: bcrypt, plotly, python-dotenv

### Natural Language Processing (NLP)

* Text preprocessing and normalization
* User intent understanding
* Context preservation across queries

### Prompt Engineering

* Domain-specific prompt design for banking use cases
* Controlled and safe response generation
* Prompt templates for consistent outputs

### LLM-based Text Generation

* Transformer-based text generation
* Instruction-following conversational AI
* Scalable and model-agnostic design

---

## Tech Stack

### Programming Language

* **Python**

### Libraries / Frameworks

* `transformers`
* `torch`
* `nltk`
* `sentencepiece`
* `streamlit` / `flask` (for UI or API layer)
* `pandas`
* `numpy`

### AI / ML Technologies

* Natural Language Processing (NLP)
* Large Language Models (LLMs)
* Transformer architecture
* Prompt Engineering


## System Architecture (High Level)
User → Streamlit UI → NLP Processing → LLM → Response → UI

Use Cases

Banking customer support automation

FAQ handling system

Educational demonstration of AI chatbots

NLP and LLM-based application showcase

## Security Considerations

Passwords are securely hashed

Environment variables are protected

Sensitive files are excluded from version control

 ## Future Enhancements

Multi-language support

Voice-based interaction

Integration with real banking APIs

User feedback and learning system

Admin analytics dashboard
