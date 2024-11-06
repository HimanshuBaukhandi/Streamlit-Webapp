# Streamlit-Webapp
# Installation
Note: Ensure you have Python 3.10 or above.

# Create a Virtual Environment (venv):
Run the following command to create a virtual environment:


python -m venv path-to-venv
Here, venv stands for Virtual Environment.

# Activate the venv:
For activation, use:


source path-to-venv/bin/activate
Install Required Packages:
Use the requirements.txt file to install dependencies:


pip install -r requirements.txt
Running the Application
OpenAI Bot:
Navigate to the bot/openai-bot directory.
Run the Streamlit app with:


streamlit run bot-openai-chat.py
LangChain Bot:
Go to the bot/langchain-bot directory.
Start the LangChain bot with:

streamlit run bot-langchain-chat.py

# Indexing:
Go to the bot/rag_indexing directory.
Run the indexing script with:

python indexing.py [url]
Replace [url] with the target URL, for example:

https://lilianweng.github.io/posts/2023-06-23-agent/

# OpenAI Bot Overview
The OpenAI Bot section provides pure OpenAI-powered bots, utilizing a Streamlit web interface for user interactions.

# OpenAI Chatbot:
Supports models such as gpt-3.5-turbo, gpt-4-turbo-preview, and gpt-4-vision-preview.

# OpenAI Image Bot:
Allows image generation with models like dall-e-3 and dall-e-2.

# LangChain Agent Bot
The LangChain Agent Bot employs a Language Model (LLM) to decide which tools to use for various tasks. It uses GPT-3.5-Turbo for decision-making and direct question answering when possible. Although the model is generally effective, it may occasionally modify words in the final response instead of directly passing the answer as intended.

# List of Tools Available:
GPT4-Turbo General Assistant
GPT4-Turbo Code Assistant
GPT3.5-Turbo Code Assistant
DALL-E 3 Image Generator





