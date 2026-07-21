
*AI-Multi-Agent-RAG-System*

Overview:
This platform orchestrates specialized AI agents using LangGraph to process enterprise documents, perform deep semantic retrieval via ChromaDB, cross-validate findings, and execute external actions. Built with a high-performance FastAPI backend and a responsive Next.js frontend, it bridges the gap between static knowledge bases and active, tool-using enterprise workflows.

⚙️ Key Features:
- Multi-Agent Orchestration: Powered by LangGraph to manage state, routing, and collaboration between specialized agents (Research, Validation, Execution).
- Advanced RAG Pipeline: Secure document ingestion, chunking, and vector embedding stored in ChromaDB for lightning-fast semantic retrieval.
- Cross-Validation Engine: Multi-step verification checks agent outputs against source documents to drastically reduce hallucinations.
- Modern Enterprise Stack: Asynchronous FastAPI backend coupled with a sleek Next.js dashboard.
- Real-World Tool Integration: Agents can autonomously execute tasks using integrated capabilities:

🌐 Web Search (Live data fetching)
📧 Email (Automated notifications and drafting)
🐙 GitHub (Issue tracking, PR insights, and repo analysis)
💻 Code Execution (Safe sandbox environment for data analysis and scripting)
🎨 Image Generation (Visual asset creation on demand)

⚙️ Prerequisites:
Python 3.10+
Node.js 18+
Docker & Docker Compose (Recommended for seamless setup)
API Keys for your preferred LLM provider (e.g., GeminiAPI,GrokAPI, OpenAI) and tool integrations (GitHub, Search APIs, etc.).

⚙️ Usage: 
- Ingest Documents: Navigate to the Document Manager in the Next.js UI to upload PDFs, TXT, or Markdown enterprise documents. They are automatically chunked, embedded, and  indexed into ChromaDB.
- Interact with Agents: Use the chat interface to query your data. The LangGraph supervisor will route your request to the appropriate specialized agents.
- Execute Actions: Ask agents to perform complex workflows
