# Augmenting LLM capabilities using mcp-use
This repository demonstrates augmenting LLMs with external knowledge through multiple MCP servers using mcp-use   

## Software Stack   
OS: Windows 11   
Python: 3.12   
IDE: Cursor   
LangChain-Groq   
LangChain-OpenAI   
mcp-use   

## Installation  
```
uv init <project_name>
uv venv --python 3.12
.venv\Scripts\activate
uv add langchain-groq
uv add langchain-openai
uv add mcp-use
```

## Verifying MCP Tools in Cursor   
![image](https://github.com/user-attachments/assets/e4a8bd53-2aed-46d8-a5d2-0a234b4cab8d)   
![image](https://github.com/user-attachments/assets/d50b6e7b-cbf1-4d66-815e-2d57b2a1b206)

## Verifying Agents Response in Cursor 
![image](https://github.com/user-attachments/assets/62088ba9-4f02-4563-b107-17df50d31896)   

## Running Application   
```
set GROQ_API_KEY=<GROQ_API_KEY>
uv run app.py
```
