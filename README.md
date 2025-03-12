# Custom-AI-Chatbot-Site

A Streamlit-based web application that integrates a custom AI chatbot powered by OpenAI's language models. This project allows users to interact with an AI assistant in a conversational interface.

## Features
- Real-time chat with an AI powered by OpenAI's GPT models.
- Persistent chat history using Streamlit's session state.
- Environment variable support for secure configuration.

## Prerequisites
- Python 3.8+
- An OpenAI API key

## **🚀 Installation & Setup **

##  Install Dependencies  

- pip install -r requirements.txt

##  Set Up Environment Variables  
Create a `.env` file and add your **OpenAI API key** and model configuration:  
```env
OPENAI_API_KEY=your_openai_api_key
LLM_MODEL=gpt-4o
```

## Run the Chatbot  
- streamlit run chatbot.py
  
Open your browser to http://localhost:8501 to interact with the chatbot.

## **Usage**
- Type a message in the input box and press Enter to chat with the AI.
- The chat history is maintained during the session.
