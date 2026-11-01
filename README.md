# 🚀 12-Week AI Engineer Learning Plan & Progress Tracker

> A practical, hands-on 12-week roadmap to build production-grade AI engineering skills. Track your weekly milestones, curated learning resources, and portfolio project deliverables directly in your GitHub repository.

---

## 📊 Progress Summary

- **Total Duration:** 12 Weeks (6 Phases)
- **Projects Completed:** `0 / 4`
- **Overall Progress:** `0 / 12 Weeks`

| Phase | Focus Area | Weeks | Status |
| :--- | :--- | :---: | :---: |
| **Phase 1** | Programming & Software Foundations | Weeks 1–2 | ⬜ Pending |
| **Phase 2** | Databases & LLM Fundamentals | Weeks 3–4 | ⬜ Pending |
| **Phase 3** | Fine-Tuning, RAG & API Engineering | Weeks 5–7 | ⬜ Pending |
| **Phase 4** | Containerization, Deployment & CD | Weeks 8–9 | ⬜ Pending |
| **Phase 5** | Agent Memory, MCP & System Design | Weeks 10–11 | ⬜ Pending |
| **Phase 6** | Voice Agents & LLMOps | Week 12 | ⬜ Pending |

---

## 🛠️ Portfolio Projects Overview

- [ ] **Project 1: News Summarizer** *(Weeks 1–3)*
  - Python CLI, `pandas` CSV processing, OpenAI API summarization, `pytest` unit/integration tests, and local PostgreSQL database migration.
- [ ] **Project 2: Streamlit & FastAPI RAG App** *(Weeks 6–7)*
  - Hybrid search retrieval (Keyword + `pgvector`), Streamlit UI, FastAPI backend, user auth, and streaming responses.
- [ ] **Project 3: Production Agentic System** *(Week 9)*
  - Multi-tool agent system built with industry tools, CD release verification, and production evaluation.
- [ ] **Project 4: Observable Voice Agent** *(Week 12)*
  - Real-time voice interaction, job search agent tool integration, and full LLMOps observability tracing.

---

## 📅 Detailed Weekly Roadmap

### Phase 1: Programming & Software Foundations (Weeks 1–2)

#### 🔹 Week 1: Core Python, Tooling & Project 1 (News Summarizer)
- [ ] **Concepts to Master:**
  - [x] Python syntax, variables, data structures, classes, and modular imports
  - [x] Package & environment management with `uv`
  - [x] Git workflow: cloning, branching, committing, pushing, and Pull Requests
  - [x] OpenAI API integration, HTTP status codes, and JSON handling
  - [ ] Unit testing (isolated functions) & integration testing (API endpoints)
- [ ] **Project Milestone:**
  - [ ] Build **Project 1: News Summarizer** (CSV input $\rightarrow$ `pandas` $\rightarrow$ OpenAI API summary $\rightarrow$ `pytest` coverage)
