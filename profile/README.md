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
| [**device-use**](https://github.com/labclaw/device-use) | Like browser-use, but for scientific instruments — AI agents operate any device through its GUI |
| [**device-skills**](https://github.com/labclaw/device-skills) | Modular, standardized device skills for labclaw & device-use |
| [**labwork-web**](https://github.com/labclaw/labwork-web) | Minimal standalone web UI for LabClaw ecosystem |
| [**lab-manager**](https://github.com/labclaw/lab-manager) | AI lab manager |
| [**dollar-lab**](https://github.com/labclaw/dollar-lab) | Reproducible demo: AI autonomously optimizes two-photon microscopy via closed-loop control |
| [**awesome-physical-ai-for-science**](https://github.com/labclaw/awesome-physical-ai-for-science) | Curated list of AI systems for scientific laboratories |


### Links

| | |
|---|---|
| Website | [labclaw.org](https://labclaw.org) |
| Docs | [docs.labclaw.org](https://docs.labclaw.org) |
| License | Apache 2.0 |

---

<sub>Open source, expanding to all experimental sciences.</sub>
