# Chat With PDF

Chat With PDF files is a project designed to facilitate question-answering tasks using multiple PDF documents. It leverages LangChain's document extraction capabilities to extract content from PDF files. The extracted content is then embedded using BAAI embeddings. Users can Chat with system in questions related to the PDF content, and the Llama model predicts the most appropriate answer based on the similarity of embeddings.

## Features

- **PDF Content Extraction**: Utilizes LangChain's document extraction capabilities to extract content from PDF files.
- **Content Embedding**: Embeds the extracted content using BAAI/bge-small-en-v1.5 embeddings.
- **Question Answering**: Accepts user queries related to the PDF content and provides answers using the Llama model.

## Usage

To use QnA with Multiple PDF files:

1. Visit the project's website: [QnA with PDF](https://huggingface.co/spaces/Mr-Vicky-01/chat-with-PDF)
2. Upload your PDF files containing the relevant content.
3. Wait for the system to extract and embed the content.
4. Input your questions related to the PDF content.
5. Receive the most appropriate answers predicted by the llama model.

## Installation

To deploy the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Mr-Vicky-01/QnA-with-Multiple-PDF-files.git
cd QnA-with-Multiple-PDF-files
pip install -r requirements.txt
python new-app.py
```

## Demo Video
https://github.com/Mr-Vicky-01/Code-Assistant/assets/143078285/7251be5f-9c96-4e82-86be-4894e954e220
