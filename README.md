# Chatbot-
This project is a GUI-based chatbot developed in Python that interacts with users through natural language. It leverages the OpenAI API to generate intelligent, human-like responses based on user input. The chatbot is designed to simulate real conversations and can be used for general Q&A, casual chat, or customized tasks.

User Interface:

Modern GUI built with Tkinter
Real-time chat interface with timestamps
Message history viewer
Knowledge addition dialog
Settings panel

Database Components:

Conversations table - stores all chat history
Knowledge base - stores questions and answers
User preferences - for customization
Pre-loaded knowledge - common greetings, questions, etc.

Smart Features:

Name recognition - remembers your name
Context awareness - maintains conversation flow
Pattern matching - recognizes different types of inputs
Confidence scoring - for knowledge base responses
Threading - non-blocking response generation

🚀 How to Run:

Save the code as chatbot.py
Install Python (3.7 or higher)
Run the application:
bashpython chatbot.py


📋 Required Libraries:
All libraries used are part of Python's standard library:

tkinter - GUI framework
sqlite3 - Database management
json, datetime, random, re - Utilities
threading - Background processing

🎯 Usage Instructions:

Start chatting - Type messages in the input box
Add knowledge - Use "Add Knowledge" button to teach the bot
View history - See all previous conversations
Clear chat - Reset the current chat display
Settings - View session and database information

