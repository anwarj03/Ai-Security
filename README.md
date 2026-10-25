<div align="center">

<img src="./assets/screenshots/ai-security-logo.png" width="220" alt="AI Security logo">

# AI Security

### A practical study guide across five completed learning modules

**5 modules · 25 source notes**

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






