Intelligent Customer Support Chatbot

This project implements an AI-powered customer support chatbot that can automatically:

Categorize incoming customer queries into Technical, Billing, or General issues

Analyze customer sentiment (positive, negative, neutral)

Generate helpful responses or escalate the issue if needed

Provide an interactive Gradio interface for testing

The chatbot is built with LangGraph, Python, and Gradio, and is designed to demonstrate intelligent query handling for customer service workflows.

📂 Project Structure

Intelligent_Customer_Support_chatbot.ipynb → Main notebook containing code for the chatbot workflow

README.md → Project documentation

⚡ Features

Automated Categorization – Detects whether a query is Technical, Billing, or General.

Sentiment Analysis – Understands customer tone for better responses.

Response Generation – Provides step-by-step troubleshooting and answers.

Escalation – Routes complex issues to human support.

Gradio UI – Simple web interface to interact with the chatbot in Colab.

🚀 Setup Instructions

Clone / Upload Notebook

Upload Intelligent_Customer_Support_chatbot.ipynb to Google Colab (or run locally with Jupyter).

Install Dependencies

pip install gradio langgraph python-dotenv


Environment Variables

Create a .env file to store your API keys (e.g., Groq, OpenAI).

GROQ_API_KEY=your_api_key_here


Run the Notebook

Execute all cells to build and run the workflow.

Launch Gradio Interface

The final cell will create a chatbot interface.

In Colab, run:

iface.launch(share=True)


Copy the generated public link to interact with your chatbot.

🧪 Example Query

User:

"My internet keeps lagging especially during the afternoon hours, can you help me?"

Bot:

Category → Technical

Sentiment → Neutral

Response → Troubleshooting steps + follow-up questions

📌 Future Improvements

Integrate with a real customer database / CRM

Add multi-turn conversation memory

Support multiple languages

Deploy as a standalone web app or API

🛠️ Tech Stack

Python 3.10+

LangGraph – for workflow state management

Gradio – for user interface

dotenv – for managing API keys securely
