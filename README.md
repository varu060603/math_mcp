# Math MCP Toolkit

This repository contains a Math MCP Toolkit that is used by a LangChain agent powered by a Groq LLM.

## 🧪 How to Run

### 1. Start the MCP Server

Open a terminal and run:

```bash
python server.py
```

> Note: The terminal will appear stuck — this is expected. The server is running and waiting for client connections.

---

### 2. Run the Client Agent

Open **another terminal** and run:

```bash
python client.py
```

> ⚠️ Don’t forget to **paste your Groq API key** in the `client.py` file before running it:

```python
groq_api_key = "YOUR_GROQ_API_KEY"
```

---

That's it! Your Math MCP Toolkit with a LangChain + Groq-powered agent should now be running.
```
