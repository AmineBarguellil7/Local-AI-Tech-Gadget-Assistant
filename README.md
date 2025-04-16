# Local-AI-Tech-Gadget-Assistant

This project involves building a local AI assistant that answers questions about tech gadgets using Python, LangChain, Ollama, and a Retrieval-Augmented Generation (RAG) approach. 
It loads a dataset of synthetic reviews, embeds them into a local Chroma vector database, and retrieves the most relevant ones based on user queries. 
The retrieved context is then passed to a local LLaMA 3 model using LangChain to generate accurate, review-based answers. 
This setup ensures fast, domain-specific responses while keeping everything fully local and private.
