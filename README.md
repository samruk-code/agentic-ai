# Agentic AI — DeepLearning.AI

Completed coursework from **[Agentic AI with Andrew Ng](https://www.deeplearning.ai/courses/agentic-ai/)** (DeepLearning.AI). The course covers production-ready agentic design patterns and builds toward a fully autonomous multi-agent research system.

---

## What I Learned

| Pattern | Description |
|---|---|
| **Reflection** | LLMs that critique and iteratively improve their own outputs |
| **Tool Use** | Integrating external APIs (web search, academic databases) via function calling |
| **Planning** | Decomposing complex tasks into executable, adaptable steps |
| **Multi-Agent Systems** | Coordinating specialized agents (planner, researcher, editor) in a pipeline |

---

## Assignments

### Module 2 — Reflection Pattern
**[`M2 Assignment/C1M2_Assignment.ipynb`](M2%20Assignment/C1M2_Assignment.ipynb)**

Built a three-step agentic workflow that simulates reflective thinking:
1. **Draft** — LLM generates an initial essay based on a topic prompt
2. **Reflect** — a separate reasoning step critiques the draft for quality and coherence
3. **Revise** — the LLM rewrites the essay by applying the critique

**Key tools & libraries:** `aisuite`, `openai:gpt-4o`, `python-dotenv`

---

### Module 3 — Tool Use & Reflective Agents
**[`M3 Assignment/C1M3_Assignment.ipynb`](M3%20Assignment/C1M3_Assignment.ipynb)**

Built a research agent that chains external tool calls with self-reflection to produce a structured HTML report:
- Integrated **arXiv** (academic paper search) and **Tavily** (web search) as callable tools
- Wired tools to an LLM via **OpenAI's function-calling API**
- Added a reflection step to critique and improve the generated report
- Rendered the final output as styled HTML

**Key tools & libraries:** `openai` (tool-calling API), `arxiv`, `tavily`, `IPython.display`

---

### Module 5 — Planning & Multi-Agent Workflows
**[`M5 Assignment/C1M5_Assignment.ipynb`](M5%20Assignment/C1M5_Assignment.ipynb)**

Built a full multi-agent research system with three specialized agents:
- **Planning Agent / Writer** — creates an outline and coordinates the overall workflow
- **Research Agent** — gathers external information using arXiv, Tavily, and Wikipedia tools
- **Editor Agent** — reflects on the draft report and provides improvement feedback

**Key tools & libraries:** `aisuite`, `arxiv`, `tavily`, `wikipedia`, `python-dotenv`

---

## Skills Demonstrated

- Designing and implementing agentic pipelines in Python
- Prompt engineering for multi-step LLM workflows
- OpenAI and `aisuite` API usage (chat completions, function/tool calling)
- Integrating real-world data sources: arXiv, Tavily, Wikipedia
- Evaluation and iterative refinement via reflection loops
- Multi-agent coordination and role decomposition

---

## Course Info

- **Instructor:** Andrew Ng (DeepLearning.AI)
- **Level:** Intermediate
- **Platform:** [DeepLearning.AI](https://www.deeplearning.ai/courses/agentic-ai/)
