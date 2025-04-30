# PDF to MCQ Generator

A Gradio-based web app that generates multiple-choice questions (MCQs) from any uploaded PDF file. It summarizes the content using BART, extracts keywords using RAKE, and forms Bloom's Taxonomy-based questions with randomized options.

## Features

- Upload a PDF and specify a topic
- Choose how many MCQs to generate (5–30)
- Summarizes text, extracts keywords, and generates MCQs
- Gradio interface for easy interaction

## Tech Stack

- Python
- Gradio
- HuggingFace Transformers (BART)
- RAKE-NLTK
- PyMuPDF for PDF text extraction

## How to Run (Colab)

1. Clone the repo or copy the code into a Google Colab notebook
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook and launch the Gradio app

## License

MIT License
