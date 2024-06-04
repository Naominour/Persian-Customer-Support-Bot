# Persian Customer Support Bot

This project provides a customer support bot that delivers responses in Persian. The core code was adjusted to integrate OpenAI's API to achieve the required functionality. 

## Features

- **Persian Language Support**: The bot provides responses in Persian.
- **OpenAI Integration**: Utilises OpenAI's API to generate responses.

## Installation

To set up the project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Requirements

The project requires the following Python packages, as specified in `requirements.txt`:

- openai
- pandas
- langgraph==0.0.45 
- langchain-community 
- tavily-python 
- langchain-openai
- translate

## Usage

1. **Set up OpenAI API Key**:
    You need to have an OpenAI API key to use the bot. Set the API key as an environment variable.

2. **Run the Bot**:
    Execute the Jupyter Notebook or Python script that initialises and runs the bot. For Jupyter Notebook, open the notebook file (`Persian-Customer-Support-Bot.ipynb`) and run the cells sequentially.

## Configuration

- **Language Settings**: The bot is configured to provide responses in Persian. Adjustments were made in the code to ensure all outputs are correctly translated.
- **API Integration**: The code utilises OpenAI's API for generating responses. Ensure that your API key is valid and has the necessary permissions.

## License

This project is licensed under the MIT License.
The original codebase was sourced from the LangChain AI project, which is also licensed under the MIT License.

