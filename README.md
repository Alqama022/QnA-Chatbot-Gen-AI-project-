Conversational Q&A Chatbot 🤖

A simple Streamlit-based conversational chatbot powered by LangChain and OpenAI GPT models. The app demonstrates how to build a Q&A chatbot with conversational memory, customizable responses, and integration with environment variables for secure API key management.

🚀 Features

Interactive Streamlit UI for chatting

Uses LangChain with ChatOpenAI for LLM-powered responses

Maintains conversation history using session state

Supports dotenv for API key management

Example notebook (langchain.ipynb) for experimenting with LangChain workflows

Lightweight and easy to deploy

📂 Project Structure
├── app.py              # Streamlit chatbot app
├── langchain.ipynb     # Notebook for LangChain experimentation
├── requirements.txt    # Python dependencies

⚙️ Installation

Clone the repository

git clone https://github.com/your-username/conversational-qa-chatbot.git
cd conversational-qa-chatbot


Create and activate a virtual environment

python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows


Install dependencies

pip install -r requirements.txt


Set environment variables
Create a .env file in the project root:

OPENAI_API_KEY=your_api_key_here

▶️ Usage

Run the Streamlit app:

streamlit run app.py


Open the local URL provided (default: http://localhost:8501) and start chatting!

📒 Notebook

Use langchain.ipynb to explore LangChain pipelines, embeddings, and prompt engineering in Jupyter.

🛠️ Requirements

Dependencies are listed in requirements.txt
:

langchain

openai

huggingface_hub

python-dotenv

streamlit

📌 Future Improvements

Support for multiple LLM providers

Improved conversational memory (vector database integration)

Option to toggle between Q&A mode and fun/creative mode
