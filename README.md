# 🧠 Advanced RAG Techniques — Course Projects

A hands-on collection of Jupyter notebooks implementing state-of-the-art **Retrieval-Augmented Generation (RAG)** architectures and agentic reasoning patterns. Completed as part of an advanced NLP / LLM course.

---

## 📁 Notebooks Overview

| # | Notebook | Description |
|---|----------|-------------|
| 1 | `1-AgenticRAG.ipynb` | Agentic RAG — LLM-driven retrieval decision-making |
| 2 | `1-rag_evaluation.ipynb` | Evaluation framework for RAG pipelines (faithfulness, relevance, etc.) |
| 3 | `2-CorrectiveRAG.ipynb` | Corrective RAG — self-correcting retrieval with relevance grading |
| 4 | `2-ReAct.ipynb` | ReAct agent — interleaved reasoning and acting with tool use |
| 5 | `3-COTRag.ipynb` | Chain-of-Thought RAG — step-by-step reasoning over retrieved context |
| 6 | `4-AdaptiveRAG.ipynb` | Adaptive RAG — dynamic routing between retrieval strategies |
| 7 | `4-Selfreflection.ipynb` | Self-Reflection RAG — iterative answer revision and hallucination check |
| 8 | `5-QueryPlanningdecomposition.ipynb` | Query planning and sub-question decomposition |
| 9 | `6-Iterativeretrieval.ipynb` | Iterative / multi-hop retrieval for complex queries |
| 10 | `7-answersynthesis.ipynb` | Answer synthesis from multiple retrieved documents |
| 11 | `8-multiagent.ipynb` | Multi-agent RAG — coordinating specialized retrieval agents |
| 12 | `cache_augment_generation.ipynb` | Cache-Augmented Generation — latency-efficient retrieval caching |
| 13 | `ragmemory.ipynb` | RAG with persistent memory — stateful conversational retrieval |

---

## 🛠️ Key Techniques Covered

- **Retrieval strategies**: Dense + sparse hybrid retrieval, FAISS, BM25 re-ranking, Weaviate
- **Agentic patterns**: ReAct, self-reflection, corrective loops, adaptive routing
- **LLM integration**: LangChain / LangGraph, LLaMA 2, GPT-4
- **Evaluation**: RAG faithfulness, answer relevance, context precision metrics
- **Performance**: FlashAttention2, LoRA fine-tuning, caching for low-latency pipelines
- **Multi-agent**: Coordinated agent graphs for complex reasoning tasks

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/advanced-rag-techniques.git
cd advanced-rag-techniques

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

### Requirements
- Python 3.9+
- `langchain`, `langgraph`
- `openai` or `ollama` (for local LLMs)
- `faiss-cpu`, `sentence-transformers`
- `jupyter`

---

## 📊 Experiment Highlights

From the research log:

- **LLaMA2 + RAG chatbot** — 75% win rate vs. human answers; ~300ms latency on A100
- **Hybrid retriever** (FAISS + BM25 re-ranking) — better recall vs. dense-only
- **Chain-of-Thought prompting** — +8% on logic tasks vs. direct prompting
- **LoRA fine-tuning** (rank=8) — 60% reduction in GPU memory footprint
- **FlashAttention2** — ~50% reduction in context processing latency

---

## 📌 Topics Learned

```
RAG Pipelines · Agentic AI · LangGraph · LLM Evaluation
Multi-Agent Systems · Query Decomposition · Prompt Engineering
Vector Databases · Fine-tuning · LLM Safety
```
