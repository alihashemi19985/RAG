# RAG Chatbot with Chat History, Trimmer, Reranking, using **bge-m3** and **Deepseek**

## Project Description

This project is a **RAG (Retrieval-Augmented Generation)** chatbot that utilizes **chat history with trimmer**, the **bge-m3 embedding model** for converting text into vectors, and the **Deepseek language model** for generating responses. Additionally, the system implements **Reranking** to improve the quality of responses by ranking the retrieved information based on relevance before generating the final output. The system is capable of maintaining and managing the conversation history to improve responses dynamically.

## Features

- **bge-m3 embedding model** for converting data into meaningful vectors and searching within data.
- **Chat history management with Trimmer** for removing unnecessary content and reducing memory usage.
- **Deepseek language model** for generating accurate and meaningful responses based on the data.
- **RAG system** that retrieves external information to augment responses.
- **Reranking** for better response accuracy by ranking the retrieved data based on relevance before response generation.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- The following libraries are required:
  - `transformers`
  - `faiss`
  - `torch`
  - `deepseek`
  - `bge-m3`
  - `trimmer`
  - `requests`
  - `flask` (if API is needed)


