# 🔍 **Search Engine with Tools & Agents**

<div align="center">

✨ *A powerful search engine built using LangChain Tools, Groq LLaMA, and HuggingFace Embeddings* ✨  
Search • Fetch • Process • Answer — all through intelligent agents

---

### 🚀 **Wikipedia** • 📄 **ArXiv** • 🌐 Custom Web Loader + Retriever • 🦙 Groq LLaMA • 🔡 HuggingFace Embeddings

![Static Badge](https://img.shields.io/badge/Python-3.10+-blue)
![Static Badge](https://img.shields.io/badge/LangChain-Framework-orange)
![Static Badge](https://img.shields.io/badge/Groq-LLaMA-green)
![Static Badge](https://img.shields.io/badge/HuggingFace-Embeddings-yellow)
![Static Badge](https://img.shields.io/badge/Status-Active-brightgreen)

🔗 **GitHub Repository:**  
https://github.com/kirantushar10/Search-Engine-with-Tools-and-Agents

</div>

---

## 🌟 **Overview**

This project showcases a **search engine powered by intelligent tools and agents**, built using:

- 🦙 **Groq LLaMA Model** for fast, accurate reasoning  
- 🔡 **HuggingFace Embeddings** for vector search  
- ⚙️ **LangChain Tools + Agents** for smart orchestration  

The system can search across Wikipedia, ArXiv, and any webpage using a custom loader and retriever.

---

## 🧰 **Tools Used**

### 1️⃣ Wikipedia Tool  
Fetches instant, high-level information from Wikipedia.

### 2️⃣ ArXiv Tool  
Retrieves scientific papers, abstracts, categories, and metadata.

### 3️⃣ 🌐 Custom Web Loader Tool (Retriever-Based)  
A custom search tool built using:

- **WebBaseLoader** → Loads any webpage  
- **RecursiveCharacterTextSplitter** → Breaks content into chunks  
- **HuggingFace Embeddings** → Converts chunks into vector embeddings  
- **Retriever** → Enables semantic, search-engine-style querying  

This converts any webpage into a **mini search engine**, allowing the LLaMA agent to pull relevant info.

---

## ✨ **Key Features**

✔️ Intelligent agent-powered search  
✔️ Wikipedia + ArXiv + Web scraping tools  
✔️ Retriever-based semantic search  
✔️ Uses Groq LLaMA for ultra-fast inference  
✔️ HuggingFace embedding integration  
✔️ Smart text chunking  
✔️ No OpenAI required  
✔️ Runs entirely through LangChain  

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
pip install -r requirements.txt
```

---

## 📁 Project Structure

```bash
├── tools_agents.ipynb      # Main notebook demonstration
├── README.md               # Project documentation
├── requirements.txt        # Dependencies
└── .env                    # API keys for Groq + HuggingFace
```
