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
- Retrieves the most relevant text chunks using TF-IDF, character-level similarity, and cosine similarity before answering.

## Technologies

- Python
- Hugging Face Transformers
- PyTorch
- PyPDF
- Pandas
- Jupyter Notebook
- Scikit-learn

## How it Works

## How it Works

1. The user selects a PDF file.
2. The system extracts and cleans the PDF text.
3. The text is split into overlapping chunks.
4. TF-IDF and cosine similarity are used to retrieve the most relevant chunks.
5. A Transformer-based QA model extracts the best answer from the selected chunks.
6. The system displays the answer, confidence score, inference time, and stores the Q&A history.

## Example

**Question**

> Who created the Deep Learning Specialization?

**Answer**

> Andrew Ng

**Confidence**

> 99.73%

## Future Improvements

- Implement Retrieval-Augmented Generation (RAG)
- Add semantic search using embeddings
- Build a Gradio web interface
- Highlight the answer inside the PDF
