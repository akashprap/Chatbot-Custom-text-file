# Project Title

Chatbot using custom text file.

## Getting Started

These instructions will help you set up the project on your local machine.

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)
- virtualenv (Python environment builder)

### Installation

Follow these steps to set up your development environment:

1. **Create a virtual environment**:
    ```bash
    virtualenv venv
    ```
    This command creates a virtual environment named 'venv' in your project directory.

2. **Activate the virtual environment**:
    ```bash
    venv\scripts\activate
    ```
    This command activates the virtual environment. You should see '(venv)' at the beginning of your command prompt once it's activated.

3. **Install the required packages**:
    ```bash
    pip install -r req.text
    ```
    This command installs the packages listed in the 'req.text' file. Make sure you have this file in your project directory and it lists all the necessary packages.

4. **Set the 'OPENAI_API_KEY' environment variable**:
    You need to set the 'OPENAI_API_KEY' in your environment variables. The method to do this depends on your operating system.

5. **Train your model**:
    Train your model on your custom text file and create an embedding. The specific command depends on the code you're using for training.

6. **Run the code**:
    Run your code by defining your custom question. The specific command depends on how your code is structured.
