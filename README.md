# Web-Search-Only Knowledge Graphs (research)

This repository contains code and notebooks for building a web-search-assembled knowledge graph to reduce LLM hallucinations.

Quick Git steps (first time):
1. git init
2. git add .
3. git commit -m "Initial commit"
4. git remote add origin <your-repo-ssh-or-https-url>
5. git branch -M main
6. git push -u origin main

Notes:
- Keep API keys and secrets in a .env file (already in .gitignore).
- Large caches/models (.pkl, faiss indices, datasets) are ignored by .gitignore.
- Add a `requirements.txt` describing Python dependencies before CI runs.
