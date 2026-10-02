# Principles

These are working principles for early experiments, not permanent laws.

## 1. Start with fewer rules

If we want to study emergence, we should not prompt the answer into existence.

Do not create a "coder agent", "manager agent", or "researcher agent" unless an experiment explicitly studies predefined roles.

Prefer giving agents general capabilities and observing how they use them.

## 2. Persistent identity matters

An agent should survive beyond one task. Its history should matter to future behavior.

Without persistence, reputation, specialization, relationships, and institutions have little room to develop.

## 3. Personal memory and model knowledge are different

An agent's personal memory may begin empty. That does **not** mean the underlying model is a blank slate.

## 4. Let history create differences

Where possible, begin with agents that are similar in model, tools, permissions, and initial state. Then observe whether different interaction histories produce stable behavioral differences.

## 5. Observe before optimizing

The first objective is not benchmark performance.

Record conversations, delegations, tool use, task outcomes, repeated partnerships, who seeks whom for help, and changes in agents' beliefs about themselves and others.

Unexpected behavior is often more valuable than a higher task score.

## 6. Do not anthropomorphize by default

Terms such as friendship, authority, culture, or trust may be useful hypotheses, but they should not be treated as established facts merely because a transcript resembles human behavior.

Prefer operational definitions and measurable traces.

## 7. Keep the first world small

Ten well-observed agents can teach us more than ten thousand poorly understood agents.

## 8. Preserve experimental reproducibility

Environment rules, prompts, model versions, tool sets, seeds where applicable, and important runtime parameters should be recorded for every experiment.

## 9. Separate world rules from interventions

The persistent world should have a small set of stable rules. Experimental interventions should be clearly recorded as interventions rather than quietly baked into agent behavior.

## 10. Build only what the experiment needs

This project is not initially trying to build a complete artificial civilization platform. The runtime should remain simple enough that the social experiment stays legible.