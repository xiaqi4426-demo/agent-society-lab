# Agent Society Lab

An open experiment in **persistent LLM agents, emergent specialization, social structure, and artificial societies**.

## Core question

> **Can persistent LLM agents with no predefined roles develop specialization, reputation, relationships, and social organization purely through accumulated interaction history?**

Most multi-agent systems begin by assigning roles:

```text
User
  ↓
Orchestrator
  ├── Researcher
  ├── Coder
  └── Reviewer
```

Agent Society Lab starts from a different question:

```text
World
├── Agent 01
├── Agent 02
├── Agent 03
├── ...
└── Agent N
```

Instead of telling agents what they are, we want to see what they become.

## Starting assumptions

- Agents are **persistent individuals**, not disposable task workers.
- Agents begin without predefined occupations, personalities, or social roles.
- Each agent's **personal memory starts empty**. The underlying language model still has its pretrained knowledge and capabilities.
- Agents may communicate, remember interactions, use tools, ask for help, and delegate work.
- Interaction history persists across tasks.
- The system records what happens without forcing a desired social structure.
- A human can enter the world and interact with any agent directly.

## What we want to observe

We are especially interested in whether the following can emerge rather than being prompted:

- specialization and division of labor
- reputation and trust
- recurring collaboration
- informal leadership or coordination
- social groups and organizations
- shared conventions and norms
- persistent individual differences created by different histories

The goal is not to make agents imitate human society as closely as possible. The more basic question is:

> **What kinds of social structures arise when persistent artificial agents are allowed to accumulate their own histories?**

## Experiment 001

The first experiment focuses on **emergent specialization**.

A small population of initially similar agents will share a minimal environment. They will receive tasks and be allowed to communicate and delegate without being assigned roles such as "coder", "researcher", or "manager".

We will observe whether repeated interaction alone creates stable differences in who does what, who is trusted for what, and who coordinates with whom.

See [Experiment 001](experiments/001-emergent-specialization/README.md).

## Repository structure

```text
agent-society-lab/
├── README.md
├── docs/
│   ├── vision.md
│   └── principles.md
├── experiments/
│   └── 001-emergent-specialization/
│       └── README.md
└── notes/
    └── related-work.md
```

## Status

**Very early.**

This repository currently defines the research direction and the first small experiment. Runtime design and implementation will follow after the experimental assumptions are kept simple enough to test.

## Contributing

Discussion, criticism, related work, experiment design, and implementation ideas are welcome.

If you are interested in persistent agents, multi-agent systems, social simulation, artificial life, or emergent collective behavior, feel free to open an issue.

---

This is an independent research experiment. It may later inform broader work on persistent research agents and agent environments, including Questra.