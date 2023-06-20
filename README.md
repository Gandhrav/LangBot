# GitHub Repo QA

This project is a web application that utilizes the power of GPT and utilizing Prompt Engineering with LangChain to build a bot that could answer technical questions regarding a specific repository on GitHub. The app uses Streamlit for the frontend.
## Table of Contents
- [Features](#features)
- [Installation&Usage](#installation&usage)

## Features

- **GitHub User Analysis**: Enter a GitHub user's username and repo name to analyze their repositories.
- **GPT-powered Analysis**: Utilizes the GPT model to analyze each repository.
- **LangChain Integration**: Integrates with LangChain for advanced language processing and understanding.

## Installation&Usage

To run this application locally, please follow these steps:

1. Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Gandhrav/LangBot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd LangBot
   ```

3. Install the required dependencies using the requirements.txt file:
   ```bash
   pip install -r requirements.txt
   ```

4. Set your ‘OPENAI_API_KEY’ Environment Variable via the cmd prompt. Run the following in the cmd prompt, replacing <yourkey> with your API key:
```bash
setx OPENAI_API_KEY “<yourkey>”
```

5. Run the application:
   ```cmd
   from langbot import print_answer
   print_answer(your question)
   ```
6. Enter the github username/ownername in the owner text field and the repo name in the repository text field. 
