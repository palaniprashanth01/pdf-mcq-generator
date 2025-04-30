# PDF to MCQ Generator

A Python application that generates multiple-choice questions (MCQs) from PDF documents using natural language processing (NLP). This tool extracts text, summarizes content, and creates MCQs aligned with Bloom's Taxonomy, providing an interactive user interface.

## Project Goal
To automate the creation of educational MCQs from PDF documents, leveraging NLP to extract key concepts and generate diverse questions. This project demonstrates proficiency in Python, NLP libraries, and web interfaces.

## Technologies Used
- **Python**: Core programming language.
- **Transformers**: For text summarization using BART (`facebook/bart-large-cnn`).
- **RAKE-NLTK**: For keyword extraction.
- **PyMuPDF**: For PDF text extraction.
- **Gradio**: For building an interactive web interface.
- **NLTK**: For text processing.
- **Git**: For version control.
- **Google Colab**: For development and testing.

## Installation
```bash
pip install -r requirements.txt
python -m nltk.downloader punkt stopwords punkt_tab wordnet
