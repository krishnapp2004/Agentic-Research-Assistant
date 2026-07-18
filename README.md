# ResearchPilot AI

## Multi-Agent Research Assistant using Agentic AI, Retrieval-Augmented Generation (RAG), Google Gemini, and FAISS

ResearchPilot AI is an intelligent multi-agent research assistant that leverages Agentic AI, Retrieval-Augmented Generation (RAG), semantic search, and Large Language Models to simplify research paper analysis.

The system enables users to upload research papers, extract information, perform semantic searches, generate summaries, answer questions, identify research gaps, create literature reviews, and generate educational resources such as quizzes and flashcards.

This project demonstrates the practical implementation of modern AI concepts including Multi-Agent Systems, Vector Databases, Semantic Retrieval, and Large Language Models.

---

# Table of Contents

- Overview
- Features
- System Architecture
- Technology Stack
- Workflow
- Project Structure
- Installation
- Usage
- AI Agents
- Core Functionalities
- Example Queries
- Applications
- Future Enhancements
- Learning Outcomes
- Author
- License

---

# Overview

ResearchPilot AI combines multiple AI agents with semantic retrieval techniques to create an intelligent research assistant capable of understanding academic papers instead of simply searching through them.

Unlike traditional document search systems, ResearchPilot AI retrieves contextually relevant information using vector embeddings before generating responses with Google's Gemini Large Language Model.

The project demonstrates a complete Retrieval-Augmented Generation (RAG) pipeline integrated with an Agentic AI architecture.

---

# Features

## Document Processing

- Upload research papers in PDF format
- Extract complete document text
- Intelligent metadata extraction
- Automatic document indexing

## Semantic Search

- Context-aware semantic retrieval
- Sentence embeddings
- FAISS vector database
- Similarity search

## Agentic AI

Specialized AI agents perform different tasks:

- Summary Agent
- Question Answering Agent
- Search Agent
- Research Gap Agent
- Literature Review Agent
- Router Agent

The Router Agent automatically determines which specialized agent should process a user request.

## Research Assistance

- Research paper summarization
- Question answering
- Literature review generation
- Research gap identification
- Future work suggestions
- Research idea generation

## Educational Features

- Flashcard generation
- Quiz generation
- Conversation memory
- PDF report export

## Analytics

- Research dashboard
- Paper categorization
- Research statistics
- Paper comparison

---

# System Architecture

```

                          User Query
                               │
                               ▼
                        Router Agent
                               │
          ┌──────────────┬──────────────┬──────────────┐
          ▼              ▼              ▼
   Summary Agent     QA Agent     Search Agent
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                Semantic Search
                   (FAISS Index)
                         │
                         ▼
              Relevant Research Chunks
                         │
                         ▼
                 Google Gemini API
                         │
                         ▼
                  Generated Response

```

---

# Technology Stack

## Programming Language

- Python

## AI & Machine Learning

- Google Gemini API
- Agentic AI
- Retrieval-Augmented Generation (RAG)
- Sentence Transformers

## Libraries

- LangChain
- FAISS
- PyMuPDF
- NumPy
- FPDF

## Development Environment

- Google Colab

---

# Workflow

1. Upload research papers.
2. Extract text from PDF documents.
3. Split documents into semantic chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings inside a FAISS vector database.
6. Retrieve relevant chunks through semantic search.
7. Route user requests to specialized AI agents.
8. Generate context-aware responses using Google Gemini.
9. Present the final answer with supporting context.

---

# Project Structure

```

ResearchPilot-AI/

│

├── Agentic_AI_Project.ipynb

├── README.md

├── requirements.txt

├── sample_papers/

├── outputs/

└── images/

```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/krishnapp2004/Agentic-Research-Assistant.git
```

Navigate to the project directory.

```bash
cd Agentic-Research-Assistant
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```

Open the notebook using Google Colab or Jupyter Notebook.

Configure your Google Gemini API key before executing the notebook.

---

# Usage

1. Upload one or more research papers.
2. Extract text and metadata.
3. Generate vector embeddings.
4. Build the FAISS index.
5. Ask questions about uploaded papers.
6. Generate summaries.
7. Create literature reviews.
8. Identify research gaps.
9. Generate quizzes and flashcards.
10. Export reports as PDF.

---

# AI Agents

### Summary Agent

Generates concise summaries of uploaded research papers.

### Question Answering Agent

Answers user questions using only retrieved document context.

### Search Agent

Retrieves semantically similar document chunks.

### Research Gap Agent

Identifies limitations, challenges, and future research opportunities.

### Literature Review Agent

Generates comprehensive literature reviews from uploaded papers.

### Router Agent

Routes user requests to the most appropriate AI agent.

---

# Core Functionalities

- PDF Upload
- Metadata Extraction
- Semantic Search
- Retrieval-Augmented Generation
- Multi-Agent Architecture
- Literature Review Generation
- Research Gap Detection
- Flashcard Generation
- Quiz Generation
- Research Idea Generation
- AI Paper Categorization
- Research Dashboard
- Conversation Memory
- PDF Report Export

---

# Example Queries

- Summarize this research paper.
- What is the main contribution of this paper?
- Identify research gaps.
- Generate a literature review.
- Compare uploaded research papers.
- Generate quiz questions.
- Create flashcards.
- Suggest future research directions.
- Explain the proposed methodology.
- What datasets were used?

---

# Applications

ResearchPilot AI can be applied in:

- Academic Research
- Literature Surveys
- Research Paper Analysis
- Thesis Preparation
- Student Learning
- AI-Assisted Education
- Knowledge Discovery
- Intelligent Document Retrieval

---

# Future Enhancements

Future improvements include:

- Web application using Streamlit or Flask
- Multi-document comparison
- Citation generation
- Research recommendation system
- Persistent vector database
- User authentication
- Cloud deployment
- API deployment
- OCR support for scanned PDFs

---

# Learning Outcomes

This project demonstrates practical implementation of:

- Agentic AI
- Retrieval-Augmented Generation
- Semantic Search
- Large Language Models
- Vector Databases
- Prompt Engineering
- Multi-Agent Systems
- Research Automation
- Embedding Models
- AI-powered Document Analysis

---

# Repository

GitHub Repository

https://github.com/krishnapp2004/Agentic-Research-Assistant

GitHub Profile

https://github.com/krishnapp2004

---

# Author

**P P Krishna**

Bachelor of Technology

Computer Science and Engineering

Areas of Interest

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Computer Vision
- Natural Language Processing
- Generative AI
- Large Language Models

GitHub

https://github.com/krishnapp2004

Project Repository

https://github.com/krishnapp2004/Agentic-Research-Assistant

---

# License

This project is developed for educational and research purposes.

Feel free to fork the repository, explore the implementation, and contribute improvements.
