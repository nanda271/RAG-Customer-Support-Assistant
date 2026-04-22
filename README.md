# RAG-Based Customer Support Assistant

## 📌 Overview
This project implements a **Retrieval-Augmented Generation (RAG)** based Customer Support Assistant for an E-commerce platform. The system retrieves relevant information from a PDF knowledge base and generates accurate, context-aware responses.

---

## 🎯 Objectives
- Process a PDF knowledge base
- Generate embeddings and store in a vector database (ChromaDB)
- Retrieve relevant information using similarity search
- Generate responses using an LLM
- Implement a graph-based workflow using LangGraph
- Support Human-in-the-Loop (HITL) escalation

---

## 🏗️ System Architecture
The system follows a RAG pipeline:

1. PDF → Text Extraction  
2. Chunking → Splitting into smaller sections  
3. Embeddings → Vector representation  
4. Vector Storage → ChromaDB  
5. Retrieval → Fetch relevant chunks  
6. LLM → Generate response  
7. Routing → Decide response or escalation  
8. HITL → Human intervention for complex queries  

---

## ⚙️ Technologies Used
- Python  
- LangChain  
- ChromaDB  
- LangGraph  
- HuggingFace Models  

---

## 📂 Project Structure
- `HLD_Document.pdf` → High-Level Design  
- `LLD_Document.pdf` → Low-Level Design  
- `Technical_Documentation.pdf` → Detailed explanation  
- `knowledge_base.pdf` → Source data for RAG  

---

## 🔄 Workflow (LangGraph)
- **Processing Node:** Handles query processing and retrieval  
- **Output Node:** Returns response or triggers escalation  
- Conditional routing is used for decision-making  

---

## 🤖 Human-in-the-Loop (HITL)
- Low confidence responses trigger escalation  
- Queries are forwarded to a human agent  
- Ensures reliability and accuracy  

---

## 🧪 Sample Queries
- "Where is my order?"  
- "What is the refund policy?"  
- "Can I cancel my order?"  

---

## ⚠️ Challenges & Trade-offs
- Retrieval accuracy vs speed  
- Chunk size vs context quality  
- Cost vs performance  

---

## 🚀 Future Enhancements
- Multi-document support  
- Chat memory integration  
- Web-based UI (Streamlit)  
- Real-time chatbot deployment  

---

## 👨‍💻 Author
nanda kishor
