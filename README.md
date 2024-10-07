## Document Parser
# SOC 3 Document Question Answering System

This project extracts text from SOC 3 documents and answers user questions using the Meta-Llama-3-8B-Instruct model via HuggingFace API.

## Features
- Extracts text from PDF documents (SOC 3 format).
- Uses a LLaMA model to answer user questions based on document content.
- Handles large documents by truncating content to fit API limitations.

## Setup

### Requirements:
- Python 3.x
- `fitz` (PyMuPDF)
- `huggingface_hub`

### Installation:
Clone the repository:
```bash
git clone https://github.com/yourusername/soc3-qa.git
cd soc3-qa
