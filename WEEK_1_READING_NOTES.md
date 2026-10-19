# Week 1 reading notes

## Francis & Zhang (2026)

**Citation:** Austin Francis and Cinder Xinde Zhang, “Can AI Match Professional Analysts? Evidence from a Multi-Agent System,” *Finance Research Letters*, vol. 103 (2026), article 110127. DOI: https://doi.org/10.1016/j.frl.2026.110127. The course also points to the authors' SSRN manuscript: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5584131.

**Publicly visible abstract / introduction takeaways:** The study compares 50 matched pairs of AI-generated and Value Line reports for U.S. firms in 2024Q3. Evaluations are blinded and include language-model judges, finance graduate students, and general-population readers. Non-expert readers perceive the AI reports as comparable or better; the MSF-student sample is split and underpowered; LLM-judge results vary by model. Neither AI nor Value Line recommendations outperform an equal-weight 1/N benchmark in the reported portfolio tests. The authors distinguish report quality from investment performance.

**Assigned reading status:** Introduction, Section 3.1, and Section 4 still need to be read from the full text. The public publisher page exposed the abstract, introduction, and section snippets, but not the complete assigned sections in this session. SSRN's page showed an anti-bot security verification. Do not treat the summary above as a substitute for the assigned sections.

## Anthropic, “Building effective agents”

**Read through the end of the first workflow section, “Prompt chaining.”** Source: https://www.anthropic.com/engineering/building-effective-agents

- A **model** is the language model that interprets input and generates output.
- A **harness** is the surrounding software that supplies context and tools, controls the model/tool loop, and handles execution, permissions, and results. This is a practical working definition for the course discussion.
- An **agent** uses a model within that harness to act toward a task. Anthropic distinguishes fixed-path **workflows** (code decides the sequence) from **agents** (the model dynamically directs its process and tool use).
- **Prompt chaining**, the first workflow, breaks a task into fixed steps. Each model call consumes the previous step's output. Programmatic checks can gate progress. It fits tasks that decompose cleanly; smaller calls may improve accuracy at the cost of latency.
- Anthropic's examples are drafting copy and then translating it, or drafting an outline, checking it against criteria, then writing the document from the outline.
