# OpenAI-Integration

This Python script is used to interact with the OpenAI API. It uses the `openai` Python package to create a client that communicates with the API.

## How it works

The script defines a class `ChatCompletion` which is used to create chat completions with the OpenAI API. The class has a method `create` which sends a request to the OpenAI API to generate a chat completion.

The `create` method uses the `chat.completions.create` method from the `openai` package. It passes a model name and a list of messages to this method. The messages include a system message that sets the behavior of the assistant and a user message that the assistant should respond to.

The `API_KEY` for authenticating with the OpenAI API is retrieved from an environment variable named `OPENAI_API_KEY`.

The `main` function creates an instance of the `ChatCompletion` class and prints the result of the `create` method.

## Installation

Before running the script, you need to install the required Python packages. These packages are listed in the `requirements.txt` file. You can install them using pip, which is a package manager for Python.

Follow these steps to install the dependencies:

1. Open a terminal.
2. Navigate to the directory that contains the `requirements.txt` file.
3. Run the following command:

```bash
$ pip install -r requirements.txt
```

## Usage

Before running the script, make sure to set the `OPENAI_API_KEY` environment variable to your OpenAI API key. Then, you can run the script with a Python interpreter.

```bash
$ cd OpenAI-Integration
$ python OpenAI.py
```
