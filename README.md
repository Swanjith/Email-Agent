# Email Agent

This project is an AI-powered Gmail assistant built with Python, Google Gmail API, LangChain, Ollama, and LangGraph. It monitors your inbox, classifies incoming emails, generates a reply, and can flag messages for later review.

## What this project does

The agent performs the following steps:

1. Connects to your Gmail account using OAuth authentication.
2. Checks for new emails in the inbox.
3. Classifies each email as a normal or non-normal email.
4. If the email looks like a normal message, it generates a polite reply.
5. Sends the generated reply back through Gmail.
6. Flags suspicious or non-normal emails using Gmail labels.

## Technologies used

- Python
- Google Gmail API
- LangChain
- Ollama
- LangGraph
- Pydantic


## Requirements

Before running the project, make sure you have:

- Python 3.10 or newer
- Ollama installed and running locally
- A Google Cloud project with Gmail API enabled
- OAuth credentials downloaded as `credentials.json`

## Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
