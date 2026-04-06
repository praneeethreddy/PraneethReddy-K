<h1 align="center">Hi 👋, I'm Praneeth</h1>
<h3 align="center">Generative AI Engineer | LLM Systems Architect | Multi-Agent Workflow Builder</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=20&pause=1000&color=238636&center=true&vCenter=true&width=600&lines=Building+Production+Grade+AI+Systems;LLM+Orchestration+%7C+RAG+%7C+Agents;Scalable+Backend+%7C+AI+Infrastructure;Cloud+Native+AI+Solutions" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/praneethkesarapu1906">
    <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://praneethreddy.netlify.app">
    <img src="https://img.shields.io/badge/PORTFOLIO-111827?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  </a>
  <a href="mailto:reddypraneeth066@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## 🛠️ GenAI Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangGraph-FF5722?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LlamaIndex-6B21A8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AutoGen-0078D4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MCP-Context%20Protocol-7952B3?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RAG-Vector%20Search-0052CC?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Anthropic%20Claude-D97706?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure%20OpenAI-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
</p>

---

## 🧠 About Me

- 🔭 I build production-grade Generative AI systems using LLMs, RAG pipelines, and agent frameworks  
- 🧩 Strong experience in designing scalable AI architectures for real-world enterprise use cases  
- ⚙️ Specializing in LangChain, LangGraph, LLM orchestration, and vector databases  
- ☁️ Experience deploying AI systems on AWS, Azure & GCP with containerized microservices  
- 🚀 Focused on building fast, reliable, and cost-efficient AI systems  

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | Python, SQL, Bash |
| **LLMs** | GPT-4, Claude, Gemini, LLaMA, Mistral, DeepSeek |
| **LLM Frameworks** | LangChain, LangGraph, LlamaIndex, AutoGen, LangSmith |
| **RAG & Vector DBs** | Pinecone, FAISS, ChromaDB, Weaviate, HyDE, CRAG |
| **Fine-Tuning** | LoRA, QLoRA, PEFT, Hugging Face Transformers |
| **Cloud & MLOps** | AWS Bedrock, Azure OpenAI, GCP Vertex AI, Docker, MLflow |
| **Backend** | FastAPI, Flask |

---

## 🧩 Multi-Agent LLM Orchestration Architecture

```mermaid
flowchart LR

A[User Query] --> B[LangGraph Orchestrator]

B --> C1[Planner Agent - Reasoning / Decomposition]
B --> C2[Tool Agent - API / DB / Search]
B --> C3[Retriever Agent - RAG / Vector DB]

C1 --> D[Action Decision Node]
C2 --> D
C3 --> D

D --> E[Observation Collector]

E --> B

B --> F[Final Response Generator]
F --> G[User Output]

subgraph MCP_LAYER [MCP Tooling Layer]
  H[MCP Server - Tool Registry]
  I[External APIs / Databases / Services]
  H --> I
end

C2 --> MCP_LAYER
C3 --> MCP_LAYER
```

---

## 🔌 MCP (Model Context Protocol) Architecture

> MCP is an open standard by Anthropic that allows AI models to securely connect to external tools, data sources, and services through a unified protocol layer — replacing fragmented custom integrations with one standard.

```mermaid
flowchart TD

A[AI Application / LLM Host] -->|MCP Client| B[MCP Protocol Layer]

B --> C1[MCP Server 1 - File System]
B --> C2[MCP Server 2 - Databases]
B --> C3[MCP Server 3 - REST APIs]
B --> C4[MCP Server 4 - Web Search]

subgraph RESOURCES [Resources Exposed via MCP]
  C1 --> R1[Read / Write Files]
  C2 --> R2[Query PostgreSQL / MongoDB]
  C3 --> R3[Call External Services]
  C4 --> R4[Live Web Data]
end

subgraph PROTOCOL [MCP Protocol Features]
  P1[Tool Definitions]
  P2[Prompt Templates]
  P3[Resource URIs]
  P4[Sampling Requests]
end

B --> PROTOCOL
```

---

## 🚀 Featured Projects

### 🔹 AI Chatbot with RAG (LangChain + Vector DB)
- Built a contextual chatbot using retrieval-augmented generation
- Implemented memory handling and document embeddings
- Reduced hallucination using hybrid search strategy

### 🔹 Local Knowledge Base Assistant
- Chat with your own documents using embeddings + vector search
- Integrated ChromaDB for persistent storage

### 🔹 Multi-Agent AI System
- Designed orchestration layer for multiple LLM agents
- Task decomposition + tool-based execution pipeline

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=praneethkesarapu1906&show_icons=true&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=praneethkesarapu1906&theme=radical" />
</p>

---

## 🧩 Key Strengths

- Building **end-to-end AI products**, not just models  
- Strong focus on **real-world scalability & cost optimization**
- Experience in **LLM system design & orchestration**
- Ability to bridge **backend engineering + AI research concepts**
- Up-to-date with **MCP, agentic frameworks & frontier LLMs**

---

<p align="center">
  ⚡ "I don't just use AI models — I build systems around them that solve real problems."
</p>
