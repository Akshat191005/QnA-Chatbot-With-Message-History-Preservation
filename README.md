
# RAG-based Conversational QnA Chatbot using LangChain, FAISS, ChromaDB, and Groq

A Retrieval-Augmented Generation (RAG) chatbot that answers user questions using semantic search and LLM-based reasoning. The system retrieves relevant context from vector databases and generates accurate, context-aware responses.

## Features

- Retrieval-Augmented Generation (RAG) pipeline
- Semantic search using FAISS and ChromaDB
- Fast LLM inference using Groq API
- Conversational memory for multi-turn interactions
- Context-aware responses using retrieved embeddings
- Interactive chatbot interface using Gradio

## Architecture

User Query  
→ Embedding Generation  
→ Vector Database (FAISS / ChromaDB)  
→ Retriever  
→ Context Injection  
→ Groq LLM  
→ Response Generation  

## Tech Stack

- Python
- LangChain
- LangChain Expression Language (LCEL)
- FAISS
- ChromaDB
- HuggingFace Embeddings
- Groq API
- Gradio

## Installation

\`\`\`bash
git clone https://github.com/yourusername/rag-chatbot.git
cd rag-chatbot
pip install -r requirements.txt
\`\`\`

Set API key:

\`\`\`bash
export GROQ_API_KEY="your_api_key"
\`\`\`

Run:

\`\`\`bash
python app.py
\`\`\`

## Example Prompts

- "Explain neural networks"
- "Summarize the document"
- "What is machine learning?"

## Concepts Demonstrated

- Retrieval-Augmented Generation (RAG)
- Vector databases and embeddings
- Semantic search
- LLM integration
- Conversational memory

## Author

Akshat Singhvi
EOF
