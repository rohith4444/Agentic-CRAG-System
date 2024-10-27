# Research Paper Answer Bot with Agentic Corrective RAG

This project implements a Research Paper Answer Bot using Agentic Corrective Retrieval-Augmented Generation (RAG) to answer questions about key research papers in Generative AI. The bot leverages a vector database and a multi-retriever setup to fetch relevant context from papers like GPT-4, InstructionGPT, Mistral, and others, generating detailed answers with cited sources.

---

## Project Overview

The bot is designed to:
- Retrieve relevant content from research papers on Generative AI using a vector database with embedding models.
- Use corrective RAG strategies, including web search, when relevant documents are lacking in context.
- Display source documents alongside generated answers to ensure transparency and reference accuracy.

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/ResearchPaperAnswerBot.git
cd ResearchPaperAnswerBot
```

### Running the Project

- Open Agentic_RAG.ipynb in Jupyter Notebook or JupyterLab or googleColab.
- Update file paths as needed.
- Execute the cells in the notebook to initialize and run the project.

---

## Project Details

- Vector Database: Implemented with ChromaDB for fast, efficient document retrieval.
- Retrievers: Multiple retrieval techniques (cosine similarity, re-rankers, hybrid retrieval) enhance context relevance.
- Agentic Corrective RAG: Corrective actions like web search are applied when no relevant documents are found, ensuring comprehensive responses.

---

## Web Search Integration

- When local document retrieval does not provide enough context, the system automatically performs a web search and integrates relevant results into the generated response.











