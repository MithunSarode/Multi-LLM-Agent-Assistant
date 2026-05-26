# Multi-LLM-Agent-Assistant


## Overview

Multi-LLM Agent Assistant is an AI-powered application that integrates multiple Large Language Models (LLMs) into a single platform. The project allows users to interact with different AI models through a unified interface for answering questions, generating content, solving problems, and assisting with various tasks.

This project is designed to provide flexibility by supporting multiple AI providers and models, making it easier to compare responses and improve productivity.

---

# Features

* Multi-LLM integration
* Interactive chatbot interface
* REST API support
* Frontend and backend architecture
* Docker support for easy deployment
* Environment-based configuration
* Modular and scalable project structure
* Easy model switching
* FastAPI backend support

---

# Technologies Used

## Backend

* Python
* FastAPI
* Uvicorn
* REST APIs

## Frontend

* HTML
* CSS
* JavaScript

## Tools & Platforms

* Docker
* Git & GitHub
* Virtual Environment (venv)

---

# Project Structure

```bash
multiLLM/
│── app/                  # Backend application files
│── frontend/             # Frontend files
│── tests/                # Test cases
│── .env                  # Environment variables
│── env.example           # Sample environment configuration
│── Dockerfile            # Docker configuration
│── docker-compose.yml    # Docker compose setup
│── requirements.txt      # Python dependencies
│── main.py               # Main application entry point
│── run_servers.py        # Server runner script
│── README.md             # Project documentation
```

---

# Installation

## Prerequisites

Make sure the following are installed on your system:

* Python 3.10 or above
* pip
* Git
* Docker (optional)

---

# Clone the Repository

```bash
git clone https://github.com/MithunSarode/Multi-LLM-Agent-Assistant.git
cd Multi-LLM-Agent-Assistant
```

---

# Create Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

```bash
venv\Scripts\activate
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Environment Setup

Create a `.env` file in the project root and add your API keys.

Example:

```env
OPENAI_API_KEY=your_api_key
GEMINI_API_KEY=your_api_key
ANTHROPIC_API_KEY=your_api_key
```

---

# Run the Application

## Using Python

```bash
python main.py
```

OR

```bash
python run_servers.py
```

---

# API Endpoints

| Method | Endpoint  | Description              |
| ------ | --------- | ------------------------ |
| GET    | `/`       | Home route               |
| POST   | `/chat`   | Send message to AI model |
| GET    | `/models` | Get available models     |

---

# Workflow

1. User sends a query from the frontend.
2. Backend API receives the request.
3. Selected LLM processes the request.
4. AI-generated response is returned.
5. Frontend displays the response to the user.

---

# Advantages of the Project

* Supports multiple AI providers
* Scalable and modular architecture
* Easy deployment using Docker
* User-friendly interface
* Faster experimentation with AI models

---

# License

This project is developed for educational and learning purposes.

---

# Author

**Mithun Raj**

GitHub: [https://github.com/MithunSarode](https://github.com/MithunSarode)

---
