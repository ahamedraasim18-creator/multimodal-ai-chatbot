# Nullclass-intrenship-Task1
Auto Knowledge Base Updater using Langch🧠 Auto Knowledge Base Updater using LangChain & ChromaDB

This project implements an automated knowledge base update system that fetches data from online sources, processes it, embeds it, and stores it inside a vector database (Chroma DB).
It is part of the Nullclass Gen AI Internship – Task 1.

⭐ Project Overview

The goal of this project is to:

Fetch news/updates from specified URLs

Convert raw webpage content into meaningful text chunks

Generate vector embeddings using OpenAI embeddings

Store the chunks inside ChromaDB

Auto-update the knowledge base whenever new content arrives

Perform similarity search for question answering


ain,chromaDB,openAI 

  📁 Nullclass-Task1
│
├── Nullclass_Task1_KnowledgeBase_Update.ipynb   # Main notebook
├── README.md                                     # Project documentation
└── knowledge_db/                                 # Vector DB (auto-created)


---

🛠 Technologies Used

Component	Library

Web scraping	langchain_community.document_loaders.WebBaseLoader
Text chunking	RecursiveCharacterTextSplitter
Embeddings	OpenAIEmbeddings
Vector database	ChromaDB
Programming	Python
Notebook	Jupyter / Google Colab



---

🚀 Features Implemented

✔ Web data extraction

Extracts text from websites dynamically.

✔ Preprocessing & chunking


ip install langchain langchain-community langchain-openai chromadb tiktoken

2. Add Your OpenAI API Key

Inside the notebook:

OPENAI_API_KEY = "your_api_key_here"

3. Add Your Data Sources

SOURCES = [
    "https://example.com/news",
    "https://example.com/updates"
]

Open → Run all cells → DB gets updated.


---

🧪 Sample Query

query = "What are today's latest updates?"
results = db.similarity_search(query, k=3)


---🎯 Output

Clean and processed text

Embeddings stored in Chroma DB

Auto-updated knowledge base

Query responses using similarity search




NAME:AHAMED RAASIM A.B 
INTERNSHIP:NULLCLASS GEN AI
TASK 1:KNOWLEDGE BASE AUTO UPDATER






