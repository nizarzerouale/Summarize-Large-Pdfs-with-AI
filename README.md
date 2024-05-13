# PDF Text Summarization Project

This repository hosts a Python project designed to automate the extraction and summarization of text from PDF documents using advanced NLP techniques and AI, particularly leveraging OpenAI's GPT models. The project clusters text for thematic organization, generates seamless transitions to create a coherent narrative, and outputs the final summaries in a professionally formatted PDF.

## Features

- **Text Extraction**: Extracts readable content from PDFs.
- **Text Segmentation and Clustering**: Segments text into manageable parts and clusters similar sections.
- **Summary Generation**: Uses AI to summarize clustered text and create fluid transitions between sections.
- **PDF Output**: Outputs the final, cohesive narrative as a PDF file, suitable for distribution and archiving.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed on your system. You will also need to install several libraries, which include `fpdf2`, `fitz` (PyMuPDF), `sklearn`, and `sentence-transformers`. You can install these with pip:

```bash
pip install fpdf2 pymupdf scikit-learn sentence-transformers
```
You will also need access to OpenAI's API and set your API key in the environment or within the script securely.

### Installation
Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/pdf-text-summarization.git
```
### Usage
Run the script with:

```bash
if __name__ == "__main__":
    main()
```
Ensure you have a PDF file named 2303.08774v6.pdf in your working directory or modify the file_path in the main() function to point to your PDF file.

## How It Works
The script processes the PDF by extracting text, segmenting and clustering the text based on content similarity, summarizing each cluster, and finally, integrating these summaries into a single document. This document is then saved as a PDF.

## Contributing
Contributions are welcome! Please feel free to fork the repository and submit pull requests. You can also open issues to discuss potential improvements or report bugs.

## Acknowledgments
Special thanks to Linagora for inspiring me to work on this subject.
Thanks to OpenAI for providing the GPT models used in this project.
The sentence-transformers library, which facilitated the embedding and clustering of text.

## Author
Nizar ZEROUALE


