# LangGraph AI Agent Workflows

This repository demonstrates how to build **stateful, resilient, and modular AI agent workflows** using the [LangGraph](https://www.langgraph.dev/) framework, integrated with LangChain, Gemini 1.5, Hugging Face embeddings, and Chroma vector stores.

## 🔍 Project Overview

The notebook in this repository walks through:
- Using **Google Gemini 1.5 Flash** as a conversational model
- Configuring **HuggingFace Embeddings** (`BAAI/bge-small-en`)
- Loading and chunking text documents using LangChain loaders
- Storing semantic vectors in **Chroma DB**
- Designing a **state-driven agent workflow** inspired by LangGraph’s node-and-edge paradigm
- Implementing simple **Pydantic-based state simulation** to mimic LangGraph's execution pattern

## 📘 Key Concepts Learned

- How to build a RAG (Retrieval-Augmented Generation) pipeline
- How to simulate agent state transitions using functional logic
- Embedding and storing documents in a vector database
- The importance of state checkpoints, memory, and modular agent design

## 📁 Repository Structure

```bash
.
├── langgraph_class2.ipynb    # Jupyter notebook with full implementation
├── data2/                    # Folder to hold input `.txt` files for embeddings
└── README.md                 # This file
````

## 🚀 Use Cases and Future Scope

With this foundational setup, you can extend the project to:

* Build **multi-agent systems** for customer support, document analysis, or workflow automation
* Integrate **human-in-the-loop decision-making**
* Add memory, feedback loops, and guardrails for **production-ready GenAI applications**
* Visualize agent execution using LangGraph’s tools

## 🔧 Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/vummanenidilip/Langgraph.git
cd Langgraph
```

2. Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

> You may need API keys for Gemini, Hugging Face, or OpenAI depending on your environment.

3. Run the notebook:
   Open `Supervisor Node.ipynb` in Jupyter or VS Code to explore and execute the steps.

