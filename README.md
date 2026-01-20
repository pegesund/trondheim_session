# Cogito x Antire RAG workshop

This repository contains code and resources for the Cogito x Antire RAG workshop held in Trondheim.
The goal of the workshop is to demonstrate how to build and run a RAG pipeline using Colivara and OpenRouter.


## Prerequisites

- **Git**: Ensure that git is installed on your machine. [Download Git](https://git-scm.com/downloads)
- **Python 3.12**: Required for the project. [Download Python](https://www.python.org/downloads/)
- **UV**: Used for managing Python environments. [Install UV](https://docs.astral.sh/uv/getting-started/installation/)

## Setup

1. **Clone the repository:**
   ```bash
    git clone https://github.com/pegesund/trondheim_session.git
    cd trondheim_session
    ```
2. **Configure environment variables**:

   This project uses environment variables for configuration. Copy the example environment file to create your own:
     ```bash
     cp .env.example .env
     ```
   - Edit the `.env` file to add your Colivara and OpenRouter API keys
   - To find your Colivara API key, [Visit Colivara](https://docs.colivara.com/getting-started/quickstart)
   - To find your OpenRouter API key, [Visit OpenRouter](https://openrouter.ai/docs/api/api-reference/api-keys/create-keys)
3. **Install UV:**
   ```bash
   pip install uv
   ```

## Usage

To run the RAG script, use the following command:
```bash
uv run colivara_rag.py
```