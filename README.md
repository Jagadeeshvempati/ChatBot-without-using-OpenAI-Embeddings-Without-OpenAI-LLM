# ChatBot-without-using-OpenAI-Embeddings-Without-OpenAI-LLM

Chatbot for Document Question Answering
This repository contains code for setting up a document question answering (QA) system using Python. The system is designed to retrieve answers from a collection of documents in response to user queries. It leverages pre-trained language models from the Hugging Face model hub and provides functionalities for document indexing, retrieval, and question answering.


Features:

Document Indexing: PDF documents are indexed using the langchain library, enabling efficient retrieval of relevant passages.

Language Model Integration: Utilizes Hugging Face's Transformer models for question answering tasks.

Google Drive Integration: Allows users to load PDF documents directly from Google Drive for processing.

Retrieval-Based QA: Implements a retrieval-based question answering system, retrieving relevant answers from indexed documents.


Setup:

Install required dependencies using pip.

Mount Google Drive to access PDF documents.

Configure the folder path containing PDF files.

Create document loaders and index them using langchain.

Set up the language model and retrieval-based QA chain.

Run queries to retrieve answers from indexed documents.


Usage:

Provide a query to the chatbot.

The chatbot will retrieve relevant answers from indexed documents.

Answers are returned based on document content and relevance to the query.


Requirements:

Python 3.x, 
langchain, 
huggingface_hub, 
sentence_transformers, 
unstructured, 
chromadb, 
Cython, 
tiktoken.
