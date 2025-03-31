# 🚀 Retrieval-Augmented Generation (RAG) Pipeline

## 📌 Overview
This repository implements a **Retrieval-Augmented Generation (RAG) pipeline** using **LangChain** and **OpenAI's GPT-3.5-Turbo**. The system retrieves relevant document chunks using **ChromaDB** and generates answers based on retrieved context to improve accuracy and reduce hallucinations.

## 🔧 Features
- **Web Scraping & Document Loading**: Fetches and processes blog articles.
- **Text Splitting & Tokenization**: Efficiently chunks long documents for retrieval.
- **Embedding & Vector Storage**: Converts text into vector representations using OpenAI embeddings and stores them in ChromaDB.
- **Semantic Search & Retrieval**: Retrieves the most relevant document chunks based on user queries.
- **LLM-Powered Answer Generation**: Uses GPT-3.5-Turbo to generate responses based on retrieved content.

## 📂 Project Structure
```
📦 rag-pipeline
 ┣ 📂 notebooks               
 ┣ 📜 requirements.txt        # Dependencies
 ┣ 📜 README.md              # Project documentation
 ┗ 📂 pics                   # Folder to store pictures 
```

## 🚀 Getting Started
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```


## 🛠 Technologies Used
- **LangChain** for document processing and retrieval
- **OpenAI GPT-3.5-Turbo** for answer generation
- **ChromaDB** for vector-based document retrieval
- **BeautifulSoup (bs4)** for web scraping
- **tiktoken** for token counting

## 📚 Useful Resources
- [LangChain Documentation](https://docs.smith.langchain.com/)
- [Token Counting with `tiktoken`](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_count_tokens_with_tiktoken.ipynb)
- [Understanding Tokens in OpenAI](https://help.openai.com/en/articles/4936856-what-are-tokens-and-ho)
- [OpenAI Embeddings in LangChain](https://python.langchain.com/docs/integrations/text_embedding/openai/)
- [OpenAI Embeddings FAQ](https://platform.openai.com/docs/guides/embeddings#faq)
- [Document Loaders in LangChain](https://python.langchain.com/docs/integrations/document_loaders/)
- [Vector Stores in LangChain](https://python.langchain.com/docs/integrations/vectorstores/)


