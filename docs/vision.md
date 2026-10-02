# Vision

## From task workers to persistent individuals

Most current agent systems are organized around tasks. An agent is created, given a role, performs some work, and disappears.

Agent Society Lab explores a different unit of design: the **persistent agent**.

A persistent agent has a continuing identity and an accumulating history. It can remember previous interactions, form beliefs about other agents, become better at some activities through repeated experience, and participate in relationships that survive individual tasks.

The research question is not simply whether multiple agents can collaborate. The deeper question is:

> What happens when collaboration patterns are not predefined by the designer, but are allowed to emerge from the agents' own histories?

## A minimal artificial society

The long-term direction is to build increasingly rich environments in which agents can:

- exist for long periods of time
- interact with one another directly
- maintain private memories
- use shared tools and resources
- ask for and delegate work
- form persistent relationships
- create groups or organizations
- develop conventions, norms, and specializations
- potentially create new agents in later experiments

The project should begin much smaller than this vision. Early experiments should avoid adding mechanisms merely because they sound socially interesting. Every additional rule makes it harder to know whether an observed behavior actually emerged.

## Model is not agent

- The **model** provides pretrained knowledge and general capabilities.
- The **agent** is the persistent individual created by a model operating inside an environment with identity, memory, tools, relationships, and history.

Two agents may use the same underlying model and still become different individuals because they accumulate different histories.

One of the project's central empirical questions is how far this historical differentiation can go.

## Humans inside the society

A future environment may allow a person to enter the society and simply approach an agent:

> "Can you help me test this strategy?"

That agent may do the work, refuse, ask another agent, delegate parts of the task, or coordinate a group based on relationships and capabilities that already exist in the society.

At that point the interaction is no longer just `human → model`. It becomes `human → persistent agent → social network of agents → world`.

## Relationship to Questra

Agent Society Lab is currently independent from Questra.

Questra may eventually provide a particularly useful real-world environment for this research: a society of persistent agents operating inside a quantitative research world, using data, code, experiments, and verification tools.

For now, keeping the projects partially separate makes the experimental questions easier to study without prematurely forcing them into a product architecture.