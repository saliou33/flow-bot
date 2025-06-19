# Workflows Introduction

FlowBot workflows are built using a visual node-flow interface, supporting various node categories: Trigger, Message, Operator, Variables, and Integration. Each category offers specific types to create complex automation.

## Node Categories

Brief overviews are provided in the [Nodes](../nodes/trigger.md) section.

## Referencing

Use `${{var.name}}` to reference variables, `${{context}}` for global context, and `prev.output`/`prev.meta` for previous node data.

## Execution

Workflows execute based on triggers, with real-time tracking and variable evaluation.
