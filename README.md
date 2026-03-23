# AI Product Manager Resources

A curated reference list I maintain for AI product management — 
frameworks, tools, evaluation approaches, and reading worth keeping.

---

## 🧠 Prompt Engineering

| Resource | What It Is | Link |
|---|---|---|
| Anthropic Prompt Library | Official prompting patterns from Anthropic | [docs.anthropic.com](https://docs.anthropic.com) |
| OpenAI Prompt Engineering Guide | Best practices for GPT models | [platform.openai.com](https://platform.openai.com/docs/guides/prompt-engineering) |
| LearnPrompting.org | Free open-source prompting course | [learnprompting.org](https://learnprompting.org) |

---

## 📊 AI Product Metrics & Evaluation

Key metrics I track when evaluating AI feature quality:

**Output Quality**
- Accuracy / correctness rate
- Hallucination rate (factual errors per N outputs)
- Relevance score (does the output match the intent?)

**User Experience**
- Task completion rate with AI vs. without
- Time-to-value (how fast does the user get what they need?)
- Override rate (how often do users edit or reject AI output?)

**Reliability**
- Latency (p50, p95, p99)
- Error / fallback rate
- Consistency across rephrased inputs

---

## 🛠️ Tools I Use

| Category | Tool | Notes |
|---|---|---|
| API Testing | Anthropic Console | Best for Claude prompt iteration |
| API Testing | OpenAI Playground | Good for GPT comparison testing |
| Prototyping | Streamlit | Fastest way to wrap an AI API in a UI |
| Prototyping | v0.dev | Great for UI scaffolding |
| Evals | LangSmith | Tracing and evaluation for LLM apps |
| Docs | Notion AI | Good reference for AI-assisted writing |

---

## 📚 Reading List

**Foundational**
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — the original transformer paper (worth skimming)
- [Building LLM-Powered Applications](https://huyenchip.com/2023/04/11/llm-engineering.html) — Chip Huyen's practical guide

**AI Product Strategy**
- [The AI Product Playbook](https://www.lennysnewsletter.com/) — Lenny's Newsletter AI issues
- [Sequoia's AI Ascent talks](https://www.sequoiacap.com/) — market-level AI thinking

**Evaluation & Safety**
- [Anthropic's model cards](https://www.anthropic.com/research) — how to think about model behavior
- [HELM Benchmark](https://crfm.stanford.edu/helm/) — Stanford's LLM evaluation framework

---

## 🗂️ PM Frameworks Adapted for AI

### The AI Feature Decision Matrix
Before building any AI feature, I ask:

| Question | Why It Matters |
|---|---|
| What's the fallback if the model is wrong? | AI fails — products must handle it gracefully |
| How will we know if it's working? | Evals must be defined before shipping |
| What data does this need, and do we have it? | Data availability gates most AI features |
| What's the latency budget? | AI is slow — UX must account for it |
| Is this the right job for AI? | Not everything benefits from ML |

---

*Updated regularly. Suggestions welcome via Issues.*
