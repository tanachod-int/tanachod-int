# Hi there, I'm Tanachod
### Full-Stack Developer & AI Systems Engineer

I specialize in building **agentic workflows**, **local-first AI applications**, and **high-observability data pipelines**. I love bridging the gap between advanced AI models (like Gemini & Typhoon) and robust, modern full-stack architectures.

---

## 🛠️ Tech Stack & Tooling

| Category | Technologies & Tools |
| :--- | :--- |
| **Frontend** | ![Next.js 15](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React 19](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) |
| **Backend & APIs** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3A?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge&logo=langchain&logoColor=orange) |
| **AI / ML & Local LLMs** | ![Gemini API](https://img.shields.io/badge/Gemini_API-8E75C2?style=for-the-badge&logo=googlegemini&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) ![Typhoon 2.5](https://img.shields.io/badge/Typhoon_2.5-FF5A09?style=for-the-badge&logo=opsgenie&logoColor=white) ![BGE M3](https://img.shields.io/badge/BGE--M3-26A69A?style=for-the-badge&logo=deepmind&logoColor=white) ![BGE Reranker](https://img.shields.io/badge/BGE--Reranker-00796B?style=for-the-badge&logo=deepmind&logoColor=white) |
| **Databases & Cloud** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white) |
| **DevOps & Services** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Google Sheets API](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white) ![Discord Webhook](https://img.shields.io/badge/Discord_Webhook-5865F2?style=for-the-badge&logo=discord&logoColor=white) |

---

## 🚀 Featured Projects

### 1. **AutoAgent Dashboard** — *Human-in-the-Loop AI Automation*
An advanced dashboard designed for natural-language driven AI operations pipelines with interactive observability and human approval gates.
*   **The Workflow**: 
    1. Users input natural language requests in Thai (e.g., *"หาสินค้าที่ stock ต่ำกว่า 10 ชิ้น"*).
    2. Backend translates the query into optimized PostgreSQL SQL via Gemini API (`gemini-3.1-flash-lite`).
    3. Executes the query against a Supabase/PostgreSQL database.
    4. Automatically generates critical inventory reports and logs them to **Google Sheets**.
    5. Drafts a **Discord Embed Notification** using Gemini.
    6. Prompts the user on the dashboard to **approve** the notification before broadcasting via Discord Webhooks.
*   **Tech Stack**: Next.js 15, React 19, TypeScript, Tailwind CSS 4, Python, FastAPI, LangGraph (State Machine), Gemini API, Supabase PostgreSQL, Google Sheets API, Discord Webhook.

### 2. **ChatBSA** — *Local-First Medical RAG Chatbot*
A secure, privacy-focused Medical Retrieval-Augmented Generation (RAG) assistant designed for initial symptom analysis referencing Thai medical textbooks.
*   **Key Highlights**:
    *   **Two-Stage Retrieval**: Vector Search (Cosine Similarity via `bge-m3` on `pgvector`) combined with high-accuracy local re-ranking (`bge-reranker-base` run via `@xenova/transformers` in INT8) to extract context.
    *   **OCR Pipeline**: Automated document parser utilizing `typhoon-ocr1.5-3b` to convert scanned medical textbooks into structured Markdown text.
    *   **Strict Medical Guardrails**: Embedded security rules (Red Flags) to detect severe symptoms and immediately redirect to emergency services while providing textbook citations for diagnoses.
*   **Tech Stack**: Next.js 15 (App Router), React 19, Tailwind CSS v4, Radix UI, LangChain, PostgreSQL (pgvector), Supabase SSR, Ollama (`typhoon2.5-qwen3-4b`, `bge-m3`, `bge-reranker-base`, `typhoon-ocr1.5-3b`).

---

## 📫 Let's Connect!
- **GitHub**: [github.com/tanachod-int](https://github.com/tanachod-int)
- **Email**: tanachod.int@gmail.com
