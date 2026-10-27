###Tanish Gudise

CS + Business @ Carnegie Mellon '27 · GPU kernels and inference, agent infrastructure, and evals

GPU kernels and inference

Megakernels #15: a stale read in Hazy Research's Llama-1B megakernel on H100. 26 of 1,000 stock generations produced a wrong token, vs 0 of 1,000 with a release/acquire fix (p = 2.5×10⁻⁸); repro script and two patches, the cheaper one at +3.8% decode.
ThunderKittens #215: bind_kernel returned silently when a launch failed, leaving outputs unwritten; it now raises with the kernel name and CUDA error.
unsloth-zoo #2095: turns the MoE QLoRA replay pin on by default above a 512 MiB floor (1.063x faster).
Parameter Golf: 16MB language model trained on 8×H100s with 60+ tracked ablations; briefly topped the leaderboard. The upstream eval split was later found to overlap training data; details in the repo.

Reliability of AI systems

daft-ai-audit + Daft #7643: 11 bugs in Daft's AI functions under fault injection (silent row loss with vLLM on Ray, hangs, ignored concurrency limits), fixes for the top three, and a one-command repro.
silent-failure-bench: exactly labeled silent failures in a tool-using agent's traces, three ways to detect them, and whether a fix holds on new cases.
session-memory-bench: which kind of memory from earlier agent sessions helps the next coding session, graded by hidden tests only.
claims-vs-reality: a pre-registered study comparing coding agents' final reports with an exact system-call record of what they ran. Rubric judges caught at most 1 of 3 misreport mechanisms; the exact record caught all of them.
pipeline-reliability: 282 validated Harbor tasks in 56 problem families where agents fix reliability bugs in LLM data-pipeline code, each passing an automated QA gate.
Merged reliability fixes in agent infrastructure: Composio (co-author), Cua, Daytona, Osmosis.

Experience

Airbnb, AI Infrastructure intern: built a conversational agent for an internal prompt-engineering platform, with RAG, a confirm-before-apply step, OpenTelemetry tracing across the inference pipeline and an eval harness. Full-time return offer.
Also: fin-model-edits · filing-update-evals (exact-graded agent evals on real SEC filings) · Relay (MongoDB NYC hackathon).

Python · C/C++ · CUDA · Triton · Go · TypeScript · Rust · PyTorch · vLLM · Ray · Docker

Open to full-time roles starting January 2027 · Website · LinkedIn · tgudise@andrew.cmu.edu
