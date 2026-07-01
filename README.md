# 📄 PDF Question Answering System

An NLP application that allows users to upload a PDF document and ask questions about its content using a Transformer-based Question Answering model.

## Features

- 📄 Upload any PDF document.
- 🤖 Ask unlimited questions about the uploaded PDF.
- 🧠 Uses a pre-trained Hugging Face Transformer model.
- 📊 Displays the confidence score for each answer.
- 📚 Stores question-answer history.
- ⏱️ Measures inference time.
- ✂️ Splits long documents into overlapping text chunks to improve answer quality.

## Technologies

- Python
- Hugging Face Transformers
- PyTorch
- PyPDF
- Pandas
- Jupyter Notebook

## How it Works

1. Upload a PDF document.
2. The system extracts all text from the PDF.
3. The document is split into overlapping chunks.
4. The model searches across all chunks.
5. The answer with the highest confidence score is returned.

## Example

**Question**

> Who created the Deep Learning Specialization?

**Answer**

> Andrew Ng

**Confidence**

> 99.73%

## Future Improvements

- Support RAG (Retrieval-Augmented Generation)
- Add semantic search using embeddings
- Build a Gradio web interface
- Highlight the answer inside the PDF