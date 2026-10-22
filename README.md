### Tanish Gudise
CS + Business @ Carnegie Mellon '27 · RL environments, agent evals, and agent infrastructure

- [pipeline-reliability](https://github.com/TanishGudise/pipeline-reliability): a generator of 282 validated Harbor tasks in 56 problem families where agents fix reliability bugs in LLM data-pipeline code. Every task passes an automated QA gate (reference 1, unfixed 0, wrong/decoy/tamper fixes 0); the grader runs unprivileged in a separate container and writes the reward last.
- [claims-vs-reality](https://github.com/TanishGudise/claims-vs-reality): a pre-registered study comparing coding agents' final reports with an exact system-call record of what they ran. Rubric judges caught at most 1 of 3 misreport mechanisms; the exact record caught all of them.
- [fin-model-edits](https://github.com/TanishGudise/fin-model-edits) · [filing-update-evals](https://github.com/TanishGudise/filing-update-evals): exact-graded agent evals on real SEC filings and credit agreements, recalculated in LibreOffice with perturbed inputs; no LLM judge.
- Merged reliability fixes in agent infrastructure: [Cua](https://github.com/trycua/cua/pull/5194), [Daytona](https://github.com/daytona/clients/pull/353), [Osmosis](https://github.com/Osmosis-AI/osmosis-sdk-python/pull/444), [Composio](https://github.com/ComposioHQ/composio/pull/4903) (co-author).
- Airbnb, AI Infrastructure intern: built a conversational agent for an internal prompt-engineering platform, with RAG, a confirm-before-apply step, OpenTelemetry tracing across the inference pipeline and an eval harness. Full-time return offer.
- [Parameter Golf](https://github.com/TanishGudise/parameter-golf-16mb): 16MB language model trained on 8×H100s with 60+ tracked ablations; briefly topped the leaderboard. The score was flagged in a shared upstream train/val overlap issue, so I treat it as optimistic.
- Also: [Relay](https://github.com/TanishGudise/mongodb-hackathon), a long-horizon agent with crash-safe MongoDB checkpoints (MongoDB NYC hackathon).

Go · Python · TypeScript · C/C++ · Docker · Harbor · PyTorch/CUDA · vLLM · gRPC · PostgreSQL

Open to full-time roles starting January 2027 · [Website](https://tanishgudise.vercel.app/) · [LinkedIn](https://linkedin.com/in/tanish-gudise) · [tgudise@andrew.cmu.edu](mailto:tgudise@andrew.cmu.edu)
