#Data Analyst Agent 2.0

An interactive, autonomous data analysis tool powered by Large Language Models (LLMs). The agent can take datasets or natural language questions, generate Python code for analysis, execute it safely, and display results directly in the browser.

#📖 Overview

The Data Analyst Agent 2.0 is designed to make data analysis accessible and automated.
It supports multiple data formats, generates rich visualizations, and can even scrape the web to fetch required data. The project includes both local setup and containerized deployment options.

#✨ Features

Interactive Web Interface – Upload datasets and questions with ease.

LLM-Powered Analysis – Natural language queries are translated into Python code automatically.

Multi-format Dataset Support – CSV, Excel, JSON, and Parquet supported.

Automated Web Scraping – Fetches online data when no dataset is provided.

Rich Visualizations – Generates plots and charts for insights.

Containerized Deployment – Dockerfile included for smooth deployment.

#🛠️ Technology Stack

FastAPI – Backend framework

LangChain – AI integration

Pandas – Data processing

Vanilla JS + Tailwind CSS – Frontend UI

Chart.js – Visualizations

#🔄 Workflow

User Input – Upload questions and (optionally) a dataset.

LLM Code Generation – The agent writes Python analysis code.

Secure Execution – Code runs in a sandboxed environment.

Results & Visualization – Answers and charts are returned to the browser.

🚀 Getting Started
Local Setup

Set up your environment

# Create a .env file and add:
GOOGLE_API_KEY="your-gemini-api-key-here"


Install dependencies

pip install -r requirements.txt


Run the app

uvicorn app:app --host 0.0.0.0 --port 8000


Visit: http://localhost:8000

Docker Setup

Build the Docker image

docker build -t data-analyst-agent .


Run the container

docker run -p 8000:8000 --env-file .env data-analyst-agent

📊 Example Stats

Python Version: 3.12

Supported Formats: 4+

Deployment Options: 2 (Local & Docker)

#📜 License

This project is licensed under the MIT License.
