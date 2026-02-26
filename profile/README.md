# LabClaw

**Open-source infrastructure for AI-native scientific labs.**

LabClaw provides a standard framework for running scientific workflows with AI agents — from real-time data capture to hypothesis generation to self-improving experimental design.

---

### Why LabClaw

| | Traditional Tools | LabClaw |
|---|---|---|
| **Memory** | Manual notes, lost when people leave | Persistent 3-tier memory that grows with your lab |
| **Instruments** | Disconnected from analysis | Real-time edge monitoring with automated quality checks |
| **Learning** | Redundant experiments, no institutional knowledge | Self-evolving strategies that improve with every experiment |

### Architecture

```
Layer 5  PERSONA    Digital lab staff with training and promotion pipeline
Layer 4  MEMORY     Markdown + Knowledge Graph + Shared Blocks
Layer 3  ENGINE     OBSERVE → HYPOTHESIZE → EXPERIMENT → VALIDATE → EVOLVE
Layer 2  INFRA      FastAPI Gateway, Event Bus, Dashboard, Edge Nodes
Layer 1  HARDWARE   Device Registry, Safety Checker, Protocol Adapters
```

### Projects

| Project | Description |
|---------|-------------|
| [**labclaw**](https://github.com/labclaw/labclaw) | Core platform — Python 3.11+, Apache 2.0 |
| [**awesome-physical-ai-for-science**](https://github.com/labclaw/awesome-physical-ai-for-science) | Curated list of AI systems for scientific laboratories |


### Links

| | |
|---|---|
| Website | [labclaw.org](https://labclaw.org) |
| Docs | [docs.labclaw.org](https://docs.labclaw.org) |
| License | Apache 2.0 |

---

<sub>Open source, expanding to all experimental sciences.</sub>
