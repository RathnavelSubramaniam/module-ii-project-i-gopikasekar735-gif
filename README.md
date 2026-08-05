# MedRAG - Medical Question Answering System

## 📖 About the Project

This project is a **Retrieval-Augmented Generation (RAG)** based medical question-answering system. It uses the **Merck Manual** as the knowledge source and generates accurate, evidence-based answers using **Llama-2**, **ChromaDB**, and **HuggingFace Embeddings**.

---

## Objective

* Build a medical question-answering system.
* Retrieve relevant information from medical documents.
* Generate accurate and reliable answers.
* Reduce hallucinations using RAG.

---

## Technologies Used

* Python
* LangChain
* Llama-2
* ChromaDB
* HuggingFace Embeddings
* PyMuPDF
* Google Colab

---

## Project Workflow

1. Load the medical PDF.
2. Extract and split the text into chunks.
3. Create embeddings using HuggingFace.
4. Store embeddings in ChromaDB.
5. Retrieve relevant information for the user's question.
6. Generate an answer using Llama-2.
7. Evaluate the response using relevance and groundedness scores.

---

## Features

* Medical question answering
* Evidence-based responses
* Fast document retrieval
* Reduced hallucinations
* High relevance and groundedness

---

## Results

* High relevance scores (4–5/5)
* High groundedness scores (4–5/5)
* Reliable and accurate medical responses

---

##  Future Improvements

* Add hybrid search (BM25 + Vector Search)
* Improve retrieval accuracy
* Deploy as a web application
* Add more medical datasets

---


