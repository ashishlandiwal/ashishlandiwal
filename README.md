# Ashish Jangra — AI / ML Engineer

**NLP · Generative AI · MLOps** — [GitHub](https://github.com/ashishlandiwal) ·
[LinkedIn](https://linkedin.com/in/ashishjangra284) · ashishjangra284@gmail.com

Four end-to-end projects spanning the modern AI stack — RAG/agents, deep learning, classical
ML, and unsupervised learning. Every repo is reproducible: real measured metrics, unit tests,
Docker, and CI. Numbers below are produced by the code, not claimed.

| Project | What it shows | Stack | Headline result |
|---|---|---|---|
| [genai-support-assistant-rag](https://github.com/ashishlandiwal/genai-support-assistant-rag) | RAG + agentic routing with an answerability gate; pluggable embeddings/LLM; eval harness | Flask · FAISS · sentence-transformers · OpenAI/Ollama | hit@4 **100%**, grounding **100%**, escalation recall **100%** (offline eval) |
| [sentiment-analysis-rnn-lstm-bert](https://github.com/ashishlandiwal/sentiment-analysis-rnn-lstm-bert) | RNN vs LSTM vs fine-tuned transformer, same split | PyTorch · HuggingFace Transformers | RNN **49.5%** → LSTM **71.7%** → DistilBERT **82.6%** |
| [medical-report-classifier](https://github.com/ashishlandiwal/medical-report-classifier) | 6-model comparison on imbalanced data, SMOTE, model card | scikit-learn · imbalanced-learn · MLflow · Streamlit | acc **97.6%**, F1 **0.938**; SMOTE recall **0.70→0.80** |
| [ecommerce-customer-segmentation](https://github.com/ashishlandiwal/ecommerce-customer-segmentation) | KMeans/DBSCAN + PCA, validated against known segments | scikit-learn · pandas · matplotlib | silhouette **0.435**, ARI **0.50** vs ground truth |

## What's deliberate across all four

- **Honest metrics.** READMEs report what the code actually measured — including a vanilla RNN
  failing at chance and a segmentation ARI of 0.50 — not inflated numbers.
- **Runs anywhere.** The RAG app runs with zero API keys (offline backend); the ML projects use
  bundled or auto-downloaded data; tests need no network.
- **Engineering, not just notebooks.** `src/` packages, pytest suites, ruff, Dockerfiles, and
  GitHub Actions CI in every repo.

## Skills

Python · PyTorch · scikit-learn · HuggingFace · RAG / LLMs / agents · LangChain · FAISS ·
imbalanced-learn · MLflow · Flask · Streamlit · Docker · Git/GitHub Actions · pandas/NumPy.
