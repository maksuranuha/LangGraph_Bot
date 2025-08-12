# LangGraph
Simple Chatbot using LangGraph, LangSmith, and LLMs

This is a minimal yet extensible chatbot built with LangGraph and LangSmith, designed for experimenting with large language models (LLMs).
By default, it uses gemma2-9b-it via Groq API, but you can easily switch to any other supported LLM (e.g., OpenAI, Anthropic, HuggingFace) by modifying the llm configuration:

llm = ChatGroq(groq_api_key=groq_api_key, model_name="gemma2-9b-it")

This project is ideal for beginners looking to understand how LLM orchestration works with LangGraph, and how to track experiments and debug via LangSmith.
