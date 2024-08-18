# Chat with Word Documents

This application allows users to upload a Word document file and ask questions about its content. It uses natural language processing to understand and respond to user queries based on the document content.

## Features

- Word document file upload
- Text extraction from Word documents
- Question answering based on document content
- Option to use either Google Palm (online) or Ollama (offline) for processing

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/chat-with-word.git
   cd chat-with-word
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Set up your Google API key in Streamlit secrets or as an environment variable.

4. If using Ollama, make sure it's installed and the "llama2" model is available.

## Usage

Run the Streamlit app:

```
streamlit run main.py
```

Then, open your web browser and go to the URL shown in the terminal (usually http://localhost:8501).

1. Use the sidebar checkbox to choose between Google Palm (online) and Ollama (offline).
2. Upload a Word document file (.docx) using the file uploader.
3. Once uploaded, you can start asking questions about the document content in the text input box.

## Note

This application requires an active internet connection when using Google Palm. For offline usage, select the Ollama option.
