<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,11,20,30&height=220&section=header&text=SHAIKH%20AKBAR%20ALI&fontSize=50&fontColor=ffffff&animation=fadeIn&subtext=AI%20Engineer%20%E2%80%A2%20LangGraph%20Multi-Agent%20%E2%80%A2%20Production%20Hybrid%20RAG&subfontSize=18&subfontColor=38bdf8" alt="Shaikh Akbar Ali - AI Systems Engineer" width="100%" />

<br/>

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=%E2%96%B8+LangGraph+Multi-Agent+Orchestration+%26+Supervision;%E2%96%B8+Production+Hybrid+RAG+(Dense+%2B+BM25+%2B+Cross-Encoder);%E2%96%B8+High-Concurrency+Async+FastAPI+%26+Docker+Microservices;%E2%96%B8+Deterministic+AI+Pipelines+with+Zero-Hallucination+Guarantees" alt="Typing SVG" />
</a>

<br/>

<p align="center">
  <a href="https://portfolio-liard-mu-5zv1yuvq8q.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/LIVE_PORTFOLIO-0284C7?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/shaikh-akbar-ali-a5b44128b" target="_blank">
    <img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:mimali31394@gmail.com">
    <img src="https://img.shields.io/badge/DIRECT_EMAIL-E11D48?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

</div>

---

### ⚡ Systems Engineering Philosophy

I engineer production-grade AI systems that bridge raw non-deterministic foundation models with deterministic software architecture. My core work focuses on **LangGraph state machines**, **hybrid dense/sparse retrieval engines**, and **containerized FastAPI backends** optimized for latency (p50/p95), token costs, and strict schema validation.

Actively open to **AI/ML & Generative AI Engineering opportunities** building scalable agentic systems.

```mermaid
flowchart LR
    A["💬 User Query<br><b>(Multimodal & Text)</b>"] --> B["🧠 LangGraph Router<br><b>(State-Graph Machine)</b>"]
    B --> C["⚡ Hybrid RAG Engine<br><b>(AstraDB + BM25 + RRF)</b>"]
    C --> D["🚀 FastAPI Core<br><b>(Dockerized Async Stream)</b>"]

    style A fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#f8fafc
    style B fill:#1e1b4b,stroke:#818cf8,stroke-width:2px,color:#f8fafc
    style C fill:#3b0764,stroke:#c084fc,stroke-width:2px,color:#f8fafc
    style D fill:#022c22,stroke:#34d399,stroke-width:2px,color:#f8fafc
```

---

### 🏛️ Flagship Production Architectures

<table>
  <thead>
    <tr>
      <th width="35%">System &amp; Focus</th>
      <th width="45%">Architecture &amp; Engineering Solution</th>
      <th width="20%">Deployments</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b>🛍️ Flipkart AI Shopping Assistant</b><br/>
        <sub>Multi-Agent Supervisor &amp; Hybrid RAG</sub><br/><br/>
        <img src="https://img.shields.io/badge/LangGraph-Router-818cf8?style=flat-square" alt="LangGraph" />
        <img src="https://img.shields.io/badge/AstraDB-Dense+BM25-38bdf8?style=flat-square" alt="AstraDB" />
        <img src="https://img.shields.io/badge/FastAPI-Docker-34d399?style=flat-square" alt="FastAPI" />
      </td>
      <td>
        • Architected a <b>multi-agent LangGraph supervisor</b> routing queries across 3 specialized sub-agents over 6 catalog domains.<br/>
        • Implemented <b>Reciprocal Rank Fusion (RRF)</b> uniting AstraDB dense embeddings with BM25 lexical search, reranked via cross-encoders to top-4.<br/>
        • Containerized FastAPI backend with token usage instrumentation and GitHub Actions CI/CD.
      </td>
      <td align="center">
        <a href="https://flipkart-ai-shopping-assistant.vercel.app/" target="_blank">
          <img src="https://img.shields.io/badge/Live_Demo-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" />
        </a><br/><br/>
        <a href="https://github.com/SHAIKH-AKBAR-ALI/flipkart-ai-shopping-assistant" target="_blank">
          <img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <b>✈️ FairFare Flight Agent</b><br/>
        <sub>ReAct Flight Agent &amp; ML Pricing Engine</sub><br/><br/>
        <img src="https://img.shields.io/badge/LangGraph-ReAct-818cf8?style=flat-square" alt="ReAct" />
        <img src="https://img.shields.io/badge/98.4%25-R²_Score-10b981?style=flat-square" alt="R2" />
        <img src="https://img.shields.io/badge/SHAP-Explainability-c084fc?style=flat-square" alt="SHAP" />
      </td>
      <td>
        • Autonomous <b>ReAct LangGraph agent</b> navigating live flight inventories and executing programmatic booking rule validations.<br/>
        • Trained predictive pricing model over <b>300K+ historical flight logs</b> (98.4% R², MAE ₹1,368) backed by real-time SHAP feature attribution.<br/>
        • Verified with automated Playwright end-to-end evaluation harness on Render cloud.
      </td>
      <td align="center">
        <a href="https://flight-predictor-v2-frontend.onrender.com/" target="_blank">
          <img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=render&logoColor=white" alt="Live Demo" />
        </a><br/><br/>
        <a href="https://github.com/SHAIKH-AKBAR-ALI/flight-predictor-v2" target="_blank">
          <img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🥗 MacroChat AI</b><br/>
        <sub>Multimodal Vision &amp; Zero-Hallucination RAG</sub><br/><br/>
        <img src="https://img.shields.io/badge/GPT--4o-Vision-a855f7?style=flat-square" alt="GPT-4o" />
        <img src="https://img.shields.io/badge/PostgreSQL-RLS-38bdf8?style=flat-square" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Zero-Hallucination-34d399?style=flat-square" alt="Zero Hallucination" />
      </td>
      <td>
        • Solved LLM nutritional inaccuracy by using <b>GPT-4o Vision purely for ingredient identification</b>, while resolving calories and macros deterministically via database lookups (1,014 Indian recipes + USDA).<br/>
        • Implemented dynamic BMR/TDEE calculation (Mifflin-St Jeor formula) inside PostgreSQL stored queries with Row Level Security (RLS).
      </td>
      <td align="center">
        <a href="https://macrochat-d6oi.onrender.com/" target="_blank">
          <img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=render&logoColor=white" alt="Live Demo" />
        </a><br/><br/>
        <a href="https://github.com/SHAIKH-AKBAR-ALI/macrochat-ai" target="_blank">
          <img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <b>🎙️ JARVIS Voice &amp; Task Agent</b><br/>
        <sub>Multi-Agent State Governance &amp; Long-Term Memory</sub><br/><br/>
        <img src="https://img.shields.io/badge/LangGraph-State_Machine-818cf8?style=flat-square" alt="LangGraph" />
        <img src="https://img.shields.io/badge/SQLite-Long_Term_Memory-f59e0b?style=flat-square" alt="Memory" />
        <img src="https://img.shields.io/badge/Dockerized-Compose-2496ed?style=flat-square" alt="Docker" />
      </td>
      <td>
        • Modular conversational agent with multi-modal voice processing, asynchronous task execution, and SQLite checkpoint state memory.<br/>
        • Integrated tool calling for system operations, calendar scheduling, and automated information retrieval with Docker Compose deployment.
      </td>
      <td align="center">
        <a href="https://github.com/SHAIKH-AKBAR-ALI/jarvis-assistant" target="_blank">
          <img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo" />
        </a>
      </td>
    </tr>
  </tbody>
</table>

---

### 🛠️ Production Technology Stack

#### 🧠 Agentic AI, LLMOps & Retrieval
<p align="left">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Hybrid_RAG_(RRF)-1D4ED8?style=for-the-badge&logoColor=white" alt="Hybrid RAG" />
  <img src="https://img.shields.io/badge/Cross--Encoder_Rerank-4338CA?style=for-the-badge&logoColor=white" alt="Reranker" />
  <img src="https://img.shields.io/badge/AstraDB-000000?style=for-the-badge&logoColor=white" alt="AstraDB" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/Groq_(Llama_3.3)-F05A28?style=for-the-badge&logo=meta&logoColor=white" alt="Llama 3" />
  <img src="https://img.shields.io/badge/OpenAI_GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white" alt="GPT-4o" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace" />
</p>

#### ⚡ Backend Microservices, Cloud & Databases
<p align="left">
  <img src="https://img.shields.io/badge/Python_3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Playwright_E2E-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI/CD" />
  <img src="https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white" alt="Render" />
</p>

#### 🔬 Core Machine Learning & Data Science
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/SHAP_(XAI)-581C87?style=for-the-badge&logoColor=white" alt="SHAP" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
</p>

---

<div align="center">
  <p align="center">
    <b>📍 Mumbai, Maharashtra, India</b> &nbsp;•&nbsp; 
    <a href="https://portfolio-liard-mu-5zv1yuvq8q.vercel.app/">portfolio-liard-mu-5zv1yuvq8q.vercel.app</a> &nbsp;•&nbsp; 
    <a href="mailto:mimali31394@gmail.com">mimali31394@gmail.com</a>
  </p>
  <p align="center">
    <i>"Designing deterministic, agentic AI pipelines that bridge raw foundation models with enterprise execution."</i>
  </p>
</div>
