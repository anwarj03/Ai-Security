<div align="center">

<img src="./assets/screenshots/ai-security-logo.png" width="220" alt="AI Security logo">

# AI Security

### A practical study guide across five completed learning modules

**5 modules · 25 source notes**

<p align="center">
<img src="https://img.shields.io/badge/Python-ML%20language-3776AB?logo=python&amp;logoColor=white" alt="Python ML language"> <img src="https://img.shields.io/badge/PyTorch-framework-EE4C2C?logo=pytorch&amp;logoColor=white" alt="PyTorch framework"> <img src="https://img.shields.io/badge/TensorFlow-framework-FF6F00?logo=tensorflow&amp;logoColor=white" alt="TensorFlow framework"> <img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&amp;logoColor=white" alt="scikit--learn ML"> <img src="https://img.shields.io/badge/Transformers-NLP-7A42A6" alt="Transformers NLP"> <img src="https://img.shields.io/badge/Hugging%20Face-model%20hub-FFD21E?logo=huggingface&amp;logoColor=white" alt="Hugging Face model hub"> <img src="https://img.shields.io/badge/Ollama-local%20inference-222222?logo=ollama&amp;logoColor=white" alt="Ollama local inference"> <img src="https://img.shields.io/badge/MLflow-model%20lifecycle-0194E2?logo=mlflow&amp;logoColor=white" alt="MLflow model lifecycle"> <img src="https://img.shields.io/badge/Safetensors-model%20format-6F42C1" alt="Safetensors model format"> <img src="https://img.shields.io/badge/LangChain-RAG-1C3C3C" alt="LangChain RAG"> <img src="https://img.shields.io/badge/Chroma-vector%20database-D97706" alt="Chroma vector database"> <img src="https://img.shields.io/badge/Qdrant-vector%20database-DC244C" alt="Qdrant vector database"> <img src="https://img.shields.io/badge/NVIDIA-GPU%20compute-76B900?logo=nvidia&amp;logoColor=white" alt="NVIDIA GPU compute"> <img src="https://img.shields.io/badge/OWASP-LLM%20Top%2010-111111" alt="OWASP LLM Top 10"> <img src="https://img.shields.io/badge/MITRE-ATLAS-3C3C3C" alt="MITRE ATLAS"> <img src="https://img.shields.io/badge/EU%20AI%20Act-governance-003399" alt="EU AI Act governance">
</p>

</div>

---

## About

This repository introduces my completed TryHackMe AI Security path and summarizes its five modules.

These are personal learning notes and summaries, not an official TryHackMe publication. Challenge flags and copied answer text are excluded. Use hands-on security techniques only in systems and labs where you have authorization.

## Learning path

| Module | Focus | Notes |
|---|---|---:|
| **01. AI Fundamentals** | How models learn, what data shapes them, and where security starts. | 5 |
| **02. Secure AI Systems** | Architecture, threat modeling, and the exposed AI infrastructure surface. | 5 |
| **03. Prompt Security** | Instruction boundaries, adversarial prompts, and layered defenses. | 5 |
| **04. AI Supply Chain Security** | Model provenance, dependencies, datasets, and infrastructure controls. | 5 |
| **05. Data Poisoning and RAG** | Retrieval boundaries, corpus integrity, and sensitive-data protection. | 5 |

## What the path covers

- **AI foundations:** machine learning, neural networks, LLMs, data provenance, and model lifecycle.
- **Secure AI systems:** architecture, trust boundaries, threat modeling, LLM risks, and infrastructure reconnaissance.
- **Prompt security:** prompt injection, jailbreaks, and layered defenses.
- **AI supply chain:** model provenance, serialization, dependencies, registries, providers, and evaluation gates.
- **RAG and data security:** corpus poisoning, retrieval boundaries, tenant isolation, and sensitive information disclosure.

## Core principles

1. **Map the whole system.** Include data, models, prompts, APIs, vector stores, tools, identities, logs, providers, and dependencies.
2. **Enforce authorization before retrieval and action.** Similarity search and model instructions do not implement access policy.
3. **Constrain model capabilities.** Use least privilege, deterministic validation, safe output handling, and resource limits.
4. **Verify what enters the pipeline.** Track provenance, inspect artifacts and dependencies, and evaluate models in a sandbox.
5. **Monitor and preserve evidence.** Watch retrieval, tool use, egress, and behavior changes while minimizing sensitive logs.
6. **Retest after changes.** Data, model, prompt, provider, and dependency updates can change the threat surface.






