# Language Creation Project

This repository contains code and resources for a language generation project using OpenAI's API and Python. The project includes using various tools and libraries to interact with AI and language models for efficient text generation, manipulation, and analysis.

## Features

- Utilizes OpenAI's GPT models for language creation
- Incorporates environment variables for secure API key management
- Dependency management through `pip` and `Python-dotenv`
- Error handling and warnings related to SSL libraries
- Comprehensive setup instructions and usage guides

## Project Structure

- `.env.example`: Example file for environment variables
- `LanguageCreation.ipynb`: Jupyter Notebook with Python code for AI interaction
- `README.md`: This file
- `requirements.txt`: Dependencies required for the project
- `src/`: Directory for source code

## Installation

First, clone the repository to your local machine.

Make sure you have Python 3.9 or higher installed.

Install the required packages using the command in your terminal.

## Environment Setup

Copy the `.env.example` file to `.env` and edit the `.env` file to include your OpenAI API key:

```
API_KEY=your_openai_api_key_here
```

## Running the Project

Open the Jupyter Notebook (`LanguageCreation.ipynb`) and execute the cells to start interacting with OpenAI's GPT models.

## Dependencies

The following Python packages are required for this project:

- `openai`
- `python-dotenv`
- `google-generativeai`


## Troubleshooting

- **SSL Warning**: You may encounter an SSL warning if your Python environment is compiled with `LibreSSL`. For more information and to resolve this, please visit the relevant issue on urllib3's GitHub.
- **API Key Error**: Make sure that your `.env` file is correctly configured with the API key.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Contact

For any inquiries or additional information, please contact [shb@3sholding.com].