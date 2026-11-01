<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:2e1065,100:0e7490&height=230&section=header&text=Harshil%20Kaneria&fontSize=62&fontColor=E9D5FF&animation=fadeIn&fontAlignY=36&desc=Agentic%20AI%20Engineer%20%C2%B7%20Multi-Agent%20Systems%20%C2%B7%20RAG%20%C2%B7%20LLM%20Evals&descAlignY=56&descSize=18&descColor=A5F3FC"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3500&pause=900&color=A78BFA&center=true&vCenter=true&width=780&lines=I+build+agents+that+ship+to+production;Agents+that+falsify+their+own+hypotheses;LangGraph+%C2%B7+RAG+%C2%B7+GraphRAG+%C2%B7+Text-to-SQL;Evals+first.+Vibes+second.;Placed+%40+Microsoft+Build+AI+Hackathon+2026)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshil-kaneria-3a498918b/)
[![Twitter](https://img.shields.io/badge/Twitter-1D9BF0?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/HarshilKaneria4)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=google-chrome&logoColor=white)](https://harshil26202.github.io/My-portfolio/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshilkaneriya26202@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-0E7490?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com/drive/folders/13eFBkf4dUJCc2UqfdoVkQ5FfCR2Wn5Eg?usp=drive_link)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Harshil26202&label=Profile+Views&color=8b5cf6&style=flat-square)&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/Harshil26202?style=flat-square&color=8b5cf6&label=Followers)](https://github.com/Harshil26202)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-5K%2B%20Followers-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/harshil-kaneria-3a498918b/)

</div>

---

## <img src="https://api.iconify.design/heroicons/command-line-solid.svg?color=%238b5cf6" width="24" align="center"/> agent.run("Who is Harshil?")

```diff
@@ agent.run(task="Who is Harshil Kaneria?", tools=["linkedin", "github", "prod_metrics"]) @@

  [plan]     3 sub-goals -> current role, proof of work, how he builds
+ [tool]     linkedin.lookup()          -> AI Engineer @ Argusoft  |  5K+ followers
+ [tool]     github.scan(topic="ai")    -> 6 public agentic & LLM systems (see below)
+ [tool]     prod_metrics("rag")        -> 97% answer accuracy over 1,000+ enterprise docs
+ [tool]     hackathons.results()       -> Nexus placed at Microsoft Build AI Hackathon 2026
- [reject]   hypothesis: "just another LangChain wrapper"      falsified by eval harness
+ [verify]   every claim above resolves to a repo or metric      citations OK
  [answer]   Builds agents that ship to production, and the evals that prove they work.
```

---

<img align="right" alt="Animated agent loop: plan, act, observe, reflect" width="340" src="assets/agent-loop.svg"/>

## <img src="https://api.iconify.design/heroicons/user-circle-solid.svg?color=%238b5cf6" width="24" align="center"/> About Me

- <img src="https://api.iconify.design/heroicons/cpu-chip-solid.svg?color=%238b5cf6" width="15" align="center"/> **AI Engineer** @ [Argusoft India Ltd](https://argusoft.com): agentic systems, RAG and voice AI in production
- <img src="https://api.iconify.design/heroicons/beaker-solid.svg?color=%238b5cf6" width="15" align="center"/> **AI Model Evaluation & RLHF** (contract): expert-level eval tasks for frontier LLMs
- <img src="https://api.iconify.design/heroicons/trophy-solid.svg?color=%238b5cf6" width="15" align="center"/> **Microsoft Build AI Hackathon 2026** (placed) • **Google HashCode 1st** • **SIH 2nd**
- <img src="https://api.iconify.design/heroicons/academic-cap-solid.svg?color=%238b5cf6" width="15" align="center"/> **B.E. Computer Engineering**, GEC Rajkot | **CGPA 9.26** | IIT Gandhinagar Externship
- <img src="https://api.iconify.design/heroicons/megaphone-solid.svg?color=%238b5cf6" width="15" align="center"/> Ex-**GDSC Lead** • 11 speaking sessions • guided 400+ students in GCP
- <img src="https://api.iconify.design/heroicons/map-pin-solid.svg?color=%238b5cf6" width="15" align="center"/> Rajkot, India | Open to remote AI engineering roles

<br clear="right"/>

```python
from harshil import Agent

me = Agent(
    role="AI Engineer @ Argusoft",
    tools=["LangGraph", "LangChain", "OpenAI", "Claude", "FastAPI", "pgVector", "Playwright"],
    memory="RAG + GraphRAG + vector stores",
    guardrails=["evals before vibes", "abstain when unsure", "human approval before actions"],
)

me.currently_building = [
    "Root-cause agents that separate cause from symptom",
    "Agentic scraping across 10+ e-commerce platforms",
    "Voice & meeting agents for Zoom and phone calls",
]
me.exploring = ["MCP & tool ecosystems", "versioned agent memory", "eval-driven development"]
me.open_to   = ["Agentic AI / LLM engineering roles", "Open-source AI collabs"]
```

---

## <img src="https://api.iconify.design/heroicons/share-solid.svg?color=%238b5cf6" width="24" align="center"/> Me, as a Multi-Agent System

```mermaid
flowchart LR
    IN(["Your problem"]) --> ORCH{{"Orchestrator<br/><b>Harshil</b>"}}
    ORCH --> PLAN["Planner<br/>LangGraph state machines<br/>task decomposition"]
    ORCH --> RET["Retriever<br/>RAG · GraphRAG<br/>pgVector · ChromaDB · FAISS"]
    ORCH --> TOOL["Tool-user<br/>function calling · Text-to-SQL<br/>Playwright · Celery"]
    PLAN --> EVAL
    RET --> EVAL
    TOOL --> EVAL["Evaluator<br/>baselines · LLM-as-judge<br/>falsification · SHAP"]
    EVAL -->|pass| SHIP(["Production<br/>FastAPI · Docker · AWS"])
    EVAL -.->|fail, retry| ORCH

    classDef core fill:#2e1065,stroke:#a78bfa,color:#f5f3ff,stroke-width:2px
    classDef agent fill:#0b1220,stroke:#22d3ee,color:#e0f2fe
    classDef io fill:#083344,stroke:#67e8f9,color:#ecfeff
    class ORCH core
    class PLAN,RET,TOOL,EVAL agent
    class IN,SHIP io
```

<div align="center">

| Agent | Where it's proven |
|:---|:---|
| **Planner** | [Cascade](https://github.com/Harshil26202/cascade) (triage, hypothesis, falsifier pipeline) • [Nexus](https://github.com/Harshil26202/nexus) (multi-agent CI/CD) |
| **Retriever** | Enterprise RAG at work (97% accuracy, 1K+ docs) • [Graph Chatbot](https://github.com/Harshil26202/graph-chatbot) (schema-aware prompting) |
| **Tool-user** | Agentic scraping at work (10+ platforms) • [Graph Chatbot](https://github.com/Harshil26202/graph-chatbot) (SQL with a safety layer) |
| **Evaluator** | [Cascade](https://github.com/Harshil26202/cascade) (eval harness vs. 2 baselines) • [Wearable Anomaly Detection](https://github.com/Harshil26202/Wearable-Data-Stream-Anomaly-Detection) (SHAP explanations) |

</div>

---

## <img src="https://api.iconify.design/heroicons/sparkles-solid.svg?color=%238b5cf6" width="24" align="center"/> Recently Shipped, Summarized by an LLM

<!--AI-LOG:START-->
_The agent runs daily via GitHub Actions and will fill this in on its first run._
<!--AI-LOG:END-->

---

## <img src="https://api.iconify.design/heroicons/rocket-launch-solid.svg?color=%238b5cf6" width="24" align="center"/> Featured AI Builds

<div align="center">

| Project | What it does | Stack |
|:---|:---|:---|
| **[Cascade](https://github.com/Harshil26202/cascade)** | On-call root-cause agent. Triage, hypothesis and falsifier agents, then deterministic precedence and evidence checks. **Abstains when the evidence is thin**; every fix waits for human approval | `OpenAI SDK` `DuckDB` `FastAPI` `Next.js` |
| **[Nexus](https://github.com/Harshil26202/nexus)** | AI-native DevOps: GPT-4o diff risk scoring, ML + LLM test selection (**67% less CI time** on demo data), auto postmortems. **Placed at Microsoft Build AI Hackathon 2026** | `GPT-4o` `XGBoost` `FastAPI` `OpenTelemetry` |
| **[Graph Chatbot](https://github.com/Harshil26202/graph-chatbot)** | Ask any PostgreSQL database questions in plain English: schema-aware text-to-SQL, SELECT-only guardrail, session memory, auto charts | `FastAPI` `asyncpg` `Gemini` `HF Inference` `React` |
| **[IPL Coaching Simulator](https://github.com/Harshil26202/gdg-vibe-coding)** | Live match simulation where an LLM grades your tactical calls on 3 axes and ranks you on a real-time leaderboard | `OpenAI` `WebSockets` `FastAPI` `React` |
| **[Wearable Anomaly Detection](https://github.com/Harshil26202/Wearable-Data-Stream-Anomaly-Detection)** | Streaming health anomaly detection that turns SHAP attributions into plain-language alerts | `Isolation Forest` `SHAP` `asyncio` |
| **[AI Photo Culling](https://github.com/Harshil26202/photo-quality-evaluation)** + **[Captus](https://github.com/Harshil26202/captus)** | 72 ML features (U²-Net saliency and more) at 2.7 img/s on CPU, plus a keyboard-first culling workspace | `PyTorch` `OpenCV` `React` `TypeScript` |

</div>

**In production @ Argusoft** (private): agentic medicine-price scraping across 10+ platforms (`LangGraph` `Celery` `Playwright`) • RAG document Q&A at 97% accuracy (`LLaMA` `ChromaDB` `OCR`) • natural-language-to-chart generator at 90%+ accuracy, saving 50+ hrs/month • Zoom & Twilio voice agent with 40% better action-item capture

---

## <img src="https://api.iconify.design/heroicons/squares-2x2-solid.svg?color=%238b5cf6" width="24" align="center"/> Tech Stack

**Agents & LLMs**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNSAxOWg1YTUgNSAwIDEgMS01LTVabTE0LTVhNSA1IDAgMSAxLTUgNWg1Wm0tOS05YTUgNSAwIDEgMC01IDVWNVptOSAwdjVhNSA1IDAgMSAwLTUtNVoiLz48L3N2Zz4%3D)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LLaMA](https://img.shields.io/badge/LLaMA-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMyAzdjE4aDE4VjN6bTExLjcyIDEzLjM3Yy0uNDEuMzgtLjgyLjY2LTEuMzMuODdsLS4yMS4wOWMtLjgzLjMtMS44Mi4yMS0yLjYzLS4xYy0uNDUtLjIxLS44Mi0uNDYtMS4xOS0uOGMuMzMtLjQxLjY2LS43NSAxLjA3LTEuMDdsLjI3LjIxYy41LjM1IDEgLjQ3IDEuNjEuNDFjLjYyLS4xMiAxLjEyLS40IDEuNTItLjljLjM3LS42MS40MS0xLjA5LjQxLTEuOFYxMC40YzAtLjcyLS4xNS0xLjE4LS42LTEuNzRjLS42MS0uNDktMS4xNy0uNzQtMS45Ni0uN2MtLjY2LjExLTEuMTkuNDItMS41OS45NWMtLjMzLjUzLS40OCAxLjA3LS4zNyAxLjY5Yy4yLjY4LjQ1IDEuMjUgMS4wNyAxLjYxYy41Mi4yNy45OC4zMiAxLjU2LjMzaC4yNWMuMi4wMi40LjAyLjYxLjAzVjE0Yy0xLjQ5LjA2LTIuNjUuMDYtMy44NC0uOTdhNC4yMiA0LjIyIDAgMCAxLTEuMjMtMi44Yy4wNC0uODguMzUtMS42Ljg2LTIuMzJsLjE1LS4yM2MxLjQzLTEuNTEgMy43LTEuNjEgNS4zMS0uMzFsLjE3LjE0Yy41OC41Mi45NiAxLjI1IDEuMDggMi4wMWMwIC4xNi4wMS4zMy4wMS40OXYzLjZjMCAxLjA1LS4zIDEuOTUtMS4wMiAyLjc0WiIvPjwvc3ZnPg%3D%3D)

**Retrieval & Memory**

![RAG](https://img.shields.io/badge/RAG_Pipelines-4A90D9?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMTguNjggMTIuMzJhNC40OSA0LjQ5IDAgMCAwLTYuMzYuMDFhNC40OSA0LjQ5IDAgMCAwIDAgNi4zNmE0LjUxIDQuNTEgMCAwIDAgNS41Ny42M0wyMSAyMi4zOUwyMi4zOSAyMWwtMy4wOS0zLjExYzEuMTMtMS43Ny44Ny00LjA5LS42Mi01LjU3bS0xLjQxIDQuOTVjLS45OC45OC0yLjU2Ljk3LTMuNTQgMGMtLjk3LS45OC0uOTctMi41Ni4wMS0zLjU0Yy45Ny0uOTcgMi41NS0uOTcgMy41MyAwYy45Ny45OC45NyAyLjU2IDAgMy41NE0xMC45IDIwLjFhNi41IDYuNSAwIDAgMS0xLjQ4LTIuMzJDNi4yNyAxNy4yNSA0IDE1Ljc2IDQgMTR2M2MwIDIuMjEgMy41OCA0IDggNGMtLjQtLjI2LS43Ny0uNTYtMS4xLS45TTQgOXYzYzAgMS42OCAyLjA3IDMuMTIgNSAzLjd2LS4yYzAtLjkzLjItMS44NS41OC0yLjY5QzYuMzQgMTIuMyA0IDEwLjc5IDQgOW04LTZDNy41OCAzIDQgNC43OSA0IDdjMCAyIDMgMy42OCA2Ljg1IDRoLjA1YzEuMi0xLjI2IDIuODYtMiA0LjYtMmMuOTEgMCAxLjgxLjE5IDIuNjQuNTZBMy4yMiAzLjIyIDAgMCAwIDIwIDdjMC0yLjIxLTMuNTgtNC04LTQiLz48L3N2Zz4%3D)
![GraphRAG](https://img.shields.io/badge/GraphRAG-7C3AED?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIiBkPSJNMTAgMTlhMiAyIDAgMSAwLTQgMGEyIDIgMCAwIDAgNCAwbTgtMTRhMiAyIDAgMSAwLTQgMGEyIDIgMCAwIDAgNCAwbS04IDBhMiAyIDAgMSAwLTQgMGEyIDIgMCAwIDAgNCAwbS00IDdhMiAyIDAgMSAwLTQgMGEyIDIgMCAwIDAgNCAwbTEyIDdhMiAyIDAgMSAwLTQgMGEyIDIgMCAwIDAgNCAwbS00LTdhMiAyIDAgMSAwLTQgMGEyIDIgMCAwIDAgNCAwbTggMGEyIDIgMCAxIDAtNCAwYTIgMiAwIDAgMCA0IDBNNiAxMmg0bTQgMGg0bS0zLTVsLTIgM005IDdsMiAzbTAgNGwtMiAzbTQtM2wyIDMiLz48L3N2Zz4%3D)
![pgVector](https://img.shields.io/badge/pgVector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1F2937?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxLjU3ZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjU2IDE2NCI%2BPGVsbGlwc2UgY3g9IjE3MC42NjciIGN5PSI4MS45MiIgZmlsbD0iI2ZmZGUyZCIgcng9Ijg1LjMzMyIgcnk9IjgxLjkyIi8%2BPGVsbGlwc2UgY3g9Ijg1LjMzMyIgY3k9IjgxLjkyIiBmaWxsPSIjMzI3ZWZmIiByeD0iODUuMzMzIiByeT0iODEuOTIiLz48cGF0aCBmaWxsPSIjZmY2NDQ2IiBkPSJNMTcwLjY2NyA4MS45MmMwIDQ1LjI0My0zOC4yMDYgODEuOTItODUuMzM0IDgxLjkyVjgxLjkyem0tODUuMzM0IDBDODUuMzMzIDM2LjY3NyAxMjMuNTM4IDAgMTcwLjY2NyAwdjgxLjkyeiIvPjwvc3ZnPg%3D%3D)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjIwIDIyMCI%2BPHBhdGggZmlsbD0id2hpdGUiIGZpbGwtcnVsZT0iZXZlbm9kZCIgZD0iTTEyNyA2LjRjLTIuMS0yLjUtNS42LTMuMS04LjQtMS41TDExNiA2LjNMODcuNyAyMi40TDk0LjMgMzRsMTguNC0xMC41bC00LjUgMjQuNmwxMy4xIDIuNGw0LjYtMjQuN0wxMzkuNSA0MmwxMC4yLTguNmwtMjAuNi0yNC42aC0uMXpNODcuMyAyMTMuOWM2LjggMCAxMi4zLTUuNCAxMi4zLTEycy01LjUtMTItMTIuMy0xMnMtMTIuMyA1LjQtMTIuMyAxMmMtLjEgNi42IDUuNSAxMiAxMi4zIDEybTE2LjUtNjUuOWwtNC40IDI0LjdsLTEzLjItMi40bDQuNC0yNC42bC0xOC40IDEwLjZsLTYuNy0xMS42bDI4LjEtMTYuMWwyLjYtMS41YzIuOC0xLjYgNi4zLTEgOC40IDEuNWwyIDIuNGwyMC45IDI0LjVsLTEwLjIgOC43em0xMC43LTU5bC00LjQgMjQuN2wtMTMuMi0yLjRsNC40LTI0LjVMODMgOTcuM2wtNi42LTExLjZsMjgtMTZ2LS4yaC4ybDIuNi0xLjVjMi44LTEuNiA2LjMtMSA4LjQgMS41bDIgMi4zbDIwLjggMjQuNmwtMTAuMiA4Ljd6bS04Ni4zIDk3LjZoLS4xbC0yLjctLjhjLTIuOS0uOC00LjgtMy42LTQuNi02LjZsMi40LTMzLjRsMTIuNy45bC0xLjUgMjAuM2wxOS43LTEzLjRsNy4xIDEwLjVsLTE5LjMgMTMuMWwxOS43IDUuN2wtMy41IDEyLjJ6bTEzMC43IDEzLjhsLS45IDIuOWMtLjkgMi44LTMuNSA0LjctNi41IDQuNWwtMi44LS4ybC0uMi4xbC0uMS0uMWwtMzEtMi4xbC44LTEyLjdsMjAuNiAxLjRsLTEzLjUtMTguOWwxMC4zLTcuNGwxMy44IDE5LjRsNi0xOS42bDEyLjEgMy43em0zNi40LTY4LjhsMS41IDIuN2MxLjUgMi43LjkgNi4xLTEuNSA4LjFsLTIuMiAxLjl2LjFoLS4xbC0yNC4xIDIwLjRsLTguNC05LjlsMTUuOC0xMy40bC0yMy43LTQuMmwyLjMtMTIuOGwyMy45IDQuMmwtMTAtMThsMTEuMy02LjN6bS0yNC41LTU1LjhsLTIxLjQgMTEuNWwtNi4yLTExLjRsMjEuMS0xMS4zbC0xOS4zLTcuOWw0LjktMTJsMjkuNCAxMS45bC4xLS4xbC4xLjJsMi43IDEuMWE2LjYgNi42IDAgMCAxIDQgNy4ybC0uNSAzbC01LjUgMzAuNWwtMTIuOC0yLjN6TTI3LjIgMTAyLjZsMjMuOCA0bC0yLjIgMTIuOGwtMjQtNC4xbDEwLjIgMThsLTExLjMgNi40bC0xNS40LTI3LjFsLTEuNS0yLjZjLTEuNS0yLjctLjktNi4xIDEuNC04LjFsMi4yLTEuOXYtLjFoLjFsMjMuOC0yMC41bDguNSA5Ljl6bTM1LjktNTUuNGwxNS44IDE3LjZsLTkuNyA4LjdsLTE2LjItMThMNDkuMyA3NmwtMTIuOC0yLjNsNS42LTMwLjRsLjYtMy4xYy41LTMgMy4xLTUuMiA2LjEtNS4zbDIuOC0uMWwuMS0uMWwuMS4xbDMxLjgtMS4zbC41IDEzeiIgY2xpcC1ydWxlPSJldmVub2RkIi8%2BPC9zdmc%2B)
![FAISS](https://img.shields.io/badge/FAISS-0066CC?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNi45MTUgNC4wM2MtMS45NjggMC0zLjY4MyAxLjI4LTQuODcxIDMuMTEzQy43MDQgOS4yMDggMCAxMS44ODMgMCAxNC40NDljMCAuNzA2LjA3IDEuMzY5LjIxIDEuOTczYTcgNyAwIDAgMCAuMjY1Ljg2YTUuMyA1LjMgMCAwIDAgLjM3MS43NjFjLjY5NiAxLjE1OSAxLjgxOCAxLjkyNyAzLjU5MyAxLjkyN2MxLjQ5NyAwIDIuNjMzLS42NzEgMy45NjUtMi40NDRjLjc2LTEuMDEyIDEuMTQ0LTEuNjI2IDIuNjYzLTQuMzJsLjc1Ni0xLjMzOWwuMTg2LS4zMjVjLjA2MS4xLjEyMS4xOTYuMTgzLjNsMi4xNTIgMy41OTVjLjcyNCAxLjIxIDEuNjY1IDIuNTU2IDIuNDcgMy4zMTRjMS4wNDYuOTg3IDEuOTkyIDEuMjIgMy4wNiAxLjIyYzEuMDc1IDAgMS44NzYtLjM1NSAyLjQ1NS0uODQzYTMuNyAzLjcgMCAwIDAgLjgxLS45NzNjLjU0Mi0uOTM5Ljg2MS0yLjEyNy44NjEtMy43NDVjMC0yLjcyLS42ODEtNS4zNTctMi4wODQtNy40NWMtMS4yODItMS45MTItMi45NTctMi45My00LjcxNi0yLjkzYy0xLjA0NyAwLTIuMDg4LjQ2Ny0zLjA1MyAxLjMwOGMtLjY1Mi41Ny0xLjI1NyAxLjI5LTEuODIgMi4wNWMtLjY5LS44NzUtMS4zMzUtMS41NDctMS45NTgtMi4wNTZjLTEuMTgyLS45NjYtMi4zMTUtMS4zMDMtMy40NTQtMS4zMDN6bTEwLjE2IDIuMDUzYzEuMTQ3IDAgMi4xODguNzU4IDIuOTkyIDEuOTk5YzEuMTMyIDEuNzQ4IDEuNjQ3IDQuMTk1IDEuNjQ3IDYuNGMwIDEuNTQ4LS4zNjggMi45LTEuODM5IDIuOWMtLjU4IDAtMS4wMjctLjIzLTEuNjY0LTEuMDA0Yy0uNDk2LS42MDEtMS4zNDMtMS44NzgtMi44MzItNC4zNThsLS42MTctMS4wMjhhNDUgNDUgMCAwIDAtMS4yNTUtMS45OGMuMDctLjEwOS4xNDEtLjIyNC4yMTEtLjMyN2MxLjEyLTEuNjY3IDIuMTE4LTIuNjAyIDMuMzU4LTIuNjAyem0tMTAuMjAxLjU1M2MxLjI2NSAwIDIuMDU4Ljc5MSAyLjY3NSAxLjQ0NmMuMzA3LjMyNy43MzcuODcxIDEuMjM0IDEuNTc5bC0xLjAyIDEuNTY2Yy0uNzU3IDEuMTYzLTEuODgyIDMuMDE3LTIuODM3IDQuMzM4Yy0xLjE5MSAxLjY0OS0xLjgxIDEuODE3LTIuNDg2IDEuODE3Yy0uNTI0IDAtMS4wMzgtLjIzNy0xLjM4My0uNzk0Yy0uMjYzLS40MjYtLjQ2NC0xLjEzLS40NjQtMi4wNDZjMC0yLjIyMS42My00LjUzNSAxLjY2LTYuMDg4Yy40NTQtLjY4Ny45NjQtMS4yMjYgMS41MzMtMS41MzNhMi4yNiAyLjI2IDAgMCAxIDEuMDg4LS4yODUiLz48L3N2Zz4%3D)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)

**Evals, ML & Observability**

![LLM Evals](https://img.shields.io/badge/LLM_Evals-0E7490?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJtMTAgMTdsLTQtNGwxLjQxLTEuNDFMMTAgMTQuMTdsNi41OS02LjU5TDE4IDltLTYtNmExIDEgMCAwIDEgMSAxYTEgMSAwIDAgMS0xIDFhMSAxIDAgMCAxLTEtMWExIDEgMCAwIDEgMS0xbTcgMGgtNC4xOEMxNC40IDEuODQgMTMuMyAxIDEyIDFzLTIuNC44NC0yLjgyIDJINWEyIDIgMCAwIDAtMiAydjE0YTIgMiAwIDAgMCAyIDJoMTRhMiAyIDAgMCAwIDItMlY1YTIgMiAwIDAgMC0yLTIiLz48L3N2Zz4%3D)
![SHAP](https://img.shields.io/badge/SHAP-00C853?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMiAyaDJ2MThoMTh2Mkgyem0xNSAwaDN2MTZoLTN6TTYgMTFoM3Y3SDZ6bTctOGgzdjRoLTN6bS0zIDVoM3Y0aC0zeiIvPjwvc3ZnPg%3D%3D)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIiBkPSJNMTQgNmEyIDIgMCAxIDAtNCAwYTIgMiAwIDAgMCA0IDBtLTcgOGEyIDIgMCAxIDAtNCAwYTIgMiAwIDAgMCA0IDBtMTQgMGEyIDIgMCAxIDAtNCAwYTIgMiAwIDAgMCA0IDBtLTcgNGEyIDIgMCAxIDAtNCAwYTIgMiAwIDAgMCA0IDBNMTIgOHY4bS01LjY4NC0zLjUwNGw0LjM2OC00Ljk5Mm03IDQuOTkybC00LjM2Ni00Ljk5Ii8%2BPC9zdmc%2B)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

[![PyTorch](https://skillicons.dev/icons?i=pytorch)](https://pytorch.org)
[![TensorFlow](https://skillicons.dev/icons?i=tensorflow)](https://tensorflow.org)
[![scikit-learn](https://skillicons.dev/icons?i=sklearn)](https://scikit-learn.org)
[![OpenCV](https://skillicons.dev/icons?i=opencv)](https://opencv.org)

**Backend for AI**

[![Python](https://skillicons.dev/icons?i=python)](https://python.org)
[![TypeScript](https://skillicons.dev/icons?i=ts)](https://typescriptlang.org)
[![FastAPI](https://skillicons.dev/icons?i=fastapi)](https://fastapi.tiangolo.com)
[![Django](https://skillicons.dev/icons?i=django)](https://djangoproject.com)
[![NodeJS](https://skillicons.dev/icons?i=nodejs)](https://nodejs.org)
[![NestJS](https://skillicons.dev/icons?i=nestjs)](https://nestjs.com)
[![Next.js](https://skillicons.dev/icons?i=nextjs)](https://nextjs.org)
[![React](https://skillicons.dev/icons?i=react)](https://react.dev)

[![PostgreSQL](https://skillicons.dev/icons?i=postgres)](https://postgresql.org)
[![MongoDB](https://skillicons.dev/icons?i=mongodb)](https://mongodb.com)
[![Redis](https://skillicons.dev/icons?i=redis)](https://redis.io)
[![MySQL](https://skillicons.dev/icons?i=mysql)](https://mysql.com)
[![DynamoDB](https://skillicons.dev/icons?i=dynamodb)](https://aws.amazon.com/dynamodb)
[![Docker](https://skillicons.dev/icons?i=docker)](https://docker.com)
[![AWS](https://skillicons.dev/icons?i=aws)](https://aws.amazon.com)
[![Linux](https://skillicons.dev/icons?i=linux)](https://linux.org)

![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?style=for-the-badge&logo=playwright&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)

---

## <img src="https://api.iconify.design/heroicons/briefcase-solid.svg?color=%238b5cf6" width="24" align="center"/> Experience

```
┌──────────────────────────────────────────────────────────────────────────┐
│  Jan 2023 – Present  │  AI Engineer @ Argusoft India Ltd                 │
│                      │  ↳ Agentic scraping: 10+ platforms, LangGraph     │
│                      │  ↳ RAG pipeline: 1K+ docs, 97% accuracy           │
│                      │  ↳ NL-to-chart tool: 90%+ accuracy, -50 hrs/month │
│                      │  ↳ Voice AI: 40% better action-item capture       │
│                      │  ↳ Backend: 10K+ rec/day, -35% latency, 99.9% up  │
├──────────────────────────────────────────────────────────────────────────┤
│  Contract            │  AI Model Evaluation & RLHF                       │
│                      │  ↳ Expert-level eval tasks for frontier LLMs      │
├──────────────────────────────────────────────────────────────────────────┤
│  May – Jul 2022      │  SDE Intern @ Maruti Techlabs                     │
│                      │  ↳ BI dashboards with DOMO, Tableau, MSSQL        │
├──────────────────────────────────────────────────────────────────────────┤
│  Jan – May 2022      │  Student Externship @ IIT Gandhinagar             │
│                      │  ↳ Selected from 20,000+ applicants               │
└──────────────────────────────────────────────────────────────────────────┘
```

---

## <img src="https://api.iconify.design/heroicons/star-solid.svg?color=%238b5cf6" width="24" align="center"/> Achievements

<div align="center">

| | Achievement | Details |
|:---:|:---|:---|
| ![](https://img.shields.io/badge/AI-7C3AED?style=flat-square&logo=microsoft&logoColor=white) | **Microsoft Build AI Hackathon 2026** | Placed with [Nexus](https://github.com/Harshil26202/nexus) |
| ![](https://img.shields.io/badge/1st-FFD700?style=flat-square&labelColor=FFD700&color=1a1200&logoColor=black&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9ImJsYWNrIiBkPSJNMTggMmMtLjkgMC0yIDEtMiAySDhjMC0xLTEuMS0yLTItMkgydjljMCAxIDEgMiAyIDJoMi4yYy40IDIgMS43IDMuNyA0LjggNHYyLjA4QzggMTkuNTQgOCAyMiA4IDIyaDhzMC0yLjQ2LTMtMi45MlYxN2MzLjEtLjMgNC40LTIgNC44LTRIMjBjMSAwIDItMSAyLTJWMnpNNiAxMUg0VjRoMnptMTQgMGgtMlY0aDJ6Ii8%2BPC9zdmc%2B) | **Google HashCode** | 1st Place, Regional |
| ![](https://img.shields.io/badge/2nd-C0C0C0?style=flat-square&labelColor=C0C0C0&color=1a1a1a&logoColor=black&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9ImJsYWNrIiBkPSJNMjAgMkg0djJsNS44MSA0LjM2YTcuMDA0IDcuMDA0IDAgMCAwLTQuNDYgOC44NGE2Ljk5NiA2Ljk5NiAwIDAgMCA4Ljg0IDQuNDZhNyA3IDAgMCAwIDAtMTMuM0wyMCA0em0tNS4wNiAxNy41TDEyIDE3Ljc4TDkuMDYgMTkuNWwuNzgtMy4zM2wtMi41OS0yLjI0bDMuNDEtLjI5TDEyIDEwLjVsMS4zNCAzLjE0bDMuNDEuMjlsLTIuNTkgMi4yNHoiLz48L3N2Zz4%3D) | **Smart India Hackathon** | 2nd Place, National |
| [![LeetCode](https://img.shields.io/badge/LC-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/hkharshil10/) | **LeetCode** | Rating **1664** |
| [![CodeChef](https://img.shields.io/badge/CC-5B4638?style=flat-square&logo=codechef&logoColor=white)](https://www.codechef.com/users/harshilhk10) | **CodeChef** | **1810 (4 stars)**, Rank 99 in International Long Challenge |
| [![GATE](https://img.shields.io/badge/GATE-0d47a1?style=flat-square&logo=googlescholar&logoColor=white)](https://gate.iitk.ac.in) | **GATE 2023** | Score 468, AIR 3933 |
| ![](https://img.shields.io/badge/CAT-7B1FA2?style=flat-square&logoColor=white&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxZW0iIGhlaWdodD0iMWVtIiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGZpbGw9IndoaXRlIiBkPSJNMTIgM0wxIDlsMTEgNmw5LTQuOTFWMTdoMlY5TTUgMTMuMTh2NEwxMiAyMWw3LTMuODJ2LTRMMTIgMTd6Ii8%2BPC9zdmc%2B) | **CAT** | **95.16 percentile** |
| [![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)](https://cloud.google.com) | **Google Cloud** | 20+ skill badges |
| [![LinkedIn](https://img.shields.io/badge/5K%2B-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshil-kaneria-3a498918b/) | **LinkedIn Network** | 5,000+ followers |
| ![](https://img.shields.io/badge/100%2B-37474F?style=flat-square&logo=databricks&logoColor=white) | **Certifications** | 100+ earned |

</div>

---

## <img src="https://api.iconify.design/heroicons/chart-bar-solid.svg?color=%238b5cf6" width="24" align="center"/> GitHub Analytics

<div align="center">

<img height="180em" alt="GitHub stats" src="profile/stats.svg"/>
<img height="180em" alt="Top languages" src="profile/top-langs.svg"/>

[![GitHub Streak](https://streak-stats.demolab.com?user=Harshil26202&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=A78BFA&ring=A78BFA&fire=22D3EE&currStreakLabel=A78BFA&sideLabels=C9D1D9&dates=8B949E)](https://git.io/streak-stats)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Harshil26202/Harshil26202/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Harshil26202/Harshil26202/output/github-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/Harshil26202/Harshil26202/output/github-snake.svg"/>
</picture>

</div>

---

<details>
<summary><b>Competitive Programming & Leadership</b></summary>

<br/>

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-1664_Rating-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/hkharshil10/)
[![CodeChef](https://img.shields.io/badge/CodeChef-1810_(4_Stars)-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/harshilhk10)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/harshilkaneriya2)

| Role | Organization | Impact |
|:---|:---|:---|
| **GDSC Lead** | Google Developer Student Clubs, GEC Rajkot | Organised 25+ events, guided 400+ students in GCP |
| **CodeChef Event Lead** | CodeChef Chapter, GEC Rajkot | Conducted 9 competitive programming events |
| **Chief Organizing Officer** | Inspire Talks | 3 editions across 2021–2022 |
| **Google Cloud Facilitator** | Google (Oct 2021) | Led 400+ students through skill badge tracks |
| **Newsletter Designer** | Dept. of Computer Engineering | Design lead 2020–2021 |

</div>

</details>

<details>
<summary><b>For AI agents, LLM crawlers & recruiter copilots: structured profile</b></summary>

<br/>

```yaml
# Machine-readable summary of this profile. Every fact here also appears above.
name: Harshil Kaneria
github: https://github.com/Harshil26202
linkedin: https://linkedin.com/in/harshil-kaneria-3a498918b/
email: harshilkaneriya26202@gmail.com
location: Rajkot, India (open to remote)
current_role: AI Engineer @ Argusoft India Ltd (Jan 2023 - present)
also: AI model evaluation & RLHF (contract)
specialties:
  - agentic AI and multi-agent orchestration (LangGraph, LangChain)
  - retrieval-augmented generation (RAG, GraphRAG, pgVector, ChromaDB, Pinecone, FAISS)
  - LLM evaluation (baselines, LLM-as-judge, falsification, abstention)
  - text-to-SQL and tool-using agents with guardrails
  - production backends for AI (Python, FastAPI, Django, Celery, Docker, AWS)
llm_providers: [OpenAI, Anthropic Claude, Google Gemini, Hugging Face, Meta LLaMA, Groq]
production_results:
  - RAG document Q&A: 97% accuracy over 1,000+ documents
  - agentic scraping across 10+ e-commerce platforms
  - natural-language-to-chart tool: 90%+ accuracy, saves 50+ hours/month
  - voice AI agent: 40% better post-call action-item capture
public_ai_projects: [cascade, nexus, graph-chatbot, gdg-vibe-coding, Wearable-Data-Stream-Anomaly-Detection, photo-quality-evaluation, captus]
awards:
  - Microsoft Build AI Hackathon 2026 (placed, project Nexus)
  - Google HashCode, 1st place regional
  - Smart India Hackathon, 2nd place national
education: B.E. Computer Engineering, GEC Rajkot, CGPA 9.26
open_to: [agentic AI engineer, LLM engineer, AI backend engineer]
```

</details>

---

<div align="center">

### <img src="https://api.iconify.design/heroicons/chat-bubble-left-right-solid.svg?color=%238b5cf6" width="22" align="center"/> Let's Build Agents That Actually Ship

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/harshil-kaneria-3a498918b/)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshilkaneriya26202@gmail.com)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-7C3AED?style=for-the-badge&logo=google-chrome&logoColor=white)](https://harshil26202.github.io/My-portfolio/)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0e7490,55:2e1065,100:0d1117&height=120&section=footer"/>

</div>
