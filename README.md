# Project 1: AI Chatbot Built in Python with Ollama Model

This repository contains **Project 1**, which sets up a conversational AI chatbot powered by the Ollama platform and the Llama 3.2 language model. The chatbot leverages `langchain` and `langchain-ollama` libraries to provide a seamless, interactive experience.

---

## Features

- Run the **Llama 3.2** open-source language model locally on macOS or Windows.
- Interactive chatbot that maintains conversational context.
- Easily customizable and extendable.

---

## Setup Instructions

### Prerequisites

1. **Install Ollama:**
   - Download Ollama from its [GitHub repository](https://github.com/ollama/ollama.git) or the [official website](https://ollama.com/).
   - Verify the installation:
     ```bash
     ollama
     ```
     If the command responds, Ollama is successfully installed on your system.

2. **Download the Llama 3.2 Model:**
   - Use the following command to download the model:
     ```bash
     ollama pull llama3.2
     ```
   - Test the model to ensure it is functioning correctly:
     ```bash
     ollama run llama3
     ```

   > Ollama allows you to download and run open-source large language models (LLMs) locally.

3. **Set Up the Python Environment:**
   - Open VS Code or any terminal of your choice.
   - Create a virtual environment for the project:
     ```bash
     python -m venv chatbot
     ```
   - Activate the virtual environment:
     - On Windows:
       ```bash
       .\chatbot\Scripts\activate.bat
       ```
     - On macOS/Linux:
       ```bash
       source chatbot/bin/activate
       ```
   - Install the required dependencies:
     ```bash
     pip install langchain langchain-ollama ollama
     ```

---

## How to Use

1. After completing the setup, run the chatbot script provided in this repository.
2. Interact with the chatbot, which will use Llama 3.2 to respond intelligently.
3. Type "quit" to exit the chatbot.

---
