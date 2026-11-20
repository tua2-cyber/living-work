# Living Work design diagrams

[Back to the project overview](README.md)

## Moving parts of Living Work

In the local workspace design, one curriculum can guide several plans. The parent chooses a plan to teach, then decides which moments are worth remembering. The notebook is private teaching memory. A parent can express a new learning goal in their own words for a later plan.

```mermaid
flowchart LR
  A["Curriculum choices: books, goals, rhythm"] --> B["Plans and revisions"]
  B --> C["Parent chooses a plan to teach"]
  C --> D["Teach and reflect"]
  D --> E["Private teaching notebook"]
  E -.->|"Parent chooses a learning goal"| A
```

## How a plan is assembled

The planner starts with a reviewed brief and a shared progression for the block. The preparation guide and detailed weeks build on that progression. The result opens as a draft the parent can change.

```mermaid
flowchart TD
  A["Parent sets a goal, chooses books and available time"] --> B["Review the exact brief"]
  B -->|Send| C["Map the books and weekly progression"]
  C --> D["Draft parent preparation"]
  C --> E["Draft detailed weekly lessons"]
  D --> F["Assemble a draft"]
  E --> F
  F --> G["Parent reviews or revises the draft"]
  G -->|Approve| H["Open for teaching"]
```

The planning request uses the reviewed educational brief and source guidance. Private notebook entries and learner work stay on the family’s device.

## Looking back and carrying a choice forward

This is a proposed design. A parent might revisit something they marked during a writing block, then decide whether to use the same practice when writing about an experiment. The original teaching record stays private. The parent can use, edit, or leave the idea.

```mermaid
flowchart TD
  A["Parent chooses Look back at this block"] --> B["Find a moment the parent marked to revisit"]
  B --> C["Show the record and why it surfaced"]
  C --> D{"Carry this idea forward?"}
  D -->|Leave it| E["Keep the record with its original block"]
  D -->|Keep or edit| F["Write a learning goal in the parent's words"]
  F --> G["Review the goal in the next planning brief"]
  G -->|Send| H["Share the reviewed brief with the planner"]
```

An MCP connection could make that reviewed brief available to the planner. The parent would see the exact information before deciding to share it.
