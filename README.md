# AI & Machine Learning — Learning Hub

Central index for my hands-on AI/ML learning projects. Each topic gets its own repo so work stays small, focused, and easy to review.

## How repos are organized

| Prefix | Purpose | Example |
|--------|---------|---------|
| `ml-learn-*` | Core ML (sklearn, stats, classical models) | `ml-learn-01-linear-regression` |
| `dl-learn-*` | Deep learning (PyTorch / TensorFlow) | `dl-learn-01-mnist-mlp` |
| `nlp-learn-*` | NLP & LLM basics | `nlp-learn-01-text-classification` |
| `genai-learn-*` | GenAI, RAG, agents, prompts | `genai-learn-01-rag-notes` |
| `mlops-learn-*` | Deployment, MLflow, monitoring | `mlops-learn-01-fastapi-serve` |

## Learning path

| # | Topic | Status | Repo |
|---|--------|--------|------|
| 01 | Python for data & notebooks | Planned | — |
| 02 | NumPy, Pandas, visualization | Planned | — |
| 03 | Supervised ML (regression, classification) | Planned | — |
| 04 | Model evaluation & cross-validation | Planned | — |
| 05 | Feature engineering | Planned | — |
| 06 | Neural networks intro | Planned | — |
| 07 | NLP fundamentals | Planned | — |
| 08 | LLMs & RAG | Planned | — |
| 09 | MLOps & model serving | Planned | — |

Update this table as you finish each project.

## Repos on GitHub

| Repo | Description |
|------|-------------|
| [nittala_aws](https://github.com/nittala36/nittala_aws) | Cloud / AWS learning |
| [lumen-retail-de-takehome](https://github.com/nittala36/lumen-retail-de-takehome) | Data engineering take-home (not ML) |

## Start a new project

```bash
# Copy the template, then create a matching repo on GitHub
cp -r templates/ml-project-template ../ml-learn-02-your-topic
cd ../ml-learn-02-your-topic
git init && git add . && git commit -m "Start ml-learn-02: your topic"
```

See [templates/ml-project-template/README.md](templates/ml-project-template/README.md) for the standard layout.

## Stack (default)

- Python 3.11+
- Jupyter / VS Code notebooks
- scikit-learn, pandas, matplotlib
- PyTorch or TensorFlow (per project)
- Optional: Hugging Face, LangChain (GenAI repos)
