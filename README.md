# Web & PDF QA System

## Overview
The Web & PDF QA System is a question-answering tool that allows users to extract information from websites and PDF documents using an AI-powered language model. It leverages FAISS for vector search and Hugging Face models for natural language processing.

## Features
- Load content from a website or a PDF file.
- Create vector embeddings using Hugging Face embeddings.
- Store and retrieve documents efficiently with FAISS.
- Answer user queries based on retrieved information.
- Powered by Mixtral-8x7B-Instruct-v0.1 from Hugging Face.

## Installation
To install the required dependencies, run:
```sh
pip install -U gradio langchain-community langchain-core fastapi uvicorn requests beautifulsoup4 pymupdf faiss-cpu huggingface_hub transformers accelerate bitsandbytes langchain-openai
```

## Usage
1. Run the script in a Python environment with the required libraries installed.
2. Provide a website link and/or upload a PDF file.
3. Enter a question related to the provided content.
4. The system will return an AI-generated response based on the extracted information.

