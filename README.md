# Generative AI Search Engine with LangChain Tools and Agents

A powerful search engine application leveraging LangChain, FAISS vector database, and custom tools (Arxiv and Wikipedia) to provide accurate and insightful answers to user queries. This app integrates advanced generative AI capabilities with specialized knowledge bases to enhance the search experience.

## 🚀 Features
- Generative AI-Powered Search: Combines the power of natural language processing with curated tools to deliver contextually accurate and meaningful answers.
- Custom Tools:
  - Arxiv Tool: Searches research papers and academic articles from Arxiv for scholarly responses.
  - Wikipedia Tool: Fetches reliable information from Wikipedia for comprehensive coverage.
- FAISS Vector Database: Efficiently stores and retrieves embeddings for fast and accurate similarity searches.
- Multi-Agent Framework: Utilizes LangChain's agents to dynamically decide which tool to invoke for each query.

## 🛠️ Tech Stack
- LangChain: Framework for building applications powered by large language models.
- FAISS (Facebook AI Similarity Search): Optimized for scalable, high-speed similarity searches.
- Python: Core programming language for the application.
- OpenAI/LLM API: For generative AI responses.
- Streamlit: Frontend for the user interface.

## 🔍 How It Works
#### 1.User Query: 
  - A user inputs a question in natural language.
#### 2.Tool Selection:
  - LangChain agents decide whether to use the Arxiv Tool, Wikipedia Tool, or both.
  - The FAISS database retrieves relevant embeddings for contextual understanding.
#### 3.Response Generation:
  - Information from the selected tools is combined and processed by the generative AI model.
  - The app delivers a coherent, accurate, and detailed response.

## 🧩 LangChain Tools
#### 1. Arxiv Tool
  - Fetches research papers and extracts key information for academic or technical queries.
#### 2. Wikipedia Tool
  - Retrieves general knowledge and detailed information from Wikipedia.
## ⚡ Benefits
- Accurate Results: Combines structured and unstructured data sources for high-quality responses.
- Efficiency: FAISS database ensures fast retrieval for real-time queries.
- Flexibility: Handles diverse queries, from academic to general knowledge.
## 🛡️ Prerequisites
- Python 3.8 or higher
- Valid API key for the generative AI model
- Internet connection to access Wikipedia and Arxiv APIs




