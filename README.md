# Eli — AI Systems for Scientific and Healthcare Reasoning

I build AI systems that help researchers and clinicians get trusted answers to highly specialized questions.

My work focuses on designing **safe, scalable, easy-to-use software for science and healthcare**. Most of what I build sits at the intersection of **agent systems, mechanistic scientific models, and tool ecosystems** that allow AI to interact with real research infrastructure.

---

## ENV

### Ida — Lakatosian Scientific Learning Environment

Ida is an experimental environment for scientific learning and hypothesis refinement inspired by the philosophy of **Imre Lakatos**.

Rather than treating models as static predictors, Ida treats them as **research programs that evolve over time**.

A research program contains:

* **Hard Core** — foundational assumptions that remain fixed
* **Protective Belt** — mechanisms that can change as the system learns
* **Positive Heuristic** — strategies that guide promising directions for refinement

#### Model Fit

Fit describes how well a model explains existing observations.

In Ida this appears as **residual structure** — systematic differences between predicted and observed behavior across interventions and time. These residual signatures are treated as signals of where the model needs improvement.

#### Theoretical Progress

A belt edit is **theoretically progressive** when it produces **new testable predictions** that were not implied by the previous model. In other words, the edit expands the model’s explanatory reach before any experiment is run.

#### Empirical Progress

**Empirical progress** occurs when those predictions are confirmed under experiment or simulation.

#### Population-Level Evaluation

At the population level, Ida compares research programs by looking at:

* prediction novelty
* anomaly resolution
* confirmation rates
* explanatory scope

The goal is to study how scientific programs **evolve, compete, and converge over time**.

---

## TOOLS

### Daedalus — Tool Infrastructure for Scientific Agents

A surprising amount of scientific work is simply **getting tools and environments to run correctly**. Daedalus exists to automate that layer.

Daedalus extends **ToolUniverse’s composable tool ecosystem** through a component called **ToolMaker**, which converts GitHub repositories into **MCP-compatible ToolUniverse tools**.

Conversion can use either:

* **user-supplied YAML tool definitions**, or
* **YAML generated automatically from example Jupyter notebooks** in the repository

For computational biology repositories, Daedalus looks for **explanatory notebooks that demonstrate workflows**, allowing the system to extract runnable tools directly from research code.

The goal is to build a growing ecosystem of **agent-usable scientific tools**.

---

## AGENTS (In Progress)

Current work explores methods for **distilling large models into smaller specialized reasoning agents** that rely on tools and structured workflows rather than monolithic inference.

---

## Interests

Agentic workflows for healthcare and science, Artificial Life, Integration and update of older ML patterns (RFs, SVMs, Logic, Genetic Algorithms) into newer possibilities. 

