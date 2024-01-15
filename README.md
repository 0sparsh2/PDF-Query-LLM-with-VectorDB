# PDF-Text-Embeddings-Search

## Overview

This project is designed to facilitate the loading of PDF files, here we took example of the book "HeerShneiderman2012-Interactive Dynamics for Visual Analysis" who's pdf was uploaded. The primary goal is to utilize Langchain and Language Models (LLMs), specifically leveraging OpenAI's LLM model, for querying data extracted from the PDF.

Additionally, the project incorporates CassandraDB, specifically Astra from DataStax, to establish a cloud-based VectorDB. This VectorDB enables efficient search and querying based on text embeddings.

## Workflow

1. **PDF Processing:**
   - Load PDF files, such as "HeerShneiderman2012-Interactive Dynamics for Visual Analysis."
   - Split the pages of the PDF.
   - Extract characters from each page.

2. **Text Embeddings:**
   - Convert characters into text embeddings.

3. **Vector Database (CassandraDB - Astra):**
   - Store text embeddings as vector data in the CassandraDB database.
   - Establish a cloud-based VectorDB for quick search and querying.

4. **Language Models (LLMs):**
   - Load Language Models.
   - Utilize LLMs for querying purposes.

5. **Query Processing:**
   - Pass text embeddings to LLMs for queries.

6. **Similarity Search:**
   - AstraDB employs similarity search algorithms.
   - Match queries to the closest information in the VectorDB.

## Technologies Used

- Langchain
- OpenAI's LLM
- CassandraDB (Astra from DataStax)

## How to Use

1. Clone the repository.
2. Install the required dependencies.
3. Follow the provided documentation for detailed instructions on loading PDFs, querying using LLMs, and utilizing the VectorDB.
