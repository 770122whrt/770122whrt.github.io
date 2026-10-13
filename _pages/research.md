---
layout: page
title: research
permalink: /research/
description: Research interests and current directions.
nav: true
nav_order: 2
---

My work and interests fall into two broad research directions. The topics below describe **research questions and areas of exploration**, not necessarily completed capabilities.

## Reinforcement Learning & Robot Control

I am interested in combining learning-based policies with model-based control, especially for underwater robots:

- **Reinforcement learning:** PPO and other policy optimization methods for decision-making and control.
- **Dynamics modeling:** Koopman representations, physical models, and their combinations for predicting nonlinear dynamics.
- **Planning and control:** Model predictive control (MPC), uncertainty and robustness under changing dynamics.
- **Sim-to-real:** Understanding what transfers from simulation, what fails, and how to improve cross-condition or cross-platform generalization.

A related project is [EASYkoopman / AUV Control]({{ '/projects/easykoopman/' | relative_url }}). Its currently documented results are **simulation-based prediction experiments**, not completed real-robot transfer.

## AI Agents, Harness, Memory & Retrieval

I am also interested in how to build agents that can execute long or complex tasks with reliable context and tool use:

- **Multi-agent systems:** Role specialization, communication, coordination, and workflow execution.
- **Agent harness:** Tool interfaces, orchestration, state tracking, feedback loops, and execution boundaries.
- **Memory and retrieval:** Selecting relevant context and experiences, and deciding what information should be retrieved, retained, or revisited.
- **Structured action and verification:** Converting natural-language intentions into constrained changes, followed by checks against the resulting artifact.

Related projects include [WeAgent]({{ '/projects/weagent/' | relative_url }}) and [Text2IFC / IFC Repair]({{ '/projects/text2ifc/' | relative_url }}).
