# Amine Karcha

Software engineer, backend and AI systems. Nantes, remote.

I build production platforms by day (TypeScript, NestJS, PostgreSQL, Clever Cloud) and
agent-driven tooling the rest of the time. Most of what is public here is about one
question: how to let coding agents do real work without losing control of what they produce.

## Current

- **[jarvis](https://github.com/thelordofpigeons/jarvis)**: a personal daemon that reads my
  repos, task tracker and notes every morning, gates everything through a fail-closed
  privacy tier before any model sees it, and writes one digest. Phase 0 isolation (sandbox,
  kill switch, hostile simulation) and the v1 digest are live on my machine; a local-model
  tier and a work hub are the next phases.
- **[claude-harness-kit](https://github.com/thelordofpigeons/claude-harness-kit)**: the
  hooks, multi-agent workflow scripts, agent definitions and memory scaffold I use with
  Claude Code, sanitized. Gate before code, model routing by job, batched verification,
  adversarial review loops with a convergence guard.
- **[train-speed-profile-surrogate](https://github.com/thelordofpigeons/train-speed-profile-surrogate)**:
  PyTorch surrogate for energy-optimal train speed profiles, built with the LAMIH laboratory
  (UPHF). Physics-informed losses, hard boundary conditions, millisecond inference. Code only,
  the dataset is under NDA.

## Earlier

- **[LS2N-SUMO-Simulator](https://github.com/thelordofpigeons/LS2N-SUMO-Simulator)**: truck
  logistics simulation on SUMO with TraCI, mission scripting and a GUI.
- **[nantes_traffic_archiver](https://github.com/thelordofpigeons/nantes_traffic_archiver)**
  and **[nantes-traffic-analysis](https://github.com/thelordofpigeons/nantes-traffic-analysis)**:
  a collector for Nantes Metropole real-time traffic data and the analysis on top of it.

## How I work with agents

Every coding task passes a gate before any edit: classify, announce, track, then build.
Agents get a model and an effort level per job, run in parallel under a concurrency cap,
and their output goes through batched verification and adversarial review until two rounds
find nothing new. Hooks enforce the parts that should not depend on anyone's discipline.

Engineering degree, INSA Hauts-de-France, 2025. French, English, Arabic.