- [ ] **Learning Resources:**
  - 🎥 [Python for AI - Full Beginner Course (Dave Ebbelaar)](https://www.youtube.com/watch?v=ygXn5nV5qFc)
  - 🎥 [Python Tutorial: UV - A Faster, All-in-One Package Manager (Corey Schafer)](https://www.youtube.com/watch?v=AMdG7IjgSPM)
  - 📖 [GitHub Hello World Guide](https://docs.github.com/en/get-started/using-github/hello-world)
  - 📖 [OpenAI API Quickstart Documentation](https://developers.openai.com/api/docs/quickstart)
  - 🎥 [How To Write Unit Tests in Python with Pytest (pixegami)](https://www.youtube.com/watch?v=YbpKMIUjvK8)
  - 🎥 [REST API Integration Testing with Pytest (pixegami)](https://www.youtube.com/watch?v=7dgQRVqF1N0)

#### 🔹 Week 2: Continuous Integration & Machine Learning Foundations
- [ ] **Concepts to Master:**
  - [x] Continuous Integration (CI) test automation on GitHub PRs
  - [ ] (Optional) ML foundations: regression, decision trees, random forests
    - [x] Linear regression
    - [x] Gradient decent
  - [ ] Overfitting vs. underfitting, bias-variance tradeoff, precision, recall, and data leakage
- [ ] **Learning Resources:**
  - 📖 [GitHub Skills - Test with Actions](https://github.com/skills/test-with-actions)
  - 📖 [Microsoft ML for Beginners (Optional)](https://github.com/microsoft/ML-For-Beginners)

---

### Phase 2: Databases & LLM Fundamentals (Weeks 3–4)

#### 🔹 Week 3: SQL & Database Integration
- [ ] **Concepts to Master:**
  - [ ] SQL selection, filtering, inner/outer joins, grouping, and schema design
  - [ ] Setting up a local PostgreSQL database instance
  - [ ] Querying database records in Python using SQL drivers
- [ ] **Project Milestone:**
  - [ ] **Upgrade Project 1:** Migrate News Summarizer storage from CSV to PostgreSQL
- [ ] **Learning Resources:**
  - 🌐 [SQLBolt Interactive Tutorials](https://sqlbolt.com/)

#### 🔹 Week 4: Large Language Model (LLM) Fundamentals
- [ ] **Concepts to Master:**
  - [ ] Model weights, training vs. inference, and backpropagation principles
  - [ ] Transformer architecture & self-attention mechanisms
  - [ ] Tokenization, text embeddings, and context window dynamics
    - [ ] Types of embeddings
      - [ ] Word2Vec algorithm  [CBOW (Continuous bag of words), Skip gram]
- [ ] **Learning Resources:**
  - 🎥 [Intro to Large Language Models (Andrej Karpathy)](https://www.youtube.com/watch?v=zjkBMFhNj_g)
  - 🌐 [Zero to Hero Course (Andrej Karpathy - Optional)](https://karpathy.ai/zero-to-hero.html)
  - 📖 [Hugging Face LLM Course - Chapter 1](https://huggingface.co/learn/llm-course/chapter1/1)

---

### Phase 3: Fine-Tuning, RAG & API Engineering (Weeks 5–7)

#### 🔹 Week 5: Fine-Tuning & Introduction to RAG
- [ ] **Concepts to Master:**
  - [ ] Parameter-efficient fine-tuning (LoRA) using free notebooks
  - [ ] Prompt engineering vs. in-context retrieval vs. fine-tuning trade-offs
  - [ ] RAG basics: document chunking, embeddings, `pgvector`, and hybrid search
- [ ] **Learning Resources:**
  - 📖 [Unsloth Notebooks Catalog](https://unsloth.ai/docs/get-started/unsloth-notebooks)

#### 🔹 Week 6: Project 2 (Basic RAG Application)
- [ ] **Concepts to Master:**
  - [ ] Document loading, text splitting, and vector embedding creation
  - [ ] Keyword + vector hybrid retrieval with `pgvector`
  - [ ] Answer generation with source citation grounding
- [ ] **Project Milestone:**
  - [ ] Build **Project 2: Local RAG Application** with a Streamlit interface
- [ ] **Learning Resources:**
  - 💻 [Jam With AI Beginner Local RAG Code](https://github.com/jamwithai/beginner-local-rag-system)
  - 📖 [Building a Local RAG System - Guide Part 1](https://jamwithai.substack.com/p/build-a-local-llm-based-rag-system)
  - 📖 [Building a Local RAG System - Guide Part 2](https://jamwithai.substack.com/p/build-a-local-llm-based-rag-system-628)

#### 🔹 Week 7: API Engineering with FastAPI
- [ ] **Concepts to Master:**
  - [ ] Async programming (`async`/`await`), routers, request validation
  - [ ] Dependency injection, authentication, and authorization checks
  - [ ] Database migrations and streaming endpoint states
- [ ] **Project Milestone:**
  - [ ] **Upgrade Project 2:** Convert RAG app to a production FastAPI backend
- [ ] **Learning Resources:**
  - 🎥 [FastAPI Tutorials Series (Corey Schafer)](https://www.youtube.com/playlist?list=PL-osiE80TeTsak-c-QsVeg0YYG_0TeyXI)
  - 📖 [FastAPI Dependencies Documentation](https://fastapi.tiangolo.com/tutorial/dependencies/)

---

### Phase 4: Containerization, Deployment & CD (Weeks 8–9)

#### 🔹 Week 8: Docker Containerization & Cloud Deployment
- [ ] **Concepts to Master:**
  - [ ] Dockerfiles, images, containers, multi-container Compose stacks, and volumes
  - [ ] Secrets management, environment configuration, health checks, and logging
  - [ ] Cloud deployment (Google Cloud Run / AWS / Azure) & cost control bounds
- [ ] **Learning Resources:**
  - 🎥 [Docker Tutorial for Beginners (TechWorld with Nana)](https://www.youtube.com/watch?v=3c-iBn73dDE)
  - 🎥 [Deploy FastAPI with Docker to Cloud Run (Corey Schafer)](https://www.youtube.com/watch?v=eqjngvKfabg)

#### 🔹 Week 9: Continuous Delivery & Project 3 (Production Agent)
- [ ] **Concepts to Master:**
  - [ ] CD release pipelines and automated evaluation quality gates
  - [ ] Production agent design patterns and multi-tool integration
- [ ] **Project Milestone:**
  - [ ] Build **Project 3: Production Agentic System**
- [ ] **Learning Resources:**
  - 💻 [Production Agentic RAG Course Repository](https://github.com/jamwithai/production-agentic-rag-course)
  - 🎥 [How a Production AI Agent System Actually Works](https://www.youtube.com/watch?v=sKzL0wSN9vQ)

---

### Phase 5: Agent Memory, MCP & System Design (Weeks 10–11)

#### 🔹 Week 10: Agent Memory Architectures
- [ ] **Concepts to Master:**
  - [ ] Managing short-term conversation context vs. long-term persistent memory
  - [ ] Implementing user state preservation across sessions
- [ ] **Learning Resources:**
  - 🎥 [AI Agent Memory: 7 Types Explained](https://www.youtube.com/watch?v=bK1clrG-boc)
  - 🎥 [Memory for Agents (LangChain Conceptual Video)](https://www.youtube.com/watch?v=JTL0yp85FsE)
  - 🎥 [Long-Term Memory Agent Template (LangChain)](https://www.youtube.com/watch?v=-xkduCeudgY)

#### 🔹 Week 11: Model Context Protocol (MCP) & System Design
- [ ] **Concepts to Master:**
  - [ ] Model Context Protocol (MCP) server & tool integrations
  - [ ] AI system design patterns: caching, rate-limiting, and request queuing
- [ ] **Learning Resources:**
  - 🎥 [Intro to MCP Servers with Python (freeCodeCamp)](https://www.youtube.com/watch?v=DosHnyq78xY)
  - 📖 [Hugging Face MCP Course](https://huggingface.co/learn/mcp-course/unit0/introduction)
  - 🎥 [AI System Design: 7 Patterns Explained](https://www.youtube.com/watch?v=0jCss9xfOiw)

---

### Phase 6: Voice Agents & LLMOps (Week 12)

#### 🔹 Week 12: Project 4 (Observable Voice Agent)
- [ ] **Concepts to Master:**
  - [ ] Real-time audio STT/TTS processing pipelines
  - [ ] LLMOps observability: latency tracing, cost monitoring, and error tracking
- [ ] **Project Milestone:**
  - [ ] Build **Project 4: Observable Job Search Voice Agent**
- [ ] **Learning Resources:**
  - 💻 [Observable Job Agent Open-Source Repository](https://github.com/jamwithai/observable-job-agent)

---


# Learn LLM

In this comprehensive and beginner-friendly course, you will learn all of the tools that you need to become a great OOP programmer, writing clean and maintainable software.

Python Introduction -

Youtube video: https://www.youtube.com/watch?v=iLRZi0Gu8Go

 ̰ ̰
## LLM Resources

| # | Resource | Link | Source |
|---|---|---|---|
| 1 | Stanford CS224N — Natural Language Processing with Deep Learning | https://web.stanford.edu/class/cs224n/ | Stanford University |
| 2 | Hugging Face — LLM Course (Hugging Face Learn) | https://huggingface.co/learn/llm-course | Hugging Face |
| 3 | GitHub — mlabonne/llm-course (LLM course repo) | https://github.com/mlabonne/llm-course | GitHub |
| 4 | YouTube — "Let's build GPT: from scratch, in code, spelled out" (Andrej Karpathy) | https://www.youtube.com/watch?v=kCc8FmEb1nY | YTScribe |
| 5 | DeepLearning.AI — Generative AI with Large Language Models (Coursera / DL.AI) | https://www.deeplearning.ai/courses/generative-ai-with-llms/ | DeepLearning.ai |
| 6 | Google Cloud / Coursera / Google Skills — Introduction to Large Language Models | https://www.coursera.org/learn/introduction-to-large-language-models | Coursera / Google Cloud |
| 7 | Learn Prompting — ChatGPT for Everyone / LearnPrompting resources | https://learnprompting.org/courses/chatgpt-for-everyone and https://learnprompting.org | Learn Prompting |
| 8 | Vanderbilt / Coursera — Prompt Engineering for ChatGPT | https://www.coursera.org/learn/prompt-engineering | Coursera |
| 9 | OpenAI Academy — official OpenAI learning resources and short courses for practitioners | https://academy.openai.com/ | OpenAI Academy |

---

## Week 1 - Stanford CS224N

### Create python virtual environment
    python -m venv .cs224n

### Activate the Environment
    source .cs224n/bin/activate

### Deactivate the Environment
    deactivate

### Install requirements
    pip install -r requirements.txt

---
### References

https://manikanthgoud123.medium.com/understanding-contextualized-word-embeddings-the-evolution-of-language-understanding-in-ai-8bf79a98eb51
https://youtu.be/ZhAz268Hdpw


