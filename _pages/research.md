---
layout: page
title: research
permalink: /research/
description: Research questions and possible approaches in underwater robotics and AI agents.
nav: true
nav_order: 2
---

I am interested in two areas: **underwater robot intelligence** and **AI agent systems**. For each direction, I start from a research problem rather than a particular algorithm or a project's benchmark results.

## Underwater Robotics: Perception, Control & Self-Evolution

### Motivation

Underwater robots operate with **partial observations**, nonlinear dynamics, unknown disturbances, and limited opportunities for external guidance. A control strategy that works in simulation may not transfer well to a different environment or physical platform. Beyond completing a single task, I want to understand how an underwater robot can **adapt during a mission** and improve from accumulated interaction.

### Research questions

- How should robots combine **environmental perception** with their **own body state, motion constraints, and control history**?
- How can perception and control remain effective when dynamics or environmental conditions change?
- What should be adapted quickly during operation, and what should evolve more slowly from experience?
- How can representations and policies become more transferable across simulation conditions and real deployments?

### Ideas and possible approaches

I want to explore **perception- and body-aware state representations**, combining local observations, robot attitude, velocity, and past actions where useful. For control, I am interested in combining **physics-informed or Koopman-based dynamics models** with **model predictive control (MPC)**, and investigating **reinforcement learning** methods such as **PPO** where interaction-driven policy learning can help.

A possible research direction distinguishes **fast adaptation** to changing local conditions from **slower experience-driven updates** to models, policies, or reusable knowledge. The larger aim is to connect perception, control feedback, and evolving experience, rather than optimizing any single algorithm in isolation.

Related exploration: [EASYkoopman / AUV Control]({{ '/projects/easykoopman/' | relative_url }}).

## AI Agents: Harness, Memory & Retrieval

### Motivation

Long-running agents operate across tools, documents, uncertain requests, and changing task state. Relevant context may be lost or buried, and an agent may act without sufficient information. Multiple agents bring additional questions of handoff, responsibility, and coordination.

### Research questions

- When should an agent **retrieve information, consult memory, ask for clarification, or act**?
- Which parts of task state and tool execution should be maintained by an **agent harness** rather than squeezed into a prompt?
- How can retrieved evidence and previous interactions be stored with enough structure and provenance to remain useful?
- How should multiple agents coordinate work without redundant or contradictory actions?

### Ideas and possible approaches

I am interested in harnesses that make **task state, evidence, tool interaction, and feedback** explicit. **Retrieval** can locate relevant external context; **memory** can retain reusable experiences and decisions. A useful system should decide what to surface, rather than indiscriminately appending all available text.

I also want to explore **multi-agent orchestration**, feedback-driven revision, and the distinction between uncertain interpretation and a well-grounded action.

Related explorations: [WeAgent]({{ '/projects/weagent/' | relative_url }}) and [Text2IFC / IFC Repair]({{ '/projects/text2ifc/' | relative_url }}).
