GenAI-SQL-Chat-Agent

A Streamlit-based GenAI application that enables users to interact with SQL databases using natural language. The system translates user questions into SQL queries, executes them securely, and returns accurate, human-readable responses in real time.

Overview

This project demonstrates how large language models can be combined with database toolkits to create an intelligent conversational interface for structured data. Users can ask questions in plain English and receive insights directly from relational databases without writing SQL manually.

Key Features

• Natural language to SQL query generation
• Supports both SQLite and MySQL databases
• LangChain SQL Agent with tool-based reasoning
• Real-time query execution and response streaming
• Live agent reasoning visualization in the UI
• Interactive chat-based Streamlit interface
• Secure, read-only database access

How It Works

The application connects to a selected SQL database and exposes it to a LangChain SQL agent.
User questions are interpreted by a Groq-hosted LLM, which decides the required SQL operations.
The agent generates optimized SQL queries, executes them against the database, and converts results into clear natural language responses.
All interactions happen through a conversational chat interface.

Technologies Used

Streamlit for interactive UI
LangChain SQL Agents for query orchestration
Groq LLMs (Llama 3) for reasoning and SQL generation
SQLite and MySQL for relational data storage
SQLAlchemy for database connectivity

Use Cases

Business analytics and reporting
Database exploration without SQL knowledge
Internal data querying for non-technical users
Rapid prototyping of AI-powered database assistants
Educational demos for NL-to-SQL systems

Project Highlights

This project showcases a practical implementation of agentic AI for structured data interaction.
It demonstrates zero-shot reasoning, tool usage, and safe database querying using modern LLM frameworks.
Designed with extensibility in mind, it can be adapted to enterprise-scale databases and workflows.
