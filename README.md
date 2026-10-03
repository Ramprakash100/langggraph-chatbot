# 🤖 Basic Chatbot with LangGraph (Graph API)

A simple conversational chatbot built using **LangGraph** and Python. This project demonstrates how to create a basic chatbot workflow using graph-based execution, state management, nodes, edges, and a language model.

## 🚀 Features

- 💬 Interactive conversational chatbot
- 🔄 Graph-based workflow using LangGraph
- 🧠 State management for handling messages
- 🔗 Nodes and edges to define the chatbot workflow
- 🤖 Integration with a language model
- 🐍 Python-based implementation

## 🛠️ Technologies Used

- **Python**
- **LangGraph**
- **LangChain**
- **LLM Provider** (depending on your implementation)
- **Jupyter Notebook**

## 📁 Project Structure

```text
1-BasicChatBot/
├── basicChatbot.ipynb
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Ramprakash100/langgggraph-chatbot.git
cd langgggraph-chatbot
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install langgraph langchain
```

Install any additional model-provider package required by your notebook.

### 4. Configure API credentials

If your chatbot uses a cloud-based language model, configure the required API key as an environment variable or in a local `.env` file.

**Important:** Never commit API keys or your `.env` file to GitHub.

### 5. Run the notebook

Open `1-BasicChatBot/basicChatbot.ipynb` in Jupyter Notebook or VS Code and execute the cells in order.

## 🔍 How It Works

1. **Define the state:** Store the conversation messages.
2. **Create nodes:** Define the chatbot's processing logic and language-model call.
3. **Connect edges:** Specify the execution flow between nodes.
4. **Build the graph:** Compile the workflow using LangGraph.
5. **Invoke the chatbot:** Send a user message to the graph and receive a response.

## 📚 Learning Objectives

This project helps demonstrate the fundamentals of LangGraph, including:

- Graph-based workflow design
- State and message management
- Nodes and edges
- Graph compilation and invocation
- Building blocks for more advanced AI agents

## 🔮 Future Improvements

- Add conversation memory across multiple interactions
- Build a Streamlit chat interface
- Add support for different language models
- Implement streaming responses
- Add tools and conditional routing

## 👨‍💻 Author

**Ramprakash V.**

GitHub: [Ramprakash100](https://github.com/Ramprakash100)

---

⭐ If you find this project useful, consider giving the repository a star!
