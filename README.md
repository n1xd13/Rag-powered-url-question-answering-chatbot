# Rag-powered-url-question-answering-chatbot
This project implements a Retrieval-Augmented Generation (RAG) pipeline using LangChain, Mistral-7B-Instruct, and Qdrant to build a chatbot that can answer questions based on the content of web URLs.

🚀 Features

Extracts and cleans text from online news articles or webpages

Splits documents into manageable chunks for vectorization

Stores embeddings in Qdrant (a vector database)

Retrieves relevant chunks based on user query

Uses Mistral-7B-Instruct model (via Hugging Face) to generate answers

🛠️  Tech Stack

LangChain: Framework to manage LLM and retrieval components

Qdrant: Vector database to store and search document embeddings

Mistral-7B-Instruct: LLM used for answer generation

Hugging Face Hub: To access and host Mistral model

Sentence-Transformers: For generating vector embeddings

UnstructuredURLLoader: For web scraping and text loading

RAG Pipeline:
