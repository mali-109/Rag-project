Short Description

KrishiMitr RAG is an AI-powered Retrieval-Augmented Generation system that provides accurate agricultural information by retrieving knowledge from agricultural documents using ChromaDB, LangChain, and Groq LLM.

GitHub Repository Description

KrishiMitr RAG is an intelligent agricultural knowledge assistant built using Retrieval-Augmented Generation (RAG). Instead of relying only on an LLM's pretrained knowledge, the system retrieves relevant information from agricultural documents and generates accurate, context-aware responses for farmers and agricultural professionals.

The project uses LangChain for orchestration, ChromaDB as the vector database, sentence-transformer embeddings for semantic search, and Groq LLM for fast response generation.

Features
🌾 Agricultural Question Answering
📄 PDF Document Knowledge Base
🔍 Semantic Search using Vector Embeddings
🗂️ ChromaDB Vector Database
⚡ Fast inference with Groq LLM
🤖 Context-aware AI responses
📚 Easy addition of new agricultural documents
🔄 Retrieval-Augmented Generation (RAG) pipeline
Tech Stack
Python
LangChain
ChromaDB
Groq API
Sentence Transformers
Hugging Face Embeddings
PDF Loader
Recursive Text Splitter
Workflow
Agricultural PDF documents are loaded.
Documents are split into smaller chunks.
Each chunk is converted into vector embeddings.
Embeddings are stored in ChromaDB.
User asks an agricultural question.
Relevant document chunks are retrieved.
Retrieved context is sent to the Groq LLM.
The AI generates an accurate, context-based answer.
Use Cases
Farmer assistance
Crop management guidance
Disease information
Pest management
Fertilizer recommendations
Government scheme information
Agricultural education
Offline agricultural knowledge base (with local documents)
Future Enhancements
Voice-enabled multilingual assistant
Integration with the KrishiMitr mobile app
Image-based crop disease diagnosis
Weather and market price integration
Personalized farming recommendations
Multi-language support (English, Hindi, Marathi, Telugu)
