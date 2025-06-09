# Rag-powered-url-question-answering-chatbot
This project implements a Retrieval-Augmented Generation (RAG) pipeline using LangChain, Mistral-7 B-Instruct, and Qdrant to build a chatbot that can answer questions based on the content of web URLs.

The LLM_PART1 consists of the basic requirements and the knowledge base required and used in the LLM_projectPART2. So, first, try to understand the LLM_PART1, then move on to the LLM_projectPART2 for the main execution of the project.

🚀 Features

Extracts and cleans text from online news articles or webpages

Splits documents into manageable chunks for vectorisation

Stores embeddings in Qdrant (a vector database)

Retrieves relevant chunks based on the user query

Uses Mistral-7 B-Instruct model (via Hugging Face) to generate answers

🛠️  Tech Stack

LangChain: Framework to manage LLM and retrieval components

Qdrant: Vector database to store and search document embeddings

Mistral-7 B-Instruct: LLM used for answer generation

Hugging Face Hub: To access and host the Mistral model

Sentence-Transformers: For generating vector embeddings

UnstructuredURLLoader: For web scraping and text loading


