---
layout: page
title: EASYkoopman / AUV Control
description: Koopman and physics-based prediction for underwater robot control research.
permalink: /projects/easykoopman/
importance: 3
category: robotics
---

**Repository:** [770122whrt/EASYkoopman](https://github.com/770122whrt/EASYkoopman)

This project explores Koopman-based dynamics representations and model predictive control (MPC) in an EasyUUV / Isaac-based underwater robot simulation environment.

The documented comparison includes frozen physical dynamics, a fully lifted Koopman predictor, and a hybrid physics + Koopman predictor.

### Current evidence and limits

In the repository's reported cross-condition experiment, a hybrid predictor trained using a 20% added quadratic-drag condition was evaluated on a 30% drag condition. Compared with the frozen physics baseline, the reported prediction errors for depth and attitude were **53.31% and 58.91% lower**, respectively.

This is **limited simulation-based prediction evidence** under the reported setup. It does not establish successful closed-loop control generalization or sim-to-real transfer.

My broader interests include PPO, robust robot control, and sim-to-real adaptation; these should not be confused with capabilities already demonstrated in this repository.
