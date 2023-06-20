# GPT & LangChain Complex Repo Finder

This project is a web application that utilizes the power of GPT (Generative Pre-trained Transformer) and LangChain to help you find the most technically complex and challenging repositories on GitHub. By providing a GitHub user's URL, the application will analyze their repositories and present you with the most sophisticated projects.

## Table of Contents
- [Features](#features)
- [Installation & Usage](#installation)

## Features

- **GitHub User Analysis**: Enter a GitHub user's URL to analyze their repositories.
- **GPT-powered Analysis**: Utilizes the GPT model to analyze each repository.
- **LangChain Integration**: Integrates with LangChain for advanced language processing and understanding.

## Installation & Usage

To run this application locally, please follow these steps:

1. Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/your-username/gpt-langchain-complex-repo-finder.git
   ```

2. Navigate to the project directory:
   ```bash
   cd gpt-langchain-complex-repo-finder
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
   
