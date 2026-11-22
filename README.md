# Literature survey: agentic software engineering for a health-constrained workout planner
## Topic (has changed)

The thesis topic is agentic software engineering. The planned application is a multi-agent system that builds a workout plan for a user with health constraints (for example, high blood pressure). It uses an orchestrator, a profile agent that interprets user requirements, an exercise agent that finds suitable exercises, a planning agent that constructs training schedules, an evaluation agent that chekcks the plan consistency and a rule-checking engine that validates the agents' output against fitness literature. The evaluation will compare the system with a plain LLM output (probably without rag) using a standard LLM benchmark.

## Contents

- [`references.bib`](references.bib): complete bibliographic entries for all sources
- [`papers/`](papers/): PDF of each source (file name = BibTeX key)
- [`notes.txt`](notes.txt): one note per source: what is relevant to my work, and what it is used for

## Sources

| Key | Source | PDF | 
|---|---|---|
| hassan2025sase | Hassan et al. (2025). Agentic Software Engineering: Foundational Pillars and a Research Roadmap | [pdf](papers/hassan2025sase.pdf) |
| hong2024metagpt | Hong et al. (2024). MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework | [pdf](papers/hong2024metagpt.pdf) |
| yao2023react | Yao et al. (2023). ReAct: Synergizing Reasoning and Acting in Language Models | [pdf](papers/yao2023react.pdf) |
| heydari2025pha | Heydari et al. (2025). The Anatomy of a Personal Health Agent | [pdf](papers/heydari2025pha.pdf) |
| li2026fitter | Li et al. (2026). A Guideline-Grounded Multi-Agent Framework for Personalized Exercise Prescription (FITTER), preprint | [pdf](papers/li2026fitter.pdf) |
| shin2025planfitting | Shin, Hsieh & Kim (2025). PlanFitting: Personalized Exercise Planning with LLM-driven Conversational Agent | [pdf](papers/shin2025planfitting.pdf) |
| lewis2020rag | Lewis et al. (2020). Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | [pdf](papers/lewis2020rag.pdf) |
| huang2024selfcorrect | Huang et al. (2024). Large Language Models Cannot Self-Correct Reasoning Yet | [pdf](papers/huang2024selfcorrect.pdf) |
| zheng2023judge | Zheng et al. (2023). Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena | [pdf](papers/zheng2023judge.pdf) | 

## Some Notes

- PDFs are the arXiv versions. Sources are open access.
- li2026fitter had not been peer reviewed at the time it was collected.
