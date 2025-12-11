
# 📦 Product Review RAG Pipeline  
### ChromaDB • LangChain LCEL • KaggleHub • SentenceTransformers

## 🚀 Run in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_LINK)


This project builds a **Retrieval-Augmented Generation (RAG)** pipeline over Amazon product reviews.  
It downloads the dataset automatically using **KaggleHub**, embeds review text using **SentenceTransformers**, stores embeddings in **ChromaDB**, and performs retrieval-based question answering using **LangChain LCEL**.

---

## 🚀 Features
- Automatic dataset download (no manual Kaggle token upload)
- Cleans + chunks review text for better retrieval
- Embeddings generated using `all-MiniLM-L6-v2`
- Vector store persisted using **ChromaDB**
- LCEL-based RAG chain (modern LangChain approach)
- Supports deep insights:
  - Trending complaints  
  - Positive themes  
  - Sentiment differences  
  - Clustered review themes  

---

## 📥 Dataset
Uses the **Amazon Fine Food Reviews** dataset:

