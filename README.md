# PDF Q&A Chatbot — RAG-based Document Assistant

This is an end-to-end Retrieval-Augmented Generation (RAG) application that allows users to upload a PDF and ask natural language questions about its contents.
Instead of returning generic answers, the bot extracts relevant context from the uploaded file using semantic search and then generates accurate responses using WatsonX LLM.

---

### Assessment Project Information
This repository contains the **assessment project and solution** for the course:  
**Project: Generative AI Applications with RAG and LangChain – IBM**  

---

## Application Preview

<img width="1818" height="911" alt="image" src="https://github.com/user-attachments/assets/b677a4da-e186-4fa2-8179-cc2cf51d0d7c" />


---

## Tech Stack
| Component | Technology |
|-----------|------------|
| Large Language Model | IBM WatsonX Granite-3-2-8B |
| Vector Store | ChromaDB |
| Embeddings | WatsonXEmbeddings |
| Framework | LangChain |
| UI | Gradio Web App |
| File Loader | PyPDFLoader |
| Language | Python |

---

## Architecture Workflow
PDF → Load & Split → Create Embeddings → Store in ChromaDB → Retrieve Similar Chunks → LLM generates final answer

---

## Features
- Upload any PDF and query information
- Retrieval-Augmented Generation (RAG)
- Similarity search with ChromaDB
- Gradio Web UI
- Clean modular Python implementation

---

### Clone Repository
```bash
git clone https://github.com/sathvik-web/rag-pdf-qa-bot.git
cd rag-pdf-qa-bot
