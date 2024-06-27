# Llama2 Chatbot using LangChain and Streamlit

## Project Overview

This project demonstrates a chatbot implementation using the Llama2 model with the LangChain framework. The chatbot is designed to interact with users by processing their queries and generating responses using a defined prompt template.

## Features

- **Prompt Template:** Defines a conversation template where the system provides a guiding context and the user input is processed to generate responses.
- **LangChain Integration:** Utilizes LangChain to create a structured workflow involving prompts, the Llama2 language model, and output parsing.
- **Streamlit Interface:** Provides a user-friendly interface for interacting with the chatbot.
- **Ollama Integration:** Retrieves the Llama2 model from Ollama for response generation.

## Key Achievements

- Developed a functional chatbot that uses a structured prompt template to generate responses.
- Integrated LangChain framework to manage the interaction between the prompt template and the Llama2 model.
- Created a simple and intuitive user interface using Streamlit for querying the chatbot.
- Utilized Ollama to retrieve and use the Llama2 model.

## Project Workflow

1. **Prompt Template:**
   - The chatbot uses a prompt template that defines the system's role and how it should respond to user queries.

2. **LangChain Core Integration:**
   - The project imports necessary modules from `langchain_core` and `langchain_community` to set up the prompt template and connect it with the Llama2 model from Ollama.

3. **Streamlit Interface:**
   - Streamlit is used to create a web interface where users can input their queries and view the chatbot's responses.

 **Download Ollama and Llama2 Model:**
   - Install Ollama by following the instructions on their [official website](https://ollama.com/).
   - Download the Llama2 model using Ollama:
     ```sh
     ollama run llama2
     ```

## Technologies Used

- **LangChain:** For defining the prompt template and integrating with the Llama2 model.
- **Llama2:** The language model used for generating responses.
- **Streamlit:** For creating an interactive web interface.
- **Ollama:** For downloading and managing the Llama2 model.
- **dotenv:** For managing environment variables securely.

## Contact


For any questions or suggestions, please contact [gowthamdupati28@gmail.com](mailto:gowthamdupati28@gmail.com).
