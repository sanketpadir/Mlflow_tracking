# GenAI Health Data Insight System

An end-to-end SQL-driven Generative AI analytics pipeline that enables users to query structured healthcare datasets using natural language and receive context-aware insights and recommendations.

---

# Project Overview

This project was developed to solve the challenge of analyzing complex healthcare datasets without manually writing SQL queries or directly feeding raw tabular data into Large Language Models (LLMs). The system dynamically generates SQL queries, retrieves relevant data, summarizes it, and produces intelligent natural language insights using Generative AI.

The solution supports multi-table querying, temporary joins, evaluation metrics, and secure data handling for healthcare analytics.

---

# Key Features

- Natural language to SQL query generation  
- Dynamic schema extraction  
- Automated SQL sanitization and validation  
- Multi-table temporary joins  
- Context-aware AI-generated insights  
- Structured data summarization before LLM inference  
- Evaluation metrics for generated responses  
- Interactive Streamlit user interface  
- Real-time analytics pipeline  

---

# Tech Stack

## Languages

- Python  
- SQL  

## Libraries & Frameworks

- Pandas  
- Streamlit  
- SQLite  
- LangChain  
- OpenAI API  

## AI & NLP

- Generative AI  
- Prompt Engineering  
- Natural Language to SQL  
- Context-aware Response Generation  

## Evaluation

- Faithfulness Evaluation  
- Relevance Accuracy  
- Context Accuracy  

---

# System Architecture

1. User uploads healthcare datasets  
2. Datasets loaded into in-memory SQLite database  
3. Schema extracted dynamically  
4. User asks question in natural language  
5. LLM generates SQL query  
6. SQL query sanitized and validated  
7. Query executed on structured data  
8. Retrieved data summarized  
9. LLM generates final insights/recommendations  
10. Evaluation metrics calculated  

---

# Datasets Used

## Dataset 1

Contains:

- Demographics  
- Hemoglobin  
- BMI  
- Genetic coefficients  
- Lifestyle factors  
- Stress levels  
- Medical disorders  

## Dataset 2

Contains:

- Patient activity data  
- Daily step counts  
- Physical activity history  

---

# Core Functionalities

## Dynamic SQL Generation

The system converts user questions into optimized SQL queries dynamically.

## Secure Query Processing

Implemented SQL sanitization and automatic column qualification to improve reliability and prevent invalid queries.

## AI-Powered Insight Generation

Generated contextual healthcare insights and recommendations using LLMs.

## Evaluation Pipeline

Measured:

- Faithfulness  
- Relevance  
- Context utilization  

---

# User Interface

The Streamlit application allows users to:

- Upload datasets  
- Ask natural language questions  
- View generated SQL queries  
- Preview retrieved data  
- Analyze AI-generated insights  
- Monitor evaluation scores  

---

# Project Outcomes

- Successfully built an end-to-end GenAI analytics system  
- Enabled real-time healthcare insight generation  
- Supported complex multi-table analytical queries  
- Improved accessibility of structured healthcare analytics using AI  

---

# Future Enhancements

- Fine-tuned domain-specific healthcare LLM  
- Role-based authentication  
- Cloud deployment with Docker and AWS  
- Vector database integration  
- Conversational memory support  

---

# Installation

```bash
git clone <your_repo_url>

cd project_folder

pip install -r requirements.txt
```

# Run the Application

```bash
streamlit run app.py
```

---

# Author

**Sanket Padir**  
Data Scientist | ML Engineer | Generative AI Developer
