### Joseph Crabtree

Founder-engineer in Austin, TX. I founded and run an industrial 3D-printing company: 900+ machines in 40+ countries, 50+ patents. Since 2026 I've been post-training and serving open-weight models on my own hardware, and putting LLM agents in charge of real systems.

**What I work on**

- **Agents that act in the physical world, and how they fail.** A 15-agent Claude Code team runs a small 3D-printing toy business, Texas Toy Lab, under an authority matrix with recall windows and shadow mode. I log every control failure and the guardrail that fixed it.
- **Post-training and serving.** A 4× NVIDIA DGX Spark lab on a 200G fabric: multi-node LoRA with FSDP2, vLLM with speculative decoding, a LiteLLM gateway.
- **Evals and red-teaming.** Golden-set eval gates that block model promotion, and multi-agent LLM reviews of safety-critical machine software.

**Selected work**

- [agent-failure-log](https://github.com/thejoecrabtree/agent-failure-log): real control failures from agents running physical hardware, and the patterns that held up.
- [nemotron-moe-lora-checkpoint-fix](https://github.com/thejoecrabtree/nemotron-moe-lora-checkpoint-fix): a silent MoE checkpoint-loading bug that left every routed expert at random init during fine-tuning; root cause and fix, reported upstream as [NVIDIA-NeMo/Automodel#4357](https://github.com/NVIDIA-NeMo/Automodel/issues/4357).
- [llm-eval-gate](https://github.com/thejoecrabtree/llm-eval-gate): a golden-set eval gate for model promotion, plus lm-eval-harness lessons.

**Elsewhere:** [josephcrabtree.com](https://josephcrabtree.com) · [LinkedIn](https://www.linkedin.com/in/josephcrabtree) · [Google Scholar](https://scholar.google.com/citations?user=fZXokS8AAAAJ) · [X](https://x.com/TheJoeCrabtree)
