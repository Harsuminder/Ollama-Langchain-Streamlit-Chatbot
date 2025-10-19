# Ollama-Langchain-Streamlit-LangSmith-Chatbot (Gemma 2B)

This project is a small demo that connects **LangChain**, **Ollama**, and **Streamlit** into a simple local chatbot powered by the **Gemma 2B** model.  
All model interactions are tracked and visualized in **LangSmith**, so you can see every step; prompt, model input, output, and timing right in your LangSmith dashboard.

---

## 💡 What this project does

- Provides a clean **Streamlit web UI** to ask questions  
- Uses **Ollama** to run the **Gemma 2B** model locally, no API costs or external calls  
- Tracks all requests and responses in **LangSmith** for visibility and debugging  
- Demonstrates a minimal but complete LangChain pipeline:
