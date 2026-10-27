### Tanish Gudise
CS + Business @ Carnegie Mellon '27 · GPU kernels and inference, agent infrastructure, and evals

- [Megakernels #15](https://github.com/HazyResearch/Megakernels/issues/15): found a stale read in Hazy Research's Llama-1B megakernel on H100. 26 of 1,000 stock generations produced a wrong token, vs 0 of 1,000 with the fix.
- [ThunderKittens #215](https://github.com/HazyResearch/ThunderKittens/pull/215): `bind_kernel` returned silently when a launch failed, leaving outputs unwritten; it now raises the CUDA error.
- [daft-ai-audit](https://github.com/TanishGudise/daft-ai-audit) · [Daft #7643](https://github.com/Eventual-Inc/Daft/pull/7643): 11 bugs in Daft's AI functions under fault injection, including silent row loss with vLLM on Ray; fixes for the top three.
- [unsloth-zoo #2095](https://github.com/unslothai/unsloth-zoo/pull/2095): MoE QLoRA replay pin on by default, 1.063x faster.
- [silent-failure-bench](https://github.com/TanishGudise/silent-failure-bench) · [session-memory-bench](https://github.com/TanishGudise/session-memory-bench) · [claims-vs-reality](https://github.com/TanishGudise/claims-vs-reality): pre-registered, exact-graded benchmarks for agent silent failures, cross-session memory, and agents' self-reports.
- Merged reliability fixes in agent infrastructure: [Composio](https://github.com/ComposioHQ/composio/pull/4903) (co-author), [Cua](https://github.com/trycua/cua/pull/5194), [Daytona](https://github.com/daytona/clients/pull/353), [Osmosis](https://github.com/Osmosis-AI/osmosis-sdk-python/pull/444).
- Airbnb, AI Infrastructure intern: built a conversational agent for an internal prompt-engineering platform, with RAG, OpenTelemetry tracing and an eval harness. Full-time return offer.
- [Parameter Golf](https://github.com/TanishGudise/parameter-golf-16mb): 16MB language model trained on 8×H100s with 60+ tracked ablations; briefly topped the leaderboard.

Python · C/C++ · CUDA · Triton · Go · TypeScript · PyTorch · vLLM · Ray · Docker

Open to full-time roles starting January 2027 · [Website](https://tanishgudise.vercel.app/) · [LinkedIn](https://linkedin.com/in/tanish-gudise) · [tgudise@andrew.cmu.edu](mailto:tgudise@andrew.cmu.edu)
