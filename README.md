# 📘 Web-Search-Only Knowledge Graphs (research)

A modular Python framework for constructing real-time Knowledge Graphs directly from web search results.
The system performs automated retrieval, information extraction, graph construction, and merging — enabling reusable, provenance-aware knowledge that can support LLM reasoning.

--- 

# 🚀 Features

- 🔍 Live **web retrieval** with query expansion + content filtering  
- 🧠 **Entity and relation extraction** using NLP  
- 🕸️ **Dynamic Knowledge Graph construction** (NetworkX)  
- ♻️ **Graph merging and reuse** via confidence-weighted alignment  
- 📌 **Provenance tracking** for every fact  
- ⚡ **Local caching** for faster repeated queries  
- 🧪 **Evaluation tools** for hallucination measurement  
- 🔐 API-safe environment setup via `.env`

---

# 📁 Repository Structure
```
WCKG-WebConstructed-KnowledgeGraph/
│
├── Web-Search-Only Knowledge Graphs.ipynb      # Notebook
├── .env.example                                # Template for environment keys
├── .gitignore                                  # Ignoring caches, models, outputs
├── requirements.txt                            # Python dependencies
└── README.md                                   # Documentation
```

---

# 🛠️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/DurveshN/WCKG-WebConstructed-KnowledgeGraph
cd WCKG-WebConstructed-KnowledgeGraph
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Prepare environment variables
Create a .env file based on .env.example:
```ini
SEARCH_API_KEY=your_key_here
OPENROUTER_API_KEY=your_key_here
```

### 4. Use Jupyter Notebook
Open the main prototype notebook:
```bash
jupyter notebook
```

Notes:
- Keep API keys and secrets in a .env file (already in .gitignore).
- Large caches/models (.pkl, faiss indices, datasets) are ignored by .gitignore.
- Add a `requirements.txt` describing Python dependencies before CI runs.
