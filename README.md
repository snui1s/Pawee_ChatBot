# 🤖 Pawee ChatBot (Personal AI Representative)

An interactive AI assistant designed to represent **Pawee Indulakshana**, a Junior AI Engineer. This bot answers questions about his career, skills, and experience while capturing leads and unknown questions in real-time.

---

## ✨ Features

- **Brain**: Powered by **OpenAI GPT-4o-mini**.
- **Context-Aware**: Uses `summary.txt` as the source of truth for all professional experience.
- **Agentic Tools**:
  - **Leads Capture**: Automatically records name and email into Supabase.
  - **Knowledge Gap Logging**: Records questions that aren't in the summary for future updates.
- **Production Ready**:
  - **Postgres Pooling**: High-performance database connection handling via `psycopg2`.
  - **FastAPI Integration**: Includes `HEAD` and `/health` endpoints for uptime monitoring (Render-friendly).
- **Multilingual**: Fluent in both **Thai** and **English**.
- **Sliding Window Memory**: Remembers context within the conversation without slowing down.

## 🛠 Tech Stack

- **Framework**: Gradio + FastAPI
- **LLM Orchestration**: LangChain
- **Database**: Supabase (PostgreSQL)
- **Package Manager**: uv

---

_Created by Pawee Indulakshana - Aspiring AI Engineer & Product Manager_
