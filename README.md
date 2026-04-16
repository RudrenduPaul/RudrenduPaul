# Rudrendu Paul — Applied AI/ML Leader · Published Author · Open Source Contributor

**Fortune 50 AI/ML · Springer Nature · Elsevier · IEEE · HuggingFace Transformers · Google ADK · MCP**

> Building and scaling world-class AI/ML systems at Fortune 50 companies for 15+ years. Published author with **Springer Nature, Elsevier, and IEEE**. Active open source contributor to the tools the AI industry runs on.

---

## What I Do

I sit at the intersection of **applied machine learning**, **causal inference**, and **marketing measurement science** — building production AI systems that drive measurable business outcomes at scale.

My work has shaped AI and data strategy across **retail media networks, AdTech, MarTech, CPG, and e-commerce** at some of the world's largest companies. I specialize in problems where the math is hard, the stakes are high, and the answer has to work in production.

**Core domains:**
- Marketing Mix Modeling · Multi-Touch Attribution · Incrementality Testing
- Causal Inference · Experimentation at Scale
- Generative AI · LLM Systems · AI Agents
- Retail Media Network (RMN) Measurement · Advertising Monetization
- Applied ML for E-commerce · CPG · AdTech · MarTech

---

## Published Research & Thought Leadership

**Published author with Springer Nature, Elsevier, and IEEE.** 31 publications across peer-reviewed journals, books, and industry platforms. Full list: [orcid.org/0009-0008-0141-4690](https://orcid.org/0009-0008-0141-4690)

**Books**

- 📘 *Applications of Artificial Intelligence in Healthcare* — **Elsevier** *(forthcoming July 2026)*
- 📘 [*AI for Advanced Manufacturing and Industrial Applications*](https://orcid.org/0009-0008-0141-4690) — **Springer Nature**, 2025
- 📘 *AI-Driven Autonomous Systems and Advanced Manufacturing with MLOps* — Chronicle International, 2023

**Selected Articles & Conference Talks**

- 🎤 **IEEE NAPS & WPI Conference** — Peer-reviewed presentations on applied AI and machine learning (2023)
- ✍️ **freeCodeCamp** *(10M+ monthly visitors)* — [*How to Build and Secure a Personal AI Agent*](https://orcid.org/0009-0008-0141-4690) (2026)
- ✍️ **DZone** *(1M+ monthly readers, global developer community)* — GenAI, MLOps, enterprise AI
- ✍️ **Hackernoon** *(4M+ monthly readers)* — AI/ML practitioner deep-dives
- ✍️ **Swiss Cognitive** *(Global AI Intelligence platform)* — Applied AI strategy and enterprise transformation
- ✍️ **Cloud Data Insights** — *A CIO's Checklist for a Low-Risk Migration to an AI-Ready Platform* (2026)
- ✍️ **Nuclear Engineering International · PV Magazine** — AI applications in energy and industrial sectors

---

## Open Source Contributions

Contributing to the infrastructure layer of AI — the frameworks, SDKs, and tooling that every ML engineer depends on.

### ✅ Contributions Merged, Approved, and Acknowledged

**6 PRs merged into production. 3 PRs approved by maintainers. 1 contribution acknowledged and shipped by the maintainer team.** These contributions are now part of the official codebases used by millions of engineers worldwide.

**[huggingface/transformers #45352](https://github.com/huggingface/transformers/pull/45352) — merged April 13, 2026**

Fixed an incorrect return type annotation on `Qwen3MoeSparseMoeBlock.forward` in **HuggingFace Transformers** (158K ⭐), the most widely-used library in AI/ML. Propagated the fix to two generated model files (`qwen3_vl_moe`, `qwen3_omni_moe`). Reviewed and approved by a Transformers core maintainer. Ran `make fix-repo` consistency checks and resolved CI failures before merge.

**[huggingface/transformers #45370](https://github.com/huggingface/transformers/pull/45370) — merged April 13, 2026**

Fixed 5 docstring errors in `Gemma3nTextConfig` across **HuggingFace Transformers** (158K ⭐) — correcting typos, grammar, and formatting issues in Google's Gemma 3n model configuration. Passed the anti-slop check and all CI checks.

**[huggingface/transformers #45351](https://github.com/huggingface/transformers/pull/45351) — approved April 13, 2026**

Fixed a crash in `get_device_capability()` in **HuggingFace Transformers** (158K ⭐) testing utilities when CUDA is installed but no GPU is present. Restructured the CUDA/XPU/NPU fallback logic per maintainer review so that each accelerator check is independent. Approved by two Transformers maintainers.

**[huggingface/trl #5527](https://github.com/huggingface/trl/pull/5527) — merged April 12, 2026**

Contributed a new training template for **DeepSeek-V3** to **HuggingFace TRL** (12K ⭐). This template enables engineers to correctly fine-tune DeepSeek-V3 models using SFT loss masking — ensuring the model learns only from the assistant's responses, not the user's questions. Reviewed and approved by the TRL core maintainer.

**[huggingface/trl #5522](https://github.com/huggingface/trl/pull/5522) — merged April 12, 2026**

Contributed a new training template for **Alibaba's Qwen2.5 language model** to **HuggingFace TRL** (12K ⭐). This change enables engineers to correctly train Qwen2.5 models so the AI learns only from the assistant's responses — a critical capability for building production chatbots and AI assistants. Reviewed and approved by the TRL core maintainer.

**[huggingface/trl #5526](https://github.com/huggingface/trl/pull/5526) — approved April 14, 2026**

Contributed a new training template for **Microsoft's Phi-3 model family** to **HuggingFace TRL** (12K ⭐). Adds `{% generation %}` markers for SFT assistant-only loss masking. Fixed a prefix-preservation issue and added the template to the project README. Approved by the TRL core maintainer.

**[huggingface/trl #5493](https://github.com/huggingface/trl/pull/5493) — merged April 10, 2026**

Contributed the equivalent training template for **Meta's Llama 3 model family** to **HuggingFace TRL** (12K ⭐). Llama 3 is one of the most popular open-source AI models in the world. This template is now part of TRL's official release and is used daily by ML engineers fine-tuning Llama 3 for production applications.

**[huggingface/trl #5494](https://github.com/huggingface/trl/pull/5494) — merged April 10, 2026**

Added a working code example to **HuggingFace TRL**'s documentation showing how to use a key training feature (`completion_only_loss`) that was previously undocumented — helping new users get started faster with a feature the community had been asking about.

**[scikit-learn/scikit-learn #33723](https://github.com/scikit-learn/scikit-learn/pull/33723) — approved April 11, 2026**

Clarified in **scikit-learn** (65K ⭐) documentation that `best_estimator_` in `HalvingGridSearchCV` and `HalvingRandomSearchCV` reflects only the winner of the final halving iteration — a subtle but important distinction for users interpreting search results. Approved by two scikit-learn core maintainers.

**[openai/openai-agents-python #2876](https://github.com/openai/openai-agents-python/pull/2876) — acknowledged April 15, 2026**

Submitted docstrings for the `Computer` and `AsyncComputer` abstract methods in the **OpenAI Agents SDK** (19K ⭐). The maintainer responded *"Thank you so much for sending this"* and resolved the gap via [#2877](https://github.com/openai/openai-agents-python/pull/2877). The contribution identified a documentation need that the core team then prioritized and shipped.

---

### 🔵 Open Pull Requests — Under Review

| PR | Repo | Stars | Description | Status |
|----|------|-------|-------------|--------|
| [#33728](https://github.com/scikit-learn/scikit-learn/pull/33728) | **scikit-learn** | 65K ⭐ | docs: document `StratifiedShuffleSplit` approximation limitation for rare classes | Feedback addressed |
| [#33722](https://github.com/scikit-learn/scikit-learn/pull/33722) | **scikit-learn** | 65K ⭐ | docs: clarify `VotingClassifier.estimators_` are fitted on integer-encoded labels | Awaiting review |
| [#3144](https://github.com/huggingface/peft/pull/3144) | **HuggingFace PEFT** | 17K ⭐ | feat: add type hints to utility functions in `merge_utils.py` and `other.py` | Under review |
| [#5235](https://github.com/google/adk-python/pull/5235) | **Google ADK** | 9K ⭐ | fix: support flat-module agents in `_determine_agent_language`; fixes `adk web` crash | Under review |
| [#5227](https://github.com/google/adk-python/pull/5227) | **Google ADK** | 9K ⭐ | fix: add `--agent_module` flag to `adk deploy agent_engine` for non-`agent.py` entry points | Under review |
| [#2410](https://github.com/modelcontextprotocol/python-sdk/pull/2410) | **MCP Python SDK** | 4K ⭐ | fix: allow integer file descriptors for `errlog` in `stdio_client` | Awaiting review |
| [#2251](https://github.com/567-labs/instructor/pull/2251) | **Instructor** | 10K ⭐ | test: unit tests for `completion:error` hook attempt metadata forwarding | Awaiting review |

**Active tracks:** HuggingFace Transformers · HuggingFace TRL · HuggingFace PEFT · scikit-learn · Google ADK · MCP · Instructor · OpenAI Agents SDK

---

## Stack

`Python` · `PyTorch` · `HuggingFace` · `LLMs / Gen AI` · `MCP` · `vLLM` · `LangChain` · `Causal Inference` · `SQL` · `Spark` · `Claude Code`

---

## Connect

| | |
|--|--|
| 💼 LinkedIn | [linkedin.com/in/rudrendupaul](https://www.linkedin.com/in/rudrendupaul) |
| 📚 Research (ORCID) | [orcid.org/0009-0008-0141-4690](https://orcid.org/0009-0008-0141-4690) |
| ✍️ Blog | [rudrendupaul.medium.com](https://rudrendupaul.medium.com) |
| 🤗 Hugging Face | [huggingface.co/Rudrendu](https://huggingface.co/Rudrendu) |
