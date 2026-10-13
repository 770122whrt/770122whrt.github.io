---
layout: page
title: Text2IFC / IFC Repair
description: Language-driven structured 3D editing with explicit execution and verification.
permalink: /projects/text2ifc/
importance: 1
category: agent
---

**Repository:** [770122whrt/text2IFC](https://github.com/770122whrt/text2IFC)

## Motivation

A natural-language instruction often leaves out **which element**, **which property**, or **which action is authorized**. When editing a structured 3D artifact, the wrong change can affect valid geometry, relationships, and downstream workflows. I am interested in how an agent can move from uncertain language and contextual evidence to a precise, inspectable action.

## Technical ideas

- **Language to structure:** Separate interpretation of user intent from an executable artifact operation.
- **Scoped changes:** Represent local edits explicitly, for example with a ChangeSet.
- **Context and clarification:** Explore when an agent should retrieve model context or seek clarification before deciding what to change.
- **Execution and verification:** Combine model proposals with deterministic checks and feedback from the resulting artifact.

IFC is a concrete setting for broader questions around **agent harnesses, retrieval, and grounded action**. See [Research]({{ '/research/' | relative_url }}).
