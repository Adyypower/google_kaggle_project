Deep Research & RAG Optimization Multi-Agent System
Powered by LangGraph • Gemini • ChromaDB • DuckDuckGo Search
(With Video Demonstration Included)

📌 Overview

This project is a Multi-Agent Research System designed to perform:

🔹 1. Deep Research (DRT Mode)

Automatically conducts:

Theoretical research using Gemini 2.5

Real-time web search using DuckDuckGo

Multi-agent synthesis to combine theory + web evidence

Produces a clean, academic-style answer

🔹 2. RAG Mode (Retrieval Augmented Generation)

Allows users to upload PDF / TXT documents and performs:

Text extraction

Chunking

Vector embedding using HuggingFace MiniLM embeddings

Storage in Chroma Vector Database

Intelligent retrieval

Gemini answers strictly based on document context

🎯 Purpose of This Project

This system is built to help users:

✔ Perform deep theoretical research
✔ Validate information with live internet results
✔ Query large documents efficiently
✔ Ensure answers are grounded in the right context
✔ Demonstrate advanced multi-agent workflows for AI applications

It is ideal for:

Students

Researchers

Engineers

Competitive coding / hackathon judge evaluation

Anyone needing combined research + document understanding

🧩 Architecture

The system uses two LangGraph pipelines:

🔸 Research Graph
Research Node → Web Search Node → Synthesizer Node → Saver

🔸 RAG Graph
Document Retriever → Context Generator → Final Answer → Saver


Each run is logged and can be exported in Markdown format.

🛠️ Technologies Used

LangGraph – multi-agent state machine

Gemini 2.5 – LLM for reasoning, research, and synthesis

ChromaDB – vector storage for document retrieval

DuckDuckGo Search API – real-time web results

HuggingFace Sentence-Transformers – embeddings (MiniLM-L6-v2)

PyPDFLoader – document loading

Gradio – simple UI

🚀 Features
✔ Deep Research Agent

Provides structured theoretical explanation

Performs web search

Merges both sources

Produces final academic-style output

✔ RAG Document Agent

Upload your own PDF or TXT

Automatically indexed into vector DB

Ask any question grounded in your document

Zero hallucination behavior

✔ Beautiful Export

Session automatically saved

Export as Markdown with timestamps

Perfect for documentation and reports

📹 Video Demonstration

A full walkthrough video of the tool is included in this repository.
The video covers:

What DIRT/DRT is

How the system works internally

Execution flow of both Research and RAG

Live results

Exporting chat history

📁 Project Structure
├── app.py / notebook.ipynb      # Main code
├── utils/                       # Optional helper modules
├── chroma_rag/                  # Chroma vector database
├── Session_Log_xx.md            # Auto-generated logs
└── README.md                    # Project explainer

▶️ Running the Project
pip install -r requirements.txt
python app.py


Or run directly in Google Colab.

📌 Why This Project Is Unique

This is not a simple chatbot.
It is a true multi-agent system with:

Independent reasoning agents

Decision pipelines

Context-grounded generation

Live web search

Full LangGraph integration

Exportable interaction memory

It demonstrates real engineering skills in AI, RAG, and multi-agent systems.

👨‍💻 Author

Aditya Kumar
B.Tech CSE | AI & ML Enthusiast
Passionate about agentic systems, RAG models, and practical AI engineering.

⭐ If you liked this project

Please give a ⭐ on GitHub and connect with me!
