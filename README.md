# LLM-Powered Chatbot with Flask

This repository contains a simple yet powerful chatbot implementation using Facebook's BlenderBot and Flask. The project demonstrates how to create an interactive conversational AI that can be accessed through a web interface.

## Features

- **AI-powered conversations**: Utilizes the `facebook/blenderbot-400M-distill` model for generating human-like responses.
- **Web interface**: Built with Flask, allowing easy interaction through a browser.
- **Conversation history**: Maintains context by keeping track of the conversation history.
- **API endpoint**: Provides a `/prompt` endpoint for sending messages and receiving responses.

## Project Structure

- `app.py`: Flask application that serves the web interface and handles API requests.
- `LLM-chatbot.py`: Standalone script for running the chatbot in a command-line interface.
- `templates/index.html`: HTML script for frontend made with using Bootstrap, Bootstrap components and Jinja.

## Getting Started

1. Install the required dependencies: pip install flask flask-cors transformers torch
2. Run the Flask application: python3 app.py
3. Open your browser and navigate to `http://localhost:5000` to start chatting!

## Note

This project is a demonstration of integrating a large language model into a web application. It's suitable for learning purposes but may require additional features and optimizations for production use.



---

Feel free to contribute, report issues, or suggest improvements!
