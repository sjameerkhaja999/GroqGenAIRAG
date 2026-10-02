# RAG Document Q&A with Groq and Llama 3

A Retrieval-Augmented Generation (RAG) application built with **Python, Streamlit, LangChain, Groq, Llama 3, and FAISS** for question answering over research papers.

The application processes research documents, generates vector embeddings, performs similarity-based retrieval, and uses the retrieved context to generate relevant answers to user questions.

## Features

- **Document Embedding**
  - Processes research papers and creates vector embeddings.
  - Stores embeddings in a FAISS vector database.

- **Context-Aware Q&A**
  - Accepts natural-language questions from users.
  - Retrieves relevant document content based on the query.
  - Generates answers using the retrieved context.

- **Document Similarity Search**
  - Performs vector similarity search against embedded research documents.
  - Surfaces documents relevant to the user's query.

- **Interactive Streamlit Interface**
  - Simple browser-based interface for document embedding and question answering.
  - Displays generated responses directly in the application.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Application development |
| Streamlit | Interactive web interface |
| LangChain | LLM and retrieval workflow |
| Groq | LLM inference |
| Llama 3 | Language model |
| FAISS | Vector similarity search |
| OpenAI | Embedding/API integration |
| python-dotenv | Environment configuration |

## Application Workflow

```text
Research Papers
      |
      v
Document Processing
      |
      v
Vector Embeddings
      |
      v
FAISS Vector Database
      |
      v
User Question
      |
      v
Similarity Search
      |
      v
Relevant Document Context
      |
      v
Groq / Llama 3
      |
      v
Generated Answer

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).
See the [LICENSE](LICENSE) file for details.
