# pdf_chatbot_lanchain
This Streamlit application allows users to upload PDF documents, process their text, and ask questions about the content using Google's Generative AI embeddings and the FAISS vector store.

## Features

- Upload PDFs: Users can upload multiple PDF files.
- Process PDF Text: Extracts text from uploaded PDFs and splits it into chunks for better processing.
- Vector Store Creation: Uses FAISS to create a vector store of the text chunks for efficient similarity search.
- Conversational AI: Utilizes Google's Generative AI for question-answering based on the context of the PDF content.

## Requirements

- Python 3.8+
- Streamlit
- PyPDF2
- LangChain
- FAISS
- Google Generative AI SDK
- Python-dotenv

## Installation

1. Clone the repository: (https://github.com/dhruv-tiwari0/dhruv-tiwari0-chatbot_using_Langchain-Framework-Vector-DB-Semantic-Search.git)
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
GOOGLE_API_KEY="AIzaSyBAhZ2gV-H8e5H0xYAM_mHGuyGEqQUlncM"
streamlit run pdf.py
.
├── pdf.py
├── .env
├── requirements.txt
├── README.md
