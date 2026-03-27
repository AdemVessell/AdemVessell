# Adem Vessell

Solo research and engineering in bounded adaptive control, provenance-backed context management, and edge consensus. I build theory-first, verify on local hardware, and publish with explicit limitations — including what failed.

## Portfolio Map

| Domain | Repo | Status |
|---|---|---|
| **Context Control** | [Continuity Ledger](https://github.com/AdemVessell/continuity-ledger) | Active — bounded adaptive budget controller with provenance spine and backward blame. 90.0%/92.0% on real phi3:mini (750 runs, locked instrument) |
| **Adaptive Control Kernel** | [small-state-control](https://github.com/AdemVessell/small-state-control) | Stable — 263-line zero-dependency Python kernel. Signal → State → Operator → Action → Trace. 63 tests passing |
| **Continual Learning** | [DIFE](https://github.com/AdemVessell/dife) | Prototype — closed-form forgetting equation. Task-level decay envelope for replay scheduling |
| **Replay Scheduling** | [Memory Vortex](https://github.com/AdemVessell/memory-vortex) | Prototype — symbolic replay scheduler with discovered operators. Epoch-level modulation |
| **Edge Consensus** | [Ghost Meadow](https://github.com/AdemVessell/ghost-meadow) | Narrowed — topology-sensitive propagation primitive for partitioned cooperative enclaves. 2160-run bakeoff, blind falsification published · [Live Demo](https://ademvessell.github.io/ghost-meadow/) |
| **Theory** | [Residue Framework](https://github.com/AdemVessell/residue-framework) | Exploratory — history compression by continuation-relevant equivalence. Conceptual lens for compaction semantics |

## How These Connect

Continuity Ledger is the integration point. DIFE provides forgetting dynamics, Memory Vortex provides replay modulation, and both run inside small-state-control's bounded kernel. The provenance spine tracks every context decision. Backward blame traces failures to specific compressions. Ghost Meadow is a potential future distributed outer layer. Residue Framework informs compaction design.

The stack was validated stage by stage — each stage tested before the next was built. Major claims were falsified along the way and published (Ghost Meadow's security thesis, large-filter predictions, Residue's operational contribution). The falsifications are as important as the wins.

## How I Work

I use AI tools (Claude, Grok, ChatGPT, and Gemini) as a multi-model R&D swarm — for rapid iteration, adversarial critique, scaffolding, and test generation. I design the architecture, specify the invariants, and verify results independently. The ideas are mine. The velocity is augmented. I'm transparent about this because I think it's the right way to work and the right way to talk about working.

## Elsewhere

- X: [@AdemVessell](https://x.com/AdemVessell)
- ORCID: [0009-0006-5110-7416](https://orcid.org/0009-0006-5110-7416)
