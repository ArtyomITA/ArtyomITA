<h1 align="center">Hi 👋, I'm Adrian</h1>
<h3 align="center">AI/ML engineer · AI tech lead at KeyTech SRL<br>Training and kernels on Blackwell, fast local inference on a GTX 1080 and inside a VR headset, agents that correct themselves</h3>

<p align="center">
  <a href="https://artyomita.github.io"><img src="https://img.shields.io/badge/website-artyomita.github.io-4fd6b9?style=for-the-badge&labelColor=0a1514" alt="website"></a>
  <a href="https://www.linkedin.com/in/adrian-ciprian-iancu-a2a477391"><img src="https://img.shields.io/badge/LinkedIn-Adrian%20Ciprian%20Iancu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://huggingface.co/adriandj3"><img src="https://img.shields.io/badge/Hugging%20Face-adriandj3-FFCC4D?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="https://www.instagram.com/artyomita"><img src="https://img.shields.io/badge/Instagram-artyomita-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
</p>

- 🥽 **[Optimized kernels for VR](https://github.com/ArtyomITA/lfm3-omni-voice-quest3s)**: LFM3-Omni-2B speaks in real time inside a Meta Quest 3S, from 0.56x to **1.17x** real time with llama.cpp. No cloud, no PC, no cable
- 🛰️ **[Vergilius](https://github.com/ArtyomITA/vergilius)**, a local OSINT assistant: one model, **LFM3 1C** (my merge of LFM3-1.7B and LFM3-VL-2B), writes, uses tools, looks at the screen and clicks. Nothing leaves the machine
- ⚡ Training and kernels on **Blackwell**: Qwen3.8 Flash-Next with 4 users × 227k tokens on one RTX PRO 6000, exact kernels: **[blackwell6000-qwen3.8-flash-next](https://github.com/ArtyomITA/blackwell6000-qwen3.8-flash-next)**
- 📘 Wrote the **[NVIDIA GTX 1080 (sm_61) AI Full Guide](https://github.com/ArtyomITA/nvidia-gtx1080-sm61-ai-full-guide)**: everything I made run fast on a 2016 GPU with 8 GB
- 🤝 Open to collaboration on inference and training kernels, speculative decoding, other inference engines and local agents
- 🎲 Fun fact: my GTX 1080 from 2016 runs a ternary 9B model at **84 tok/s**

### 🧩 chatroom, a multi-agent orchestrator

**[chatroom](https://github.com/Partido-De-What/claude-plugins)** for Claude Code and Codex: **auto-harness**, **research** and a **model council** in one plugin. Built on **37 papers** and on ideas from Qwen Code, DeepSeek, Hermes and Pi. Token-efficient by design.

- **Auto-harness**: the room learns from its own mistakes. Repeated failures become lessons on trial, kept only if they hold in a second room; skills write themselves and enter only after their check passes.
- **Research**: one file, a sealed evaluator, a number to beat. Workers in their own worktrees, repeated measures, every attempt tagged, a final run on held-out data. One overnight room made a text-to-speech kernel on a Meta Quest 3S 2.1x faster.
- **Model council**: one command puts your situation in front of 10 free models for improvements, a fact-check and ideas.
- **Rules in code, not in the prompt**: a plan closes only when every agent has said what it checked, a task is done only with a real proof, and agents stay quiet unless a message concerns them.
- **Claude Code and Codex in the same room**, other harnesses next. Lend your agents to a friend with a PIN, summon free models as roles, and watch everyone in a 3D voxel office.

<details>
<summary><b>Built on</b> 37 papers</summary>

**🧠 Auto-harness · 11 papers on skills that create and improve themselves**

- [Voyager](https://arxiv.org/abs/2305.16291)
- [SkillsBench](https://arxiv.org/abs/2602.12670)
- [SoK: Agentic Skills](https://arxiv.org/abs/2602.20867)
- [AutoSkill](https://arxiv.org/abs/2603.01145)
- [EvoSkill](https://arxiv.org/abs/2603.02766)
- [SkillX](https://arxiv.org/abs/2604.04804)
- [SkillMaster](https://arxiv.org/abs/2605.08693)
- [SkillsVote](https://arxiv.org/abs/2605.18401)
- [MUSE-Autoskill](https://arxiv.org/abs/2605.27366)
- [SkillAxe](https://arxiv.org/abs/2606.10546)
- [SAGE](https://arxiv.org/abs/2512.17102)

**💬 Chatroom · 8 papers on how agent teams coordinate and what it costs**

- [When Agents Coordinate: Measuring Coordination in Multi-Agent AI Coding](https://arxiv.org/abs/2608.16801)
- [When Parallelism Pays Off: Cohesion-Aware Task Partitioning for Multi-Agent Coding](https://arxiv.org/abs/2606.00953)
- [Token Reduction Is Not Cost Reduction](https://arxiv.org/abs/2607.12161)
- [Do We Need Complex Topology Control? Distinct-Peer Random Routing Improves Cost-Efficiency in Sparse Multi-Agent Debate](https://arxiv.org/abs/2609.27150)
- [The Compaction Cliff in Long-Running AI Agent Memory](https://arxiv.org/abs/2608.22752)
- [What Does Context Compression Cost an Agent? Interaction Costs Unrevealed by Task-Completion Metrics](https://arxiv.org/abs/2608.16370)
- [SoL-Pi: Recursively Scaling Auto-Research Loops for Efficient Agent Harness](https://arxiv.org/abs/2609.20519)
- [Persistent LLM Orchestration of Heterogeneous Robot Teams via Partial Delegation to Multi-Agent Protocols](https://arxiv.org/abs/2610.15224)

**🔬 Research · 18 papers on AI scientists, honest measurement and reward hacking**

- [The Agentic Scientist: Orchestrating Coding Agents for Automated Scientific (Co-)Discovery](https://arxiv.org/abs/2610.18933)
- [Harness-Search: Guiding Long-Horizon Search through Multi-Agent Coordination](https://arxiv.org/abs/2610.05382)
- [PatchBoard: Schema-Grounded State Mutation for Reliable and Auditable LLM Multi-Agent Collaboration](https://arxiv.org/abs/2605.29313)
- [MemTX: Transactional Belief Commit for Stateful Agent Memory](https://arxiv.org/abs/2607.23929)
- [AI Research Agents Narrow Scientific Exploration](https://arxiv.org/abs/2605.27905)
- [IdeaScientist: Orchestrating Agents for Grounded Scientific Ideation](https://arxiv.org/abs/2610.04074)
- [SwarmResearch: Orchestrating Coding Agents for Open-Ended Discovery](https://arxiv.org/abs/2607.02807)
- [ScienceFlow: A long-horizon agent for ML research, scientific discovery and beyond](https://arxiv.org/abs/2608.14354)
- [What Do Evolutionary Coding Agents Evolve?](https://arxiv.org/abs/2605.20086)
- [ARAC: Benchmarking Auto-Research's Alignment and Completeness on End-to-End Researchs](https://arxiv.org/abs/2608.12788)
- [Autonomous Research Agents: A Survey of AI Scientists and the Verification Gap](https://arxiv.org/abs/2608.05179)
- [The Winner's Curse in LLM Self-Improvement Loops: Selection Noise, Lock-in, and Acceptance Rules](https://arxiv.org/abs/2610.09239)
- [RealisticTritonBench: A Benchmark for Triton-Kernel Generation in Real-World AI Frameworks](https://arxiv.org/abs/2608.12004)
- [KREX: Concurrent Kernel Benchmarking on Shared GPUs via Region-Granular Exclusivity](https://arxiv.org/abs/2609.30057)
- [BAITBENCH: Measuring Agent Reward Hacking with Optional Shortcuts Planted in ML Tasks](https://arxiv.org/abs/2608.30724)
- [Beyond Execution: Auditing Experimental Fidelity in LLM-Driven Scientific Research](https://arxiv.org/abs/2608.26753)
- [When Does Combining Language Models Help? A Co-Failure Ceiling on Routing, Voting, and Mixture-of-Agents Across 67 Frontier Models](https://arxiv.org/abs/2606.27288)
- [Beyond Consensus: Trace-Level Synthesis in Mixture of Agents](https://arxiv.org/abs/2605.29116)

</details>

### 🔀 Upstream

| Project | Pull request | Status |
|---|---|---|
| stable-diffusion.cpp | [#2202](https://github.com/leejet/stable-diffusion.cpp/pull/2202) LoRA `baked_scale` fix | ![merged](https://img.shields.io/badge/merged-8250df?style=flat-square) |
| PrismML llama.cpp | [#368](https://github.com/PrismML-Eng/llama.cpp/pull/368) Pascal PQ2_0 mat-vec, +17% | ![merged](https://img.shields.io/badge/merged-8250df?style=flat-square) |
| vLLM | [#58863](https://github.com/vllm-project/vllm/pull/58863) exact GDN replay commit, adopted in the PR | ![adopted](https://img.shields.io/badge/adopted-4fd6b9?style=flat-square&labelColor=0a1514) |
| llama.cpp | [#27721](https://github.com/ggml-org/llama.cpp/pull/27721) CUDA graphs on Pascal, up to +75% on MoE | ![open](https://img.shields.io/badge/open-f2c14e?style=flat-square) |

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
