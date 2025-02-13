# **DeepSeek-r1 RAG Pipeline**  

This repository features a **Retrieval-Augmented Generation (RAG) pipeline** powered by **DeepSeek-r1:1.5b**, designed for efficient document-based retrieval and AI-driven response generation.  

## **Overview**  
This pipeline extracts, processes, and retrieves relevant information from documents, enhancing AI-generated responses with factual accuracy. It follows these steps:  

- **📄 Document Ingestion** – Extracts text from PDFs.  
- **🛠 Preprocessing & Chunking** – Cleans and segments text for efficient retrieval.  
- **🔍 Embedding Generation** – Converts text into vector embeddings.  
- **📂 Vector Storage & Retrieval** – Uses FAISS for fast semantic search.  
- **🤖 Augmented Response Generation** – DeepSeek generates responses using retrieved context.  

## **Key Features**  
- **Semantic Search** – Retrieves the most relevant information based on queries.  
- **Efficient Retrieval** – Uses FAISS for high-speed vector indexing.  
- **Context-Aware Responses** – Enhances AI-generated answers with real data.  
- **Scalable & Modular** – Easily adaptable for different use cases.  

## **Use Cases**  
- **Knowledge Management** – Quickly access structured information.  
- **Research & Analysis** – Retrieve key insights from large documents.  
- **AI Chatbots** – Power intelligent assistants with document-backed knowledge.  

## **Future Enhancements**  
- Support for **TXT, DOCX, and other formats**.  
- Integration with **web-based search**.  
- Fine-tuning **DeepSeek for specialized domains**.  

Contributions and feedback are welcome! 🚀
