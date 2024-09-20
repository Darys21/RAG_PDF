# Structured RAG PDF Analyzer

This project demonstrates how to extract structured information from PDF documents using Langchain and OpenAI models.

## Overview

The Structured RAG PDF Analyzer is a Streamlit application that allows users to upload PDF documents, analyze them, and extract key information such as title, summary, publication date, and authors.

## Features

- PDF upload and display
- Automatic text extraction from PDFs
- Vector store creation for efficient querying
- Integration with OpenAI API for advanced analysis

## How It Works

1. **PDF Upload**: Users can upload a PDF document through the Streamlit interface.
2. **Text Extraction**: The application extracts text from the uploaded PDF.
3. **Vector Store Creation**: The extracted text is processed and stored in a vector database for efficient querying.
4. **Analysis**: Using OpenAI's language models, the application analyzes the document to extract key information.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/structured-rag-pdf.git
   cd structured-rag-pdf
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app/streamlit_app.py
   ```

2. Open your web browser and navigate to the provided local URL (usually `http://localhost:8501`).

3. Enter your OpenAI API key in the designated field.

4. Upload a PDF document using the file uploader.

5. Click the "Analyze Document" button to extract structured information.

## Configuration

- Ensure you have a valid OpenAI API key.
- You can modify the query in the `streamlit_app.py` file to extract different types of information from the PDF.

## Dependencies

- Streamlit
- Langchain
- OpenAI
- PyPDF2 (or another PDF processing library)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
