# 🦜🔗 Chat With Website

This project is a Streamlit application that extracts text from a specified website in real time and answers questions about the content provided. You can ask questions related to the website content and get accurate responses based on the extracted data.

## Features

- Extracts and processes content from any specified website.
- Uses Google Generative AI Embeddings for semantic understanding of the website content.
- Utilizes the ChatGroq model for answering questions based on the extracted data.
- Provides a conversational interface for asking questions about the website content.

## Installation

### Prerequisites

- Python 3.8+
- Streamlit
- LangChain
- BeautifulSoup
- Requests

### Setup Instructions

1. Clone the repository:

2. Create a virtual environment:
python -m venv venv


 4. Install dependencies
 pip install -r requirements.txt

 5. Run the Streamlit app:
streamlit run main.py



Usage
Open the Streamlit app in your browser.
Enter your Google API key and Groq API key.
Insert the URL of the website you want to extract content from.
Ask a question related to the website content.
Click the "Submit Query" button to get the response.

Example Questions
What is the main topic of this page?
Can you summarize the key points?
What are the key features mentioned on this website?

