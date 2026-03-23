# Awesome Workflow Optimization for LLM Agents

A curated list of papers on workflow optimization for LLM agents.

This repository accompanies the survey paper **From Static Templates to Dynamic Runtime Graphs: A Survey of Workflow Optimization for LLM Agents**.  
Survey paper: [From Static Templates to Dynamic Runtime Graphs: A Survey of Workflow Optimization for LLM Agents](https://doi.org/10.13140/RG.2.2.23159.48806)

This list focuses on papers whose main contribution is workflow optimization. To keep the repository concise and method-centric, it does not aim to cover general survey papers, benchmarks, datasets, or framework/tooling papers.

The list is organized by **when workflow structure is determined**: static optimization and dynamic optimization.

## Table of Contents

- [Static Optimization](#static-optimization)
  - [Offline template search over constrained design spaces](#offline-template-search-over-constrained-design-spaces)
  - [Node-level optimization inside fixed scaffolds](#node-level-optimization-inside-fixed-scaffolds)
  - [Joint optimization of structure and local configuration](#joint-optimization-of-structure-and-local-configuration)
  - [Verifiability in static workflow optimization](#verifiability-in-static-workflow-optimization)
- [Dynamic Optimization and Runtime Adaptation](#dynamic-optimization-and-runtime-adaptation)
  - [Selection and pruning as the lightest form of runtime adaptation](#selection-and-pruning-as-the-lightest-form-of-runtime-adaptation)
  - [Construct-then-execute: pre-execution workflow generation](#construct-then-execute-pre-execution-workflow-generation)
  - [In-execution editing: interleaving execution with structural change](#in-execution-editing-interleaving-execution-with-structural-change)
- [Contributing](#contributing)
- [Citation](#citation)
- [Star History](#star-history)

## Static Optimization

### Offline template search over constrained design spaces

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| AFlow: Automating Agentic Workflow Generation | 2025 | [Paper](https://openreview.net/forum?id=z5uVAKwmjf) | [GitHub](https://github.com/FoundationAgents/AFlow) ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationAgents/AFlow?style=social) |
| Automated Design of Agentic Systems | 2025 | [Paper](https://openreview.net/forum?id=t9U3LW7JVX) | [GitHub](https://github.com/ShengranHu/ADAS) ![GitHub Repo stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=social) |
| A²Flow: Automating Agentic Workflow Generation via Self-Adaptive Abstraction Operators | 2025 | [Paper](https://arxiv.org/abs/2511.20693) | [GitHub](https://github.com/pandawei-ele/A2FLOW) ![GitHub Repo stars](https://img.shields.io/github/stars/pandawei-ele/A2FLOW?style=social) |
| SEW: Self-Evolving Agentic Workflows for Automated Code Generation | 2025 | [Paper](https://arxiv.org/abs/2505.18646) | - |
| Evolutionary Generation of Multi-Agent Systems | 2026 | [Paper](https://arxiv.org/abs/2602.06511) | - |

### Node-level optimization inside fixed scaffolds

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines | 2023 | [Paper](https://arxiv.org/abs/2310.03714) | [GitHub](https://github.com/stanfordnlp/dspy) ![GitHub Repo stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=social) |
| Large Language Models as Optimizers | 2023 | [Paper](https://arxiv.org/abs/2309.03409) | [GitHub](https://github.com/google-deepmind/opro) ![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/opro?style=social) |
| EvoPrompt: Connecting LLMs with Evolutionary Algorithms Yields Powerful Prompt Optimizers | 2023 | [Paper](https://arxiv.org/abs/2309.08532) | [GitHub](https://github.com/beeevita/EvoPrompt) ![GitHub Repo stars](https://img.shields.io/github/stars/beeevita/EvoPrompt?style=social) |
| CAPO: Cost-Aware Prompt Optimization | 2025 | [Paper](https://arxiv.org/abs/2504.16005) | [GitHub](https://github.com/finitearth/capo) ![GitHub Repo stars](https://img.shields.io/github/stars/finitearth/capo?style=social) |
| GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning | 2025 | [Paper](https://arxiv.org/abs/2507.19457) | [GitHub](https://github.com/gepa-ai/gepa) ![GitHub Repo stars](https://img.shields.io/github/stars/gepa-ai/gepa?style=social) |
| Optima: Optimizing Effectiveness and Efficiency for LLM-Based Multi-Agent System | 2025 | [Paper](https://aclanthology.org/2025.findings-acl.601/) | [GitHub](https://github.com/thunlp/Optima) ![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/Optima?style=social) |

### Joint optimization of structure and local configuration

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies | 2025 | [Paper](https://arxiv.org/abs/2502.02533) | - |
| Learning Multi-Agent Communication from Graph Modeling Perspective | 2024 | [Paper](https://arxiv.org/abs/2405.08550) | [GitHub](https://github.com/charleshsc/CommFormer) ![GitHub Repo stars](https://img.shields.io/github/stars/charleshsc/CommFormer?style=social) |
| Maestro: Joint Graph & Config Optimization for Reliable AI Agents | 2025 | [Paper](https://arxiv.org/abs/2509.04642) | - |

### Verifiability in static workflow optimization

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| MermaidFlow: Redefining Agentic Workflow Generation via Safety-Constrained Evolutionary Programming | 2025 | [Paper](https://arxiv.org/abs/2505.22967) | [GitHub](https://github.com/chengqiArchy/MermaidFlow) ![GitHub Repo stars](https://img.shields.io/github/stars/chengqiArchy/MermaidFlow?style=social) |
| VFlow: Discovering Optimal Agentic Workflows for Verilog Generation | 2025 | [Paper](https://arxiv.org/abs/2504.03723) | - |

## Dynamic Optimization and Runtime Adaptation

### Selection and pruning as the lightest form of runtime adaptation

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| Cut the Crap: An Economical Communication Pipeline for LLM-Based Multi-Agent Systems | 2025 | [Paper](https://openreview.net/forum?id=LkzuPorQ5L) | [GitHub](https://github.com/yanweiyue/AgentPrune) ![GitHub Repo stars](https://img.shields.io/github/stars/yanweiyue/AgentPrune?style=social) |
| Adaptive Graph Pruning for Multi-Agent Communication | 2025 | [Paper](https://arxiv.org/abs/2506.02951) | [GitHub](https://github.com/Resurgamm/AGP) ![GitHub Repo stars](https://img.shields.io/github/stars/Resurgamm/AGP?style=social) |
| DAGP: Difficulty-Aware Graph Pruning for LLM-Based Multi-Agent Systems | 2025 | [Paper](https://doi.org/10.1145/3746252.3760954) | - |
| AgentDropout: Dynamic Agent Elimination for Token-Efficient and High-Performance LLM-Based Multi-Agent Collaboration | 2025 | [Paper](https://arxiv.org/abs/2503.18891) | [GitHub](https://github.com/wangzx1219/AgentDropout) ![GitHub Repo stars](https://img.shields.io/github/stars/wangzx1219/AgentDropout?style=social) |
| A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration | 2023 | [Paper](https://arxiv.org/abs/2310.02170) | [GitHub](https://github.com/SALT-NLP/DyLAN) ![GitHub Repo stars](https://img.shields.io/github/stars/SALT-NLP/DyLAN?style=social) |
| MasRouter: Learning to Route LLMs for Multi-Agent Systems | 2025 | [Paper](https://aclanthology.org/2025.acl-long.757/) | [GitHub](https://github.com/yanweiyue/masrouter) ![GitHub Repo stars](https://img.shields.io/github/stars/yanweiyue/masrouter?style=social) |
| SkillOrchestra: Learning to Route Agents via Skill Transfer | 2026 | [Paper](https://arxiv.org/abs/2602.19672) | [GitHub](https://github.com/jiayuww/SkillOrchestra) ![GitHub Repo stars](https://img.shields.io/github/stars/jiayuww/SkillOrchestra?style=social) |

### Construct-then-execute: pre-execution workflow generation

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| Difficulty-Aware Agentic Orchestration for Query-Specific Multi-Agent Workflows | 2025 | [Paper](https://arxiv.org/abs/2509.11079) | - |
| Assemble Your Crew: Automatic Multi-Agent Communication Topology Design via Autoregressive Graph Generation | 2025 | [Paper](https://arxiv.org/abs/2507.18224) | [GitHub](https://github.com/Shiy-Li/ARG-Designer) ![GitHub Repo stars](https://img.shields.io/github/stars/Shiy-Li/ARG-Designer?style=social) |
| G-Designer: Architecting Multi-Agent Communication Topologies via Graph Neural Networks | 2025 | [Paper](https://openreview.net/forum?id=LpE54NUnmO) | [GitHub](https://github.com/yanweiyue/GDesigner) ![GitHub Repo stars](https://img.shields.io/github/stars/yanweiyue/GDesigner?style=social) |
| Dynamic Generation of Multi-LLM Agents Communication Topologies with Graph Diffusion Models | 2025 | [Paper](https://arxiv.org/abs/2510.07799) | - |
| Multi-Agent Architecture Search via Agentic Supernet | 2025 | [Paper](https://openreview.net/forum?id=imcyVlzpXh) | [GitHub](https://github.com/bingreeky/MaAS) ![GitHub Repo stars](https://img.shields.io/github/stars/bingreeky/MaAS?style=social) |
| ScoreFlow: Mastering LLM Agent Workflows via Score-Based Preference Optimization | 2025 | [Paper](https://arxiv.org/abs/2502.04306) | [GitHub](https://github.com/Gen-Verse/ScoreFlow) ![GitHub Repo stars](https://img.shields.io/github/stars/Gen-Verse/ScoreFlow?style=social) |
| FlowReasoner: Reinforcing Query-Level Meta-Agents | 2025 | [Paper](https://arxiv.org/abs/2504.15257) | [GitHub](https://github.com/sail-sg/FlowReasoner) ![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/FlowReasoner?style=social) |
| Workflow-R1: Group Sub-sequence Policy Optimization for Multi-Turn Workflow Construction | 2026 | [Paper](https://arxiv.org/abs/2602.01202) | [GitHub](https://github.com/kongmingze/Workflow-R1) ![GitHub Repo stars](https://img.shields.io/github/stars/kongmingze/Workflow-R1?style=social) |
| AutoFlow: Automated Workflow Generation for Large Language Model Agents | 2024 | [Paper](https://arxiv.org/abs/2407.12821) | [GitHub](https://github.com/agiresearch/AutoFlow) ![GitHub Repo stars](https://img.shields.io/github/stars/agiresearch/AutoFlow?style=social) |
| WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models | 2024 | [Paper](https://arxiv.org/abs/2411.05451) | [GitHub](https://github.com/OpenBMB/WorkflowLLM) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/WorkflowLLM?style=social) |
| RobustFlow: Towards Robust Agentic Workflow Generation | 2025 | [Paper](https://arxiv.org/abs/2509.21834) | [GitHub](https://github.com/DEFENSE-SEU/RobustFlow) ![GitHub Repo stars](https://img.shields.io/github/stars/DEFENSE-SEU/RobustFlow?style=social) |
| ComfyUI-R1: Exploring Reasoning Models for Workflow Generation | 2025 | [Paper](https://arxiv.org/abs/2506.09790) | - |
| AutoAgents: A Framework for Automatic Agent Generation | 2024 | [Paper](https://www.ijcai.org/proceedings/2024/3) | [GitHub](https://github.com/Link-AGI/AutoAgents) ![GitHub Repo stars](https://img.shields.io/github/stars/Link-AGI/AutoAgents?style=social) |

### In-execution editing: interleaving execution with structural change

| Title | Year | Paper | Code |
| --- | --- | --- | --- |
| DyFlow: Dynamic Workflow Framework for Agentic Reasoning | 2025 | [Paper](https://arxiv.org/abs/2509.26062) | - |
| AgentConductor: Topology Evolution for Multi-Agent Competition-Level Code Generation | 2026 | [Paper](https://arxiv.org/abs/2602.17100) | - |
| Aime: Towards Fully-Autonomous Multi-Agent Framework | 2025 | [Paper](https://arxiv.org/abs/2507.11988) | - |
| AOrchestra: Automating Sub-Agent Creation for Agentic Orchestration | 2026 | [Paper](https://arxiv.org/abs/2602.03786) | [GitHub](https://github.com/FoundationAgents/AOrchestra) ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationAgents/AOrchestra?style=social) |
| MetaGen: Self-Evolving Roles and Topologies for Multi-Agent LLM Reasoning | 2026 | [Paper](https://arxiv.org/abs/2601.19290) | - |
| ProAgent: From Robotic Process Automation to Agentic Process Automation | 2023 | [Paper](https://arxiv.org/abs/2311.10751) | [GitHub](https://github.com/OpenBMB/ProAgent) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/ProAgent?style=social) |
| Flow: Modularized Agentic Workflow Automation | 2025 | [Paper](https://openreview.net/forum?id=sLKDbuyq99) | [GitHub](https://github.com/tmllab/2025_iclr_flow) ![GitHub Repo stars](https://img.shields.io/github/stars/tmllab/2025_iclr_flow?style=social) |
| EvoFlow: Evolving Diverse Agentic Workflows on the Fly | 2025 | [Paper](https://arxiv.org/abs/2502.07373) | - |
| DebFlow: Automating Agent Creation via Agent Debate | 2025 | [Paper](https://arxiv.org/abs/2503.23781) | - |
| QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks | 2025 | [Paper](https://arxiv.org/abs/2501.17167) | [GitHub](https://github.com/amazon-science/QualityFlow) ![GitHub Repo stars](https://img.shields.io/github/stars/amazon-science/QualityFlow?style=social) |


## Contributing

Contributions are welcome.

Please edit `README.md` directly and follow these rules:

1. Only include papers whose main contribution is workflow optimization.
2. Put each paper in exactly one subsection.
3. Prefer official paper pages and official code repositories.
4. Use `-` in the `Code` column if no official repository can be verified.
5. Keep the table format as `Title | Year | Paper | Code`.
6. If a paper could fit multiple subsections, place it in the subsection that best matches its main contribution.

## Citation

If you find this repository or the accompanying survey helpful, please cite:

```bibtex
@article{yue2026workflowsurvey,
  title        = {From Static Templates to Dynamic Runtime Graphs: A Survey of Workflow Optimization for LLM Agents},
  author       = {Yue, Ling and Bhandari, Kushal Raj and Ko, Ching-Yun and Patel, Dhaval and Lin, Shuxin and Zhou, Nianjun and Gao, Jianxi and Chen, Pin-Yu and Pan, Shaowu},
  year         = {2026},
  note         = {Preprint},
  doi          = {10.13140/RG.2.2.23159.48806},
  url          = {https://doi.org/10.13140/RG.2.2.23159.48806}
}
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=IBM/awesome-agentic-workflow-optimization&type=Date&from=2026-03-19)](https://www.star-history.com/#IBM/awesome-agentic-workflow-optimization&Date)
