# LangChain Chatbot with GPT-3.5-turbo and Qdrant

## Overview
This repository contains the source code for a chatbot built using OpenAI's GPT-3.5-turbo, LangChain, and Streamlit. The chatbot is designed to take documents as input, extract information from them, and answer user queries based on the content of the documents.

## Features
- File Upload: Users can upload PDF files, and the chatbot processes the content for further interaction.
- Document Processing: The chatbot extracts text from PDF files and converts it into chunks for efficient handling.
- Vector Store: Utilizes Qdrant to create a vector store for efficient similarity-based retrieval of information.
- Retrieval QA: Implements a Retrieval Question-Answering chain to provide relevant answers to user queries.
- Streamlit Interface: The user interacts with the chatbot through a Streamlit web interface.

## Getting Started
1. Clone the repository: `git clone https://github.com/yourusername/your-repo.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables in a `.env` file:
OPENAI_API_KEY=your_openai_api_key
QDRANT_URL=your_qdrant_url
QDRANT_API_KEY=your_qdrant_api_key

4. Run the application: `Streamlit run your_app.py`

## Usage
1. Upload PDF files using the provided interface.
2. Click the "Process" button to extract information from the uploaded files.
3. Ask questions related to the documents using the chat input.
4. Receive answers generated by the GPT-3.5-turbo model based on document content.

## Dependencies
- Streamlit
- PyPDF2
- docx
- LangChain
- qdrant_client
- HuggingFace Transformers

## Contributors
-Muhammad Zain Attiq
