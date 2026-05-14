---
title: "Multi-Agent Supply Chain Competition Simulation"
excerpt: "A multi-agent systems project exploring cooperation, competition, and mixed-game dynamics among LLM agents, RL agents, and heuristic baselines."
collection: portfolio
---

This project builds a three-layer supply-chain simulation environment with six competing retailers, upstream contracts, midstream alliances, promotion budgets, and market-intelligence mechanisms. The environment supports cooperative, adversarial, and mixed-game structures.

I served as team leader and worked on environment design, agent implementation, and experimental code. The project includes LLM agents, DQN, PPO, and heuristic baselines. Local LLMs are called through a Chat Completions style API to generate structured JSON actions.

To improve LLM-agent behavior, I added scenario memory and an Experience RAG mechanism. The experiments compare agent decisions under different market-information settings and model choices.
