# Multi-Document RAG Question Answering System

A Retrieval-Augmented Generation (RAG) application that enables question answering over multiple document formats, including PDF, DOCX, and PPTX.

## Features

* Extracts text from PDF, Word, and PowerPoint files
* Splits documents into semantic chunks
* Generates embeddings using Sentence Transformers
* Stores and retrieves document embeddings with FAISS
* Uses Cohere LLM for context-aware answer generation
* Supports natural language querying across multiple documents

## Tech Stack

* Python
* LangChain
* FAISS
* Cohere
* Sentence Transformers
* Google Generative AI
* PyPDF2
* python-docx
* python-pptx

## Workflow

1. Extract text from PDF, DOCX, and PPTX files.
2. Split content into manageable chunks.
3. Create embeddings using `all-MiniLM-L6-v2`.
4. Store embeddings in a FAISS vector database.
5. Retrieve relevant context for user queries.
6. Generate accurate answers using a Retrieval-Augmented Generation pipeline.

## Example Queries

* What is self attention?
* What is hyperacidity?
* What is my project about?
* How to deal with hyperacidity?
* What is a decoder in Transformer?

