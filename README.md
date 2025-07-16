#  RAG-based Q&A

RAG-based Q&A is an LLM-powered chatbot designed to assist with reading and understanding PDF documents. It utilizes Streamlit for the user interface, LangChain for text processing, and OpenAI for language model capabilities.



## About

This application offers the following features:
- **Upload PDF**: Users can upload a PDF document.
- **Text Extraction**: The uploaded PDF is processed to extract text.
- **Text Splitting**: Text is split into smaller chunks for efficient processing.
- **Embeddings**: Text embeddings are generated using OpenAI's embeddings model.
- **Vector Storage**: Embeddings are stored and indexed using FAISS for quick retrieval.
- **Question Answering**: Users can ask questions about the PDF content, and provides relevant answers.
- **Interactive Interface**: The user interacts with PaperScribe through an intuitive web interface powered by Streamlit.



## How to Use

1. Upload a PDF document.
2. Ask questions about the content of the PDF.
3. It provide's relevant answers based on the text extracted from the PDF.

## Installation

To run locally, follow these steps:

1. Clone the repository:
   >>> https://github.com/sahilpancham/RAG_based_Q-A.git

3. Install the required dependencies:
- Streamlit
- PyPDF2
- LangChain
- FAISS
- dotenv
- streamlit-extras
- openai

3. Create a .env file with your OPENAI_API_KEY and pass it to your llm instance and OpenAIEmbeddings call.

4. Run the Streamlit app:
>>> streamlit run main.py


