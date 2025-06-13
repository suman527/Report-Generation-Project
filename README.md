# 📊 Financial Report Generation Agent
 
**Project Title:** AI-Powered Financial Report Analysis using LlamaIndex, Hugging Face, and Groq-hosted LLaMA3-70B  

---

## 🚀 Project Overview

This project implements a custom AI agent pipeline built with the **LlamaIndex** framework, **Hugging Face embeddings**, and the **Groq-hosted LLaMA3-70B-8192** language model. It automates the extraction, comparison, and summarization of top-level financial data (assets, liabilities, margins) for **Apple** and **Tesla** from structured reports using natural language queries.

---

## 🎯 Objectives

- Set up an AI agent pipeline with document understanding and reasoning.
- Extract assets and liabilities data for:
  - Tesla (2019–2023)
  - Apple (2019–2023)
- Create a Vector Index for efficient retrieval.
- Use function-calling LLMs for structured query processing.
- Generate clear, structured financial reports and comparisons.

---

## 🛠️ Tools & Technologies

| Component               | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **LlamaIndex**          | Framework for document indexing, querying, and agent orchestration.         |
| **LlamaCloud**          | Vector store for file-level and chunk-level retrieval.                      |
| **Groq LLM API**        | High-speed inference backend for LLaMA3-70B-8192.                           |
| **Hugging Face**        | Provides embedding models for semantic search.                              |
| **Python Libraries**    | `asyncio`, `transformers`, `os`, `pydantic`, and more.                      |

---

## 🔍 Sample Queries
Compare Apple and Tesla financials (2020–2023)

Summarize Tesla’s key financials in 2023

Gross margin analysis for Apple over 2020–2023

## 📈 Results
Automated retrieval and reasoning over structured documents.

Structured outputs combining tables and textual summaries.

Apple was found to have significantly stronger financial health in 2023 vs Tesla in 2019.

## ✅ Conclusion
This project demonstrates how custom AI agents powered by LLMs and semantic retrieval can be leveraged for high-quality financial analysis. With structured outputs, real-time querying, and contextual accuracy, such agents are valuable tools for decision-making in finance and business intelligence.



