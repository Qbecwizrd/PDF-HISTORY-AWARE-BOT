# PDF-HISTORY-AWARE-BOT

🧠 Conversational RAG Chatbot with PDF Uploads (Streamlit)
A minimal, memory-aware conversational assistant built with LangChain, powered by Groq LLMs, and enriched with semantic search using Hugging Face embeddings and ChromaDB. This app allows users to upload PDFs, ask context-aware questions, and receive concise answers — all within a clean Streamlit interface.

🚀 Features
📄 Upload and process multiple PDF documents

🧠 Conversational interface with session-based memory

🔎 Semantic document retrieval using Chroma and HuggingFace embeddings

🤖 LLM-powered QA via Groq (supports models like mixtral-8x7b-32768, llama2-70b-4096)

🛡️ API key authentication via input

💬 Real-time chat with history awareness and document grounding

🧾 Chat history is preserved per session for seamless multi-turn interactions

📦 Tech Stack
Streamlit – UI

LangChain – chaining and orchestration

Groq – LLM inference

Hugging Face Transformers – embeddings

ChromaDB – vector store for document chunks

Python-dotenv – secrets handling

PyPDFLoader – PDF content ingestion

📁 Example Use Cases
🧑‍🎓 Personal Study Assistant (upload course notes and ask questions)

🧑‍💼 Business Document Q&A (analyze reports, policies)

📚 Research Companion (converse with papers, legal texts)

🧪 Getting Started
bash
Copy
Edit
git clone https://github.com/<your-username>/<your-repo-name>
cd <your-repo-name>
pip install -r requirements.txt
streamlit run app.py
🔑 Add your .env file with your Hugging Face token
🔐 Enter your Groq API key in the app when prompted
