---
title: "UAV 3D Coverage Path Planning Research"
excerpt: "A research project on PPO-guided evolutionary search, symbolic scoring, and 3-cover coverage path planning over discrete 3D viewpoint graphs."
collection: portfolio
date: 2026-05-05
---

This research project studies 3-cover coverage path planning on discrete 3D viewpoint graphs. The goal is to jointly optimize viewpoint selection, camera orientation, and closed-loop routes while reducing energy cost, capture cost, and coverage-quality gaps.

I designed a PPO-guided tensorized GA planner in which PPO outputs continuous control signals for crossover and mutation parameters, while the planner performs rolling-horizon population search. The system also integrates greedy seeding and tabu-style local search.

I implemented an interpretable symbolic scoring module to replace manually designed fitness functions. The project includes multi-seed evaluation on a 26-map benchmark, comparing LGP symbolic scoring, hand-coded scoring, fixed-rate GA, greedy planning, JFR2025-style baselines, and Gurobi reference results.
