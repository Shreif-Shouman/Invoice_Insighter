# 📄 layoutlm-invoices App

Welcome to the **layoutlm-invoices App**! This application leverages the power of [Streamlit](https://streamlit.io/), [layoutlm-invoices Model](https://huggingface.co/impira/layoutlm-invoices), [Hugging Face Transformers](https://huggingface.co/transformers/), and [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) to answer questions about your documents, specifically invoices. 🚀

## 🌟 Features

- **Upload PDF or Image files**: Upload your invoices in PDF, PNG, JPG, or JPEG formats.
- **Convert PDFs to Images**: Automatically convert PDF documents into images for processing.
- **Question Answering**: Use state-of-the-art AI to answer questions about your uploaded documents.

## 📦 Installation

To get started with the layoutlm-invoices App, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/layoutlm-invoices.git
    cd layoutlm-invoices
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application**:
    ```bash
    streamlit run lay.py
    ```

## 🛠️ Usage

1. **Upload your document**: Use the sidebar to upload your PDF or image file.
2. **View the uploaded document**: The document will be displayed in the main window.
3. **Ask questions**: Enter your question in the text input box and press Enter. The app will process your question and display the answer.

## 🧠 Technologies Used

- **Streamlit**: For building the interactive web application.
- **Hugging Face Transformers**: For the document question-answering model.
- **pdf2image**: For converting PDF documents to images.
- **Pytesseract**: For optical character recognition (OCR) to extract text from images.
