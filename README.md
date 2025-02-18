# Conversational RAG with PDF Uploads and Chat History

This Streamlit application allows users to upload PDF files and interactively query their content using a Retrieval-Augmented Generation (RAG) approach. It supports conversational AI with chat history and contextual understanding powered by the Groq LLM and HuggingFace embeddings.

## Features

1. **Upload and Process PDFs:** Extracts and splits text content from uploaded PDF files.
2. **Conversational RAG:** Context-aware question answering using chat history and retrieved document content.
3. **Session-based Chat History:** Maintains conversation history across user queries.
4. **Language Model Integration:** Utilizes Groq LLM (Gemma2-9b-It) and HuggingFace embeddings (all-MiniLM-L6-v2).


## Installation

### Prerequisites

1. Python 3.8+
2. Create a virtual environment (recommended):

   ```bash
    python3 -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate  # For Windows
   ```

### Install Dependencies

  ```bash
  pip install -r requirements.txt
  ```

### Environment Variables

Create a ```.env``` file in the project root and add the following:
```bash
HF_API_TOKEN=your_huggingface_api_token
```


## Usage

1. Run the Streamlit app:
   ```bash
    streamlit run app.py
   ```
2. Enter your Groq API Key in the input box.
3. Upload one or more PDF files.
4. Enter a Session ID (default is ```default_session```).
5. Ask questions based on the uploaded documents.

## Screenshots

<img src="https://github.com/user-attachments/assets/3add8618-af5e-4aed-8678-8cde7fce9478" alt="o_board" width="600" style="max-width:100%; height:auto;">

<img src="https://github.com/user-attachments/assets/84175eac-89e6-4c40-9dfb-21a622e0666f" alt="o_board" width="600" style="max-width:100%; height:auto;">

<img src="https://github.com/user-attachments/assets/b023391f-ffd6-488e-b3a7-60b81eb20e78" alt="o_board" width="600" style="max-width:100%; height:auto;">

<img src="https://github.com/user-attachments/assets/7e696cf6-84de-42c3-bf1f-f72f84d9c997" alt="o_board" width="600" style="max-width:100%; height:auto;">



