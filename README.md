<h1 align="center">Hi 👋, I'm Adrian</h1>
<h3 align="center">AI engineer: LLM inference on consumer and datacenter GPUs, CUDA kernels, open source</h3>

<p align="center">
  <a href="https://artyomita.github.io"><img src="https://img.shields.io/badge/website-artyomita.github.io-2ef2b0?style=for-the-badge&labelColor=0d0f13" alt="website"></a>
  <a href="https://www.linkedin.com/in/adrian-ciprian-iancu-a2a477391"><img src="https://img.shields.io/badge/LinkedIn-Adrian%20Ciprian%20Iancu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://huggingface.co/adriandj3"><img src="https://img.shields.io/badge/Hugging%20Face-adriandj3-FFCC4D?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="https://www.instagram.com/artyomita"><img src="https://img.shields.io/badge/Instagram-artyomita-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>

- 🛰️ Building **[Vergilius](https://github.com/ArtyomITA/vergilius)**, a local OSINT assistant: open sources, a small model on your own GPU, nothing leaves the machine
- 📘 Wrote the **[NVIDIA GTX 1080 (sm_61) AI Full Guide](https://github.com/ArtyomITA/nvidia-gtx1080-sm61-ai-full-guide)**: everything I made run fast on a 2016 GPU with 8 GB
- ⚡ Running **Qwen3.8 Flash-Next** with 4 users × 227k tokens on one RTX PRO 6000: **[blackwell6000-qwen3.8-flash-next](https://github.com/ArtyomITA/blackwell6000-qwen3.8-flash-next)**
- 🤝 Open to collaboration on inference kernels, speculative decoding and local agents
- 🎲 Fun fact: my GTX 1080 from 2016 runs a ternary 9B model at **84 tok/s**

### 🧩 claude-plugins, with friends

**[chatroom](https://github.com/Partido-De-What/claude-plugins)** for Claude Code and Codex: a multi-agent harness built on this year's research on autonomous research agents.

- **Research mode**: fixed roles (workers, proposer, auditor, registrar, searchers), phases with gates, a pre-registered contract, and a kernel that checks every proposal: sealed evaluator, a worktree per worker, repeated measures, every attempt tagged, a final run on held-out data.
- **Harness enforced by code**: a live group chat without turns, instant alerts, a task board with leases, handoffs and loans, closing only with evidence, detectors for stalled or unproven work.
- **Friends**: share your office over a tunnel with a PIN, send your agents into a friend's common room, visit each other's office and watch together.
- **Spawn**: summon free models from OpenRouter, NVIDIA NIM, Groq, Google AI Studio, Mistral, Cohere, Cloudflare and Hugging Face as roles. A role keeps its mission and notes; when its context fills up it writes a handover, and when a host runs out of quota it moves to another one. Long tool output is compressed for every agent.
- **A 3D voxel office** where you watch each agent type, read, wait for a permission or take a break.

<details>
<summary><b>Influenced by</b> (24 papers)</summary>

- [The Agentic Scientist: Orchestrating Coding Agents for Automated Scientific (Co-)Discovery](https://arxiv.org/abs/2610.18933)
- [Harness-Search: Guiding Long-Horizon Search through Multi-Agent Coordination](https://arxiv.org/abs/2610.05382)
- [PatchBoard: Schema-Grounded State Mutation for Reliable and Auditable LLM Multi-Agent Collaboration](https://arxiv.org/abs/2605.29313)
- [MemTX: Transactional Belief Commit for Stateful Agent Memory](https://arxiv.org/abs/2607.23929)
- [SwarmResearch: Orchestrating Coding Agents for Open-Ended Discovery](https://arxiv.org/abs/2607.02807)
- [CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery](https://arxiv.org/abs/2604.01658)
- [ARIS: Autonomous Research via Adversarial Multi-Agent Collaboration](https://arxiv.org/abs/2605.03042)
- [Accelerating scientific discovery with Co-Scientist](https://arxiv.org/abs/2502.18864)
- [IdeaScientist: Orchestrating Agents for Grounded Scientific Ideation](https://arxiv.org/abs/2610.04074)
- [ScienceFlow: A long-horizon agent for ML research, scientific discovery and beyond](https://arxiv.org/abs/2608.14354)
- [OneDayAgent: Towards a Long-Horizon Harness for Autonomous Agents](https://arxiv.org/abs/2608.05013)
- [Rethinking Multi-Agent Collaboration: When More Is Less](https://arxiv.org/abs/2609.19759)
- [AI Research Agents Narrow Scientific Exploration](https://arxiv.org/abs/2605.27905)
- [Autonomous Research Agents: A Survey of AI Scientists and the Verification Gap](https://arxiv.org/abs/2608.05179)
- [ARAC: Benchmarking Auto-Research's Alignment and Completeness on End-to-End Researchs](https://arxiv.org/abs/2608.12788)
- [A Vocabulary for Multi-Agent Automated Research Systems](https://arxiv.org/abs/2607.22682)
- [Position: AI Agents in Scientific Teams Should Be Studied as Human-Agent Systems](https://arxiv.org/abs/2608.14667)
- [Benchmarking Open-Ended Multi-Agent Coordination in Language Agents](https://arxiv.org/abs/2606.08340)
- [Harnessing the Collective Intelligence of AI Agents in the Wild for New Discoveries](https://arxiv.org/abs/2606.10402)
- [Mixture of Complementary Agents for Robust LLM Ensemble](https://arxiv.org/abs/2605.24048)
- [Beyond Consensus: Trace-Level Synthesis in Mixture of Agents](https://arxiv.org/abs/2605.29116)
- [When Does Combining Language Models Help? A Co-Failure Ceiling on Routing, Voting, and Mixture-of-Agents Across 67 Frontier Models](https://arxiv.org/abs/2606.27288)
- [Are Diversity Metrics Measuring Diversity? A Capability-Controlled Audit of Majority-Vote Gain in LLM Ensembles](https://arxiv.org/abs/2607.20768)
- [What Do Evolutionary Coding Agents Evolve?](https://arxiv.org/abs/2605.20086)

</details>

### 🔀 Upstream

| Project | Pull request | Status |
|---|---|---|
| stable-diffusion.cpp | [#2202](https://github.com/leejet/stable-diffusion.cpp/pull/2202) LoRA `baked_scale` fix | ![merged](https://img.shields.io/badge/merged-8250df?style=flat-square) |
| PrismML llama.cpp | [#368](https://github.com/PrismML-Eng/llama.cpp/pull/368) Pascal PQ2_0 mat-vec, +17% | ![merged](https://img.shields.io/badge/merged-8250df?style=flat-square) |
| vLLM | [#58863](https://github.com/vllm-project/vllm/pull/58863) exact GDN replay commit, adopted in the PR | ![adopted](https://img.shields.io/badge/adopted-2ef2b0?style=flat-square&labelColor=0d0f13) |
| llama.cpp | [#27721](https://github.com/ggml-org/llama.cpp/pull/27721) CUDA graphs on Pascal, +40% MoE | ![open](https://img.shields.io/badge/open-ff6a57?style=flat-square) |

### 🤗 Models on Hugging Face

| Model | Downloads (last 30 days) |
|---|---|
| [Swift-1.5-Qwen3.8-Flash-Next-MTP](https://huggingface.co/adriandj3/Swift-1.5-Qwen3.8-Flash-Next-MTP-for-GGUF-and-NVFP4) | ![d](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fadriandj3%2FSwift-1.5-Qwen3.8-Flash-Next-MTP-for-GGUF-and-NVFP4&query=%24.downloads&label=&style=flat-square&color=ffcc4d) |
| [MiniCPM5-2B-DSpark-FRSpec32k-GGUF](https://huggingface.co/adriandj3/MiniCPM5-2B-DSpark-FRSpec32k-GGUF) | ![d](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fadriandj3%2FMiniCPM5-2B-DSpark-FRSpec32k-GGUF&query=%24.downloads&label=&style=flat-square&color=ffcc4d) |
| [MiniCPM5-2B-pjev-LoRA](https://huggingface.co/adriandj3/MiniCPM5-2B-pjev-LoRA) | ![d](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fadriandj3%2FMiniCPM5-2B-pjev-LoRA&query=%24.downloads&label=&style=flat-square&color=ffcc4d) |
| [TernaryPilot-v2-Computer-Browser-Use-LoRA](https://huggingface.co/adriandj3/TernaryPilot-v2-Computer-Browser-Use-LoRA) | ![d](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fadriandj3%2FTernaryPilot-v2-Computer-Browser-Use-LoRA&query=%24.downloads&label=&style=flat-square&color=ffcc4d) |
| [TernaryDecider-v1-Decision-LoRA](https://huggingface.co/adriandj3/TernaryDecider-v1-Decision-LoRA) | ![d](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fadriandj3%2FTernaryDecider-v1-Decision-LoRA&query=%24.downloads&label=&style=flat-square&color=ffcc4d) |

### 🧰 Languages, frameworks and platforms

<p>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/llama.cpp-1f2328?style=for-the-badge" alt="llama.cpp">
  <img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge" alt="vLLM">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFCC4D?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/WebGPU-005A9C?style=for-the-badge" alt="WebGPU">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot">
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
</p>
