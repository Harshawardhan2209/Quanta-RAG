<p align="center">
  <img src="https://github.com/user-attachments/assets/cb3b7cf9-52ea-4359-be0f-b70632ac6125" alt="Logo College" width="250">
</p>

# Quanta

**A classified, agent-aware RAG system for secure intelligence retrieval.**  
Engineered for high-stakes operations where information must be precise, permissioned, and explainable.
git push origin main
---



📄 **Problem Statement:** [text](problemStatement.txt)  


---

## 🔎 Project Overview

Quanta simulates a real-world classified intelligence assistant, designed to retrieve and justify sensitive information for agents operating at different clearance levels. Built on Retrieval-Augmented Generation (RAG), the system blends semantic search, rule-based logic, and dynamic prompt construction.

> “The right intel, to the right agent, at the right time — or not at all.”

---



---

## 🧱 Key Features

- 🔐 **Agent-Level Access Control**  
  Role-aware security — only the right eyes see the right data.

- 🧠 **RAG-Powered Retrieval**  
  Vector similarity + graph traversal = deep, contextual understanding.

- 📜 **Rule-Based Justification Engine**  
  Tailors every response based on agent level and query type.

- 🗂️ **Modular Chunking Engine**  
  Custom document chunking ensures high-precision retrieval.

- 🌒 **Response Mode Switching**  
  From cryptic whispers to strategic briefings — context shapes delivery.

---

## 🧪 Sample Use Case

```plaintext
Agent Level: 3  
Query: How do I evade thermal surveillance while extracting a compromised asset?

Response:
Eyes open, Phantom. 🧠 Strategy Brief:  
Use thermal decoys, mask signatures with industrial heat zones, and relocate through Phase-Shift Safehouses.

---

## 📂 Tech Stack

- `Streamlit` – Frontend for query submission  
- `sentence-transformers` – Embedding engine  
- `scikit-learn` – Similarity scoring  
- `LangChain`-ready architecture (extensible)  
- `python-docx`, `json`, `re` – Document processing

---

## 📦 Project Structure

```
project_quanta/
├── app.py                      # Streamlit frontend
├── data/                       # Source DOCX files
├── chunks/                     # Pre-processed semantic chunks
├── retrieval/                  # Vector + graph retrieval logic
├── rules/                      # Rule-matching response engine
├── utils/                      # Access control, prompt utils
├── scripts/                    # Chunk generation script
└── docs/                       # Technical explanation (optional)
```

---

## 🧠 Ideal For

- RAG prototyping with explainability
- Secure document question-answering
- LLM sandboxing with role-based control
- Intelligence or law-enforcement training sims

---

## ✅ Getting Started

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Generate chunks:
```bash
python -m scripts.generate_chunks
```

3. Run the app:
```bash
streamlit run app.py --server.fileWatcherType none
```

---

## 🧠 Built With Purpose

This system was designed for [Project QUANTA], simulating covert data access inside a high-risk, zero-trust environment.  
Responses are customized, cryptic, or codified depending on the agent's clearance level and context.

> 🫥 Trust no one. Assume nothing. Adapt or be eliminated.
