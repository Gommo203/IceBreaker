# ❄ IceBreaker App

**LangChain-based AI Agent for Personalized Conversation Starters**  

---

## 📌 Project Overview

The IceBreaker App is an AI-powered tool designed to generate personalized conversation starters based on publicly available information from a person’s online profiles.  

By leveraging **LangChain**, the app searches for relevant profiles, extracts data, and uses LLM reasoning to produce natural, engaging, and context-aware icebreakers.

This project provided hands-on experience with **AI agent development**, **prompt engineering**, and **external API integration**.

---

## ✨ Features

- **Automated Profile Search**  
  Finds likely LinkedIn and/or Twitter profiles based on a given name.

- **Data Extraction**  
  Gathers public profile details such as bio, experience, skills, and interests.

- **AI-Generated Icebreakers**  
  Uses LangChain to produce tailored conversation starters that sound natural and relevant.

- **Tool-Orchestrated Reasoning**  
  Employs ReAct prompting and LangChain tools for multi-step decision-making.

- **Optional Web Interface**  
  Flask-based frontend for quick input and instant results.

---

## 🛠 Technologies Used

| Area                  | Tools & Technologies                                  |
|-----------------------|--------------------------------------------------------|
| AI Framework          | LangChain, LangGraph                                   |
| LLM                   | OpenAI GPT models                                      |
| Prompting Techniques  | ReAct, Few-Shot, Chain-of-Thought, Output Parsing      |
| Data Retrieval        | SerpAPI / Tavily API, Google Search API                |
| Backend & API         | Python, Flask                                          |
| Data Storage          | Vector Stores (FAISS / Pinecone)                       |
| Others                | Requests, BeautifulSoup for scraping                   |

---
