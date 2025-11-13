# 🔍 **Search Engine with Tools and Agents**

<div align="center">

✨ *A powerful search engine built using LangChain Tools, Groq LLaMA, HuggingFace Embeddings, and LangSmith Tracking* ✨  
Search • Fetch • Process • Trace — all through intelligent agents

---

### 🚀 **Wikipedia** • 📄 **ArXiv** • 🌐 Custom Web Loader + Retriever • 🦙 Groq LLaMA • 🔡 HuggingFace Embeddings • 📊 LangSmith Monitoring

![Static Badge](https://img.shields.io/badge/Python-3.10+-blue)
![Static Badge](https://img.shields.io/badge/LangChain-Framework-orange)
![Static Badge](https://img.shields.io/badge/Groq-LLaMA-green)
![Static Badge](https://img.shields.io/badge/HuggingFace-Embeddings-yellow)
![Static Badge](https://img.shields.io/badge/LangSmith-Tracking-purple)
![Static Badge](https://img.shields.io/badge/Status-Active-brightgreen)

🔗 **GitHub Repository:**  
https://github.com/kirantushar10/Search-Engine-with-Tools-and-Agents

</div>

---

## 🌟 **Overview**

This project demonstrates a **search engine powered by intelligent tools and agents**, built using:

- 🦙 **Groq LLaMA** for fast and accurate inference  
- 🔡 **HuggingFace Embeddings** for vector search  
- ⚙️ **LangChain Tools + Agents** for orchestrating tool use  
- 📊 **LangSmith** for tracking, debugging, and monitoring agent runs  

The system can search across Wikipedia, ArXiv, and any webpage using a retriever-based custom web tool.

---

## 🧰 **Tools Used**

### 1️⃣ Wikipedia Tool  
Fetches quick, general knowledge information from Wikipedia.

### 2️⃣ ArXiv Tool  
Retrieves scientific papers, abstracts, and categories from the ArXiv database.

### 3️⃣ 🌐 Custom Web Loader Tool (Retriever-Based)  
Built using:

- **WebBaseLoader** → Imports webpage content  
- **RecursiveCharacterTextSplitter** → Breaks content into manageable chunks  
- **HuggingFace Embeddings** → Converts text chunks into vector embeddings  
- **Retriever** → Enables semantic search over webpage content  

This creates a mini search engine from any webpage.

---

## 📊 **LangSmith Tracking**

This project uses **LangSmith** to:

- Track agent execution  
- Debug tool usage  
- Visualize model reasoning  
- Monitor performance & latency  
- Store traces for experimentation  

Adding LangSmith makes the workflow transparent and easy to optimize.

---

## ✨ **Key Features**

✔️ Agent-powered multi-source search  
✔️ Wikipedia, ArXiv, and web scraping support  
✔️ Retriever-based semantic search  
✔️ Groq LLaMA inference for fast responses  
✔️ HuggingFace Embeddings for vector search  
✔️ LangSmith monitoring & tracing  
✔️ Full LangChain integration  
✔️ No OpenAI required  

---

## 📦 **Installation**

### 1️⃣ Clone the repository

```bash
git clone https://github.com/kirantushar10/Search-Engine-with-Tools-and-Agents.git
cd Search-Engine-with-Tools-and-Agents
```

### 2️⃣ Install all dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Add your API keys

Add them to the .env file:

```bash
LANGCHAIN_API_KEY = "Add your Langchain API key here"
LANGCHAIN_PROJECT = "Search Engine With Tools And Agents"
HF_TOKEN = "Add your Hugging Face API key here"
GROQ_API_KEY = "Add your Groq API key here"
```

---

## 📁 Project Structure

```bash
├── tools_agents.ipynb      # Main notebook demonstration
├── README.md               # Project documentation
├── requirements.txt        # Dependencies
└── .env                    # API keys for Groq + HuggingFace
```

---

## 🧠 How the Search Engine Works

### 📚 Wikipedia Tool

Provides encyclopedia-style information instantly.

### 📄 ArXiv Tool

Helps users search for scientific papers and abstracts.

### 🌐 Custom Web Loader Tool

Transforms any webpage into a searchable space:

- Loads webpage using WebBaseLoader

- Splits text into chunks

- Embeds chunks using HuggingFace models

- Creates a retriever

- Agent queries the retriever to find relevant information

### 🦙 Groq LLaMA Model

Serves as the AI reasoning engine:

- Determines which tool to use

- Interprets retriever outputs

- Generates the final answers

### 📊 LangSmith

Monitors and visualizes the complete workflow:

- Tool calls

- Agent reasoning steps

- Latency

- Model inputs/outputs
