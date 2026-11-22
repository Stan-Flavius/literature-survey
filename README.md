# Literature survey: agentic software engineering for a health-constrained workout planner
## Topic (has changed)

The thesis topic is agentic software engineering. The planned application is a multi-agent system that builds a workout plan for a user with health constraints (for example, high blood pressure). It uses an orchestrator, a profile agent that interprets user requirements, an exercise agent that finds suitable exercises, a planning agent that constructs training schedules, an evaluation agent that chekcks the plan consistency and a rule-checking engine that validates the agents' output against fitness literature. The evaluation will compare the system with a plain LLM output (probably without rag) using a standard LLM benchmark.

## Contents

- [`references.bib`](references.bib): complete bibliographic entries for all sources
- [`papers/`](papers/): PDF of each source (file name = BibTeX key)
- [`notes/`](notes/): one note per source: summary, what is relevant to my work, and what it is used for

## Sources

| Key | Source | PDF | Notes |
|---|---|---|---|
| hassan2025sase | Hassan et al. (2025). Agentic Software Engineering: Foundational Pillars and a Research Roadmap | [pdf](papers/hassan2025sase.pdf) | [notes](notes/hassan2025sase.md) |
| hong2024metagpt | Hong et al. (2024). MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework | [pdf](papers/hong2024metagpt.pdf) | [notes](notes/hong2024metagpt.md) |
| yao2023react | Yao et al. (2023). ReAct: Synergizing Reasoning and Acting in Language Models | [pdf](papers/yao2023react.pdf) | [notes](notes/yao2023react.md) |
| heydari2025pha | Heydari et al. (2025). The Anatomy of a Personal Health Agent | [pdf](papers/heydari2025pha.pdf) | [notes](notes/heydari2025pha.md) |
| li2026fitter | Li et al. (2026). A Guideline-Grounded Multi-Agent Framework for Personalized Exercise Prescription (FITTER), preprint | [pdf](papers/li2026fitter.pdf) | [notes](notes/li2026fitter.md) |
| shin2025planfitting | Shin, Hsieh & Kim (2025). PlanFitting: Personalized Exercise Planning with LLM-driven Conversational Agent | [pdf](papers/shin2025planfitting.pdf) | [notes](notes/shin2025planfitting.md) |
| lewis2020rag | Lewis et al. (2020). Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | [pdf](papers/lewis2020rag.pdf) | [notes](notes/lewis2020rag.md) |
| huang2024selfcorrect | Huang et al. (2024). Large Language Models Cannot Self-Correct Reasoning Yet | [pdf](papers/huang2024selfcorrect.pdf) | [notes](notes/huang2024selfcorrect.md) |
| zheng2023judge | Zheng et al. (2023). Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena | [pdf](papers/zheng2023judge.pdf) | [notes](notes/zheng2023judge.md) |

## Some Notes

- PDFs are the arXiv versions. Sources are open access.
- li2026fitter had not been peer reviewed at the time it was collected.
