# [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ragchatbot-txt-openai-czeyvla6eqoc37qrsxbzue.streamlit.app/)

This is a Document Question Answering app using LangChain, OpenAI and Streamlit. Upload your document and provide more context to LLMs.

### Overview: 
This app is a sophisticated question-answering (QA) application built using Streamlit, Langchain, and OpenAI's GPT models. This application enables users to upload textual documents and ask questions based on the content of these documents. It utilizes RAG to provide accurate and context-relevant answers.

### Features 
- Document Upload: Users can upload text documents in .txt format. 

- Query Processing: After uploading a document, users can input queries or questions to gain insights from the uploaded document. 

- Secure API Key Handling: The app requires an OpenAI API key for processing, ensuring secure and authenticated access to OpenAI's language models. 

- Responsive UI: Built with Streamlit, the app provides an interactive and user-friendly interface. 

## Installation and Setup

To run this on your local machine, follow these steps:

### Clone the Repository: 
Clone this repository to your local machine using git clone.

### Install Dependencies:

Ensure you have Python installed. Install required packages using pip install -r requirements.txt. Set Up OpenAI API Key: You must have an OpenAI API key to use this app. If you don't have one, you can obtain it from OpenAI's website.

### Run the Streamlit App:

Navigate to the app's directory in your terminal. Run the command streamlit run your_app_script.py. How to Use Start the App: Open the app in your web browser after running the Streamlit command.

- Upload a Document: Click on the file uploader to upload your .txt document.

- Enter Your Query: Once the document is uploaded, type in your question in the text input field.

- Enter OpenAI API Key: Provide your OpenAI API key securely in the provided field.

- Submit and Get Answers: Click 'Submit' to process your query. The app will display the answer based on the content of your uploaded document.

Security Note:

The app uses text input for OpenAI API key entry, ensuring the key is not stored or logged. Always keep your API keys confidential and never share them publicly.
