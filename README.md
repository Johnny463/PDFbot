# PDF Bot

PDF Bot is a Streamlit-based web application that allows users to upload PDF documents, perform question-answering tasks, and execute various operations related to indexing and vector manipulations. It leverages Pinecone for vector similarity search and OpenAI for question-answering capabilities.

## Features

- **Document Upload:**
  - Upload PDF documents to the application.
  - Extract text content from the uploaded documents.
  - Perform similarity search using Pinecone.

- **Question-Answering:**
  - Ask the bot questions related to the uploaded documents.
  - Utilize OpenAI for generating answers based on the document content.

 
## Getting Started

### Prerequisites

Before running the application, ensure you have the following dependencies installed:

- Python 3.x
- Streamlit
- Fitz
- Pinecone
- OpenAI
- Other dependencies (specified in requirements.txt)

 ### Installation

1. Clone the repository

```bash
git clone https://github.com/Johnny463/PDFbot.git
cd PDFbot
```
2. Install the dependencies
```bash
pip install -r requirements.txt
```
 ### Usage
```bash
streamlit run app.py
```
Visit the provided URL (usually http://localhost:8501) in your web browser to access the PDF Bot application.



### Configuration

To configure API keys and other environment variables, create a .env file in the project root and add the following:
``` env
PINECONE_API_KEY=your_pinecone_api_key
OPENAI_API_KEY=your_openai_api_key
```



### Screenshots
#### Screenshot1: Document Upload
![Screenshot 2024-08-02 112045](https://github.com/user-attachments/assets/537b8037-8559-4e5e-b3ae-fa886c14f314)

- **Overview:**
  - This page allows users to upload PDF documents to the PDF Bot application.

 
 
- **Key Features:**
  - Users can see a clear title indicating the purpose of the page ("Transcript Upload").
  - A file upload button is prominently displayed, inviting users to upload PDF documents.

  
- **Usage Instructions:**

  - Users are encouraged to click on the "Upload Document" button.
  - A brief description may be provided on supported file formats, e.g., "Tip: Supported file formats include PDF."

#### Screenshot2: Question-Answering
![Screenshot 2024-08-02 112557](https://github.com/user-attachments/assets/323469c8-bd43-49a9-9a20-15a3bdb79631)
![Screenshot 2024-08-02 111629](https://github.com/user-attachments/assets/685e5452-dd8f-4887-82f5-a6d1ef67af31)




- **Overview:**

  - This page allows users to interact with the chatbot for question-answering tasks.
- **Key Features:**

  - Clear header/title ("Question Answers") sets the context for the user.
  - A chat history section displays previous interactions between the user and the bot.
  - A text input field and a button for users to ask questions.
- **Usage Instructions:**

  - Users can type questions into the input field and click the "Ask" button to receive answers.
  - Relevant icons may be used to represent the user and bot interactions.

## License
```
MIT License

Copyright (c) 2024 Muhhamd Junaid

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```



