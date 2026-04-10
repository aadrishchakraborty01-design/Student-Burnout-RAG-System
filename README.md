# 🚀 Student Burnout Early Detection using RAG

## 📖 Overview

This project explores the design of a Retrieval-Augmented Generation (RAG) based system to detect early signs of student burnout using behavioral and academic indicators.

---

## 🧠 System Architecture

 

Flowchart_1.drawio.png

   

---

## 🔍 RAG Pipeline

 

Flowchart_2.drawio.png

   

---

## 🎯 Objective

The goal is to shift from reactive intervention to proactive awareness by identifying early warning signals such as:

* Attendance decline
* Reduced engagement
* Assignment delays
* Quiz participation patterns

---

## ⚙️ System Flow

Student Data → Processing → Vector Database → RAG Pipeline → Insight Generation → Mentor Output

---

## 🧩 Key Components

* **Data Processing Layer** – Handles raw student behavioral data
* **Embedding Generation** – Converts data into vector representations
* **Vector Database** – Stores embeddings for retrieval
* **RAG Pipeline** – Combines retrieval with LLM reasoning
* **n8n Workflow** – Automates the pipeline
* **Insight Engine** – Generates mentor-readable summaries

---

## 📊 Sample Output

```
Student shows a consistent drop in attendance along with delayed submissions 
and reduced quiz participation, indicating early signs of disengagement.
```

---

## 🛠️ Tech Stack

* RAG Architecture
* Vector Database
* n8n (Workflow Automation)
* LLM APIs

---

## 📈 Scalability

* Currently tested on single student
* Designed for multi-student systems and institutional use

---

## 🔮 Future Scope

* Multi-student clustering
* Dashboard integration (Tableau / Web App)
* Real-time alert system
* LMS integration
