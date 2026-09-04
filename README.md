# PDF RAG

A simple Retrieval-Augmented Generation project that allows you to ask questions about a PDF.

## How it works

1. Upload a PDF
2. Extract text from the PDF
3. Split the text into smaller chunks
4. Convert the chunks into embeddings
5. Store the embeddings in Chroma
6. Retrieve the most relevant chunks for a question
7. Send the retrieved context to Gemini
8. Generate an answer based only on the PDF

## Tech Stack

- Python
- LangChain
- Chroma
- Hugging Face Sentence Transformers
- Google Gemini

## Setup

Install the required packages:

```bash
pip install -r requirements.txt
