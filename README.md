🧠 Advanced RAG Techniques — Course Projects
A hands-on collection of Jupyter notebooks implementing state-of-the-art Retrieval-Augmented Generation (RAG) architectures and agentic reasoning patterns. Completed as part of an advanced NLP / LLM course.

📁 Notebooks Overview
#NotebookDescription11-AgenticRAG.ipynbAgentic RAG — LLM-driven retrieval decision-making21-rag_evaluation.ipynbEvaluation framework for RAG pipelines (faithfulness, relevance, etc.)32-CorrectiveRAG.ipynbCorrective RAG — self-correcting retrieval with relevance grading42-ReAct.ipynbReAct agent — interleaved reasoning and acting with tool use53-COTRag.ipynbChain-of-Thought RAG — step-by-step reasoning over retrieved context64-AdaptiveRAG.ipynbAdaptive RAG — dynamic routing between retrieval strategies74-Selfreflection.ipynbSelf-Reflection RAG — iterative answer revision and hallucination check85-QueryPlanningdecomposition.ipynbQuery planning and sub-question decomposition96-Iterativeretrieval.ipynbIterative / multi-hop retrieval for complex queries107-answersynthesis.ipynbAnswer synthesis from multiple retrieved documents118-multiagent.ipynbMulti-agent RAG — coordinating specialized retrieval agents12cache_augment_generation.ipynbCache-Augmented Generation — latency-efficient retrieval caching13ragmemory.ipynbRAG with persistent memory — stateful conversational retrieval

🛠️ Key Techniques Covered

Retrieval strategies: Dense + sparse hybrid retrieval, FAISS, BM25 re-ranking, Weaviate
Agentic patterns: ReAct, self-reflection, corrective loops, adaptive routing
LLM integration: LangChain / LangGraph, LLaMA 2, GPT-4
Evaluation: RAG faithfulness, answer relevance, context precision metrics
Performance: FlashAttention2, LoRA fine-tuning, caching for low-latency pipelines
Multi-agent: Coordinated agent graphs for complex reasoning tasks


🚀 Getting Started
bash# Clone the repository
git clone https://github.com/YOUR_USERNAME/advanced-rag-techniques.git
cd advanced-rag-techniques

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
Requirements

Python 3.9+
langchain, langgraph
openai or ollama (for local LLMs)
faiss-cpu, sentence-transformers
jupyter


📊 Experiment Highlights
From the research log:

LLaMA2 + RAG chatbot — 75% win rate vs. human answers; ~300ms latency on A100
Hybrid retriever (FAISS + BM25 re-ranking) — better recall vs. dense-only
Chain-of-Thought prompting — +8% on logic tasks vs. direct prompting
LoRA fine-tuning (rank=8) — 60% reduction in GPU memory footprint
FlashAttention2 — ~50% reduction in context processing latency


📌 Topics Learned
RAG Pipelines · Agentic AI · LangGraph · LLM Evaluation
Multi-Agent Systems · Query Decomposition · Prompt Engineering
Vector Databases · Fine-tuning · LLM Safety
