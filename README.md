# Chat with SQL DB with Langchain SQL Toolkit and Agent type

This project is a Streamlit application that enables users to interact with SQL databases (SQLite or MySQL) using natural language through a chatbot interface. It utilizes LangChain's SQL toolkit, the Groq LLM (`Llama3-8b-8192`), and the `ZERO_SHOT_REACT_DESCRIPTION` agent type for interpreting and executing queries.

## Features

- Chat-based interface for database interaction
- Supports both SQLite (local `student.db`) and MySQL databases
- Uses LangChain's `SQLDatabaseToolkit` and Groq's Llama3 model
- Maintains chat history using Streamlit session state
- Allows real-time LLM streaming with callback support
- Option to clear previous chat history
