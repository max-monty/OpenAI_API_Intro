# Introduction to OpenAI API

Welcome to this introductory project on using the OpenAI API. This project is designed for students with no prior knowledge of the OpenAI API.

## Project Setup

### Prerequisites

- Python 3.x
- Visual Studio Code (VSCode)

### Installation Steps

1. **Clone or Download the Project**:

   - Use `git clone` or download this project onto your local machine.

2. **Install Python**:

   - If not already installed, download and install Python from [python.org](https://www.python.org/).

3. **Set up VSCode**:

   - Download and install Visual Studio Code from [code.visualstudio.com](https://code.visualstudio.com/).
   - Open VSCode and install the Python extension.

4. **Setting Up a Virtual Environment**:

   - Open a terminal in VSCode.
   - Navigate to the project directory.
   - Run `python -m venv venv` to create a virtual environment named 'venv'.
   - Activate the virtual environment:
     - On Windows, run `venv\\Scripts\\activate`.
     - On MacOS/Linux, run `source venv/bin/activate`.
   - Your terminal should now show the virtual environment name.

5. **Install Required Packages**:

   - Open a terminal in VSCode.
   - Navigate to the project directory.
   - Run `pip install -r requirements.txt` to install dependencies.

6. **API Key Setup**:
   - Sign up for an OpenAI account and obtain an API key from [OpenAI](https://openai.com/).
   - Replace `your_api_key_here` in the `.env` file with your actual API key.

### Running the Project

- In the terminal, run `python main.py`.
- Enter a prompt when prompted and see the response from the OpenAI API.

## Expanding the Project

After getting familiar with the basics, you can expand this project in several ways:

1. **Enhance the Query Function**:

   - Add more parameters to the `query_openai` function to customize responses (e.g., temperature, max tokens).

2. **Create a GUI**:

   - Build a graphical user interface (GUI) for easier interaction with the application.

3. **Explore Different Engines**:
   - Try using different engines available in the OpenAI API and observe how the responses vary.

## New Project Ideas

1. **Chatbot**:

   - Create a simple chatbot that converses using the OpenAI API.

2. **Content Generator**:

   - Build an application that generates creative content like poems, stories, or code.

3. **Language Translator**:
   - Develop a tool that uses the OpenAI API to translate text between languages.

Enjoy exploring the world of AI with OpenAI!
