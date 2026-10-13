---
layout: page
title: EASYkoopman / AUV Control
description: Exploring underwater robot dynamics modeling and learning-based control.
permalink: /projects/easykoopman/
importance: 3
category: robotics
---

**Repository:** [770122whrt/EASYkoopman](https://github.com/770122whrt/EASYkoopman)

## Motivation

Underwater vehicles face nonlinear hydrodynamics, uncertain disturbances, and changing operating conditions. Fixed models may not describe every situation, while learned controllers must still account for physical constraints. I am interested in the broader challenge of **adaptive underwater autonomy** and eventually bridging simulation and real deployment.

## Technical ideas

- **Dynamics representation:** Explore how physical knowledge and Koopman-style lifted representations could complement one another.
- **Model-based control:** Investigate MPC to plan actions using a predictive model while respecting constraints.
- **Learning and adaptation:** Consider how reinforcement learning, such as PPO, and interaction history may contribute to more adaptive behavior.
- **Perception and body-awareness:** Connect dynamics and control to environmental sensing and the robot's own state.

This project is one setting for my interest in [underwater robotic perception, control, and self-evolution]({{ '/research/' | relative_url }}).
