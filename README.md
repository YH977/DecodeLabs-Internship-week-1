# Simple Rule-Based AI Chatbot

A lightweight Python-based chatbot that uses predefined rules and dictionary mapping to interact with users. This project demonstrates basic Natural Language Processing (NLP) concepts like input normalization and keyword matching.

## Features
- **Keyword Mapping:** Uses a dictionary to map user inputs to specific responses.
- **Multi-Keyword Support:** Handles multiple greetings or triggers for the same response using tuples.
- **Dynamic Content:** Includes functional responses, such as generating random numbers.
- **Input Cleaning:** Automatically handles case sensitivity and extra whitespace.

## How It Works
The bot operates on a simple `while` loop. It takes user input, converts it to lowercase, and checks it against a dictionary of "rules." If a match is found, it returns the value; otherwise, it provides a default fallback message.

## Installation & Usage
1. Ensure you have [Python 3.x](https://www.python.org/) installed.
2. Clone this repository or download the script.
3. Run the script via terminal:
   ```bash
   project_1.py
