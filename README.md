# AI PDF Assistant

## Overview
A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and ask questions about their content.

## Features
- Upload any PDF
- AI-powered question answering
- Semantic search using FAISS
- OpenAI embeddings
- Streamlit interface

## Tech Stack
- Python
- Streamlit
- LangChain
- OpenAI
- FAISS
- pdfplumber

## Installation

pip install -r requirements.txt

## Environment Variables

Create a .env file:

OPENAI_API_KEY=your_api_key

## Run

streamlit run app.py