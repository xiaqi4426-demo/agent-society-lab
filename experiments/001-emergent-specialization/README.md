# Experiment 001 — Emergent Specialization

## Question

> If initially similar persistent agents receive no predefined occupations or social roles, can stable specialization and division of labor emerge from interaction history alone?

## Why this experiment comes first

Role-based multi-agent systems commonly assign identities such as researcher, coder, reviewer, or manager. This makes coordination easier, but it also makes specialization unsurprising.

Experiment 001 removes that assumption.

We want to know whether repeated experience, reputation, delegation, and path dependence are enough to create persistent differences.

## Initial population

Target: **10–20 agents**.

For the first implementation, agents should be as similar as practical:

- same underlying model, unless model variance is itself being tested
- same initial system rules
- same tool access
- same permissions
- empty personal memory at birth
- no predefined occupation
- no predefined personality
- no predefined social rank

Each agent still has a unique persistent identity.

## Minimal capabilities

Candidate primitives:

- `talk(agent, message)`
- `find_agent(...)`
- `delegate(agent, task)`
- `accept_or_reject(task)`
- `use_tool(...)`
- `remember(...)`

The exact API is not fixed yet.

## Environment

The first world does not need graphics or a spatial map.

It only needs persistent agents, persistent personal memories, a communication mechanism, a task mechanism, a small shared tool set, durable event logging, and a way for a human observer to talk directly to any agent.

## Procedure sketch

1. Create a population of initially similar agents.
2. Give the society a stream of varied tasks.
3. Allow agents to communicate and delegate freely.
4. Do not assign roles or tell agents who is good at what.
5. Preserve memories and relationships across tasks.
6. Record every interaction and relevant state change.
7. Periodically measure whether stable social patterns appear.

## Candidate observations

### Specialization

- Does an agent receive disproportionate numbers of certain task types?
- Does it begin voluntarily selecting those tasks?
- Do other agents describe it as especially capable in that area?
- Does its own self-description change?

### Reputation

- Which agents are repeatedly consulted?
- Do agents remember successful or failed collaborators?
- Does past performance affect future delegation?

### Coordination

- Do some agents increasingly route work between others?
- Do recurring teams form?
- Does an informal coordinator appear without being assigned?

### Path dependence

Run the experiment multiple times with the same initial configuration.

If different agents become specialists in different runs, that would suggest that specialization depends partly on accumulated history rather than fixed initial traits.

## Baseline comparisons

Later runs may compare:

- persistent memory vs. no persistent memory
- free delegation vs. no delegation
- persistent identity vs. disposable agents
- homogeneous initial agents vs. predefined roles

These are later interventions, not requirements for the first run.

## What would count as an interesting result?

Not merely that agents complete tasks.

Interesting outcomes would include stable patterns that were **not directly specified by the system**, such as repeated division of labor, durable reputation, recurring partnerships, emergent coordination roles, or persistent beliefs about other agents' capabilities.

A negative result is also useful. If no stable differentiation appears, the next question is which missing mechanisms are actually necessary.

## Non-goals for Experiment 001

For now, do **not** add:

- reproduction
- economics or currency
- simulated biological needs
- elaborate geography
- governments
- explicit social classes
- predetermined personalities
- large-scale populations

## Next implementation question

Design the smallest runtime that can support persistent identity, memory, communication, delegation, tool use, and complete event logging without embedding social roles into the architecture.