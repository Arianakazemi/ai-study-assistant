AI Study Assistant

A command-line chatbot powered by LLM API that helps university students with academic questions.

Features:

1-Focused on academic subjects (Math, Programming, Physics, CS)
2-Maintains conversation history
3-Automatic model fallback if one is unavailable
4-Secure API key management with .env

Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=for-the-badge&logoColor=white)

Setup

1. Clone the repository
git clone https://github.com/Arianakazemi/ai-study-assistant.git
cd ai-study-assistant

1. Install dependencies
pip install -r requirements.txt

1. Create a .env file and add your OpenRouter API key
OPENROUTER_API_KEY=your_api_key_here

1. Run the chatbot
python app.py

Usage
AI Study Assistant
Type 'exit' to quit

You: What is a for loop in Python?
chat: A for loop in Python is used to iterate over a sequence...

Models Used

- google/gemma-4-31b-it
- nvidia/nemotron-3-super-120b
- openai/gpt-oss-120b

Made with ❤️ by Ariana Kazemi
