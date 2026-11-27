# Awesome-Mathematical-Reasoning-Chain-Of-Thought-AI

# Top Mathematical Reasoning & Chain-of-Thought AI Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Step-by-Step Math Solving, Chain-of-Thought Reasoning & Automated Theorem Proving*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mathematical Reasoning & Chain-of-Thought AI**. These tools solve math problems with visible step-by-step explanations, ranging from photo-based homework helpers to frontier reasoning models and formal theorem provers.

**Examples** include OpenAI o1, Anthropic Claude 3.5 Sonnet, Google DeepMind Gemini Pro, Wolfram Alpha, Mathway, Symbolab, Photomath, QANDA, Socratic, Microsoft Math Solver, and esengine/DeepSeek-Reasonix (the category leaders and notable projects).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting mathematical reasoning models, transparent chain-of-thought pipelines, and open theorem-proving frameworks — ideal for researchers, educators, and developers building auditable, math-focused AI without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[OpenAI o1](https://openai.com/)**  
  Frontier reasoning model trained via reinforcement learning to produce internal chain-of-thought before answering; scored 74.4% on AIME 2024 Pass@1 and 94.8% on MATH [citation:11].

- **[Anthropic Claude 3.5 Sonnet](https://www.anthropic.com/)**  
  General-purpose LLM with strong reasoning capabilities; benchmark scores show 51.7% on MATH Level 5 and 27.6% on Omni-MATH, though reasoning consistency degrades with problem perturbation [citation:7][citation:2].

- **[Google DeepMind Gemini Pro / Deep Think](https://deepmind.google/)**  
  Gemini 3.1 Pro Deep Think achieved gold-medal-equivalent scores on Japanese Mathematical Olympiad and ICPC domestic qualifiers, with perfect scores on both contests [citation:3].

- **[Wolfram Alpha](https://www.wolframalpha.com/)**  
  Computational knowledge engine providing step-by-step solutions for math, science, and engineering problems via curated algorithms and Wolfram Language.

- **[Mathway](https://www.mathway.com/)**  
  AI-powered math solver backed by Chegg, covering 11 subjects with photo input and step-by-step explanations; has solved over 5 billion problems [citation:17].

- **[Symbolab](https://www.symbolab.com/)**  
  Math solver with over 500 specialized calculators, offering step-by-step solutions across algebra, calculus, trigonometry, and differential equations [citation:18][citation:24].

- **[Photomath](https://photomath.com/)**  
  Photo-based math learning app with step-by-step explanations, animated steps, and multiple solution methods; basic step-by-step content is free [citation:19][citation:25].

- **[QANDA](https://www.qanda.ai/)**  
  AI study companion used by 95 million students, offering 5-second photo-based problem solving, AI feedback on handwritten work, and coverage across math and science subjects [citation:26].

- **[Socratic (by Google)](https://socratic.org/)**  
  Homework help app acquired by Google, combining AI with expert-made content for step-by-step explanations across multiple subjects.

- **[Microsoft Math Solver](https://math.microsoft.com/)**  
  Free AI math solver from Microsoft with photo, handwriting, and typed input; provides step-by-step guidance, graphing, and supplementary learning materials [citation:22][citation:28].

- **[esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix)**  
  Reliable coding agent for complex software engineering tasks; despite the "Reasonix" name, it is a Go-based CLI agent framework, not a mathematical reasoning model [citation:10].

## Open-Source GitHub Projects

- **[ZGCM-1](https://github.com/zgcagi/ZGCM-1)**  
  Fully open 7B dense foundation model for math and agentic search; scores 75.0% on AIME 2026, 97.1% on MATH-500, and 70.4% on HMMT 2025, with weights, training code, and data recipes released [citation:4][citation:14].

- **[Ring-flash-2.0](https://huggingface.co/inclusionAI/Ring-flash-2.0)**  
  Efficient MoE reasoning model activating only 6.1B parameters while delivering performance comparable to ~40B dense models; designed for complex reasoning with high-speed inference (200+ tokens/sec on 4× H20 GPUs) [citation:9].

- **[LEAP](https://arxiv.org/html/2606.03303v3)**  
  Agentic framework for formal mathematics that achieves 83.3% on Lean-IMO-Bench Basic and 56.7% on Advanced, outperforming direct formalization baselines including Gemini-3.1-Pro on Putnam 2025 [citation:13].

- **[youtube-dl / yt-dlp (educational reference for CoT parsing)**  
  While primarily media downloaders, their codebases are frequently referenced in open-source projects for parsing structured output and handling multi-step extraction pipelines relevant to chain-of-thought tooling.

- **[OpenMathReasoning (community collections)](https://huggingface.co/datasets)**  
  Community-curated datasets and model fine-tunes on Hugging Face focused on mathematical reasoning, including competition math and step-by-step solution generation.

### Additional Strong Open-Source Options

- **Hugging Face Math Reasoning Models** — Community fine-tunes of Llama, Qwen, and Mistral on MATH, GSM8K, and AIME datasets; search "math reasoning" or "CoT" on the Hub for actively maintained variants.
- **Lean 4 / Mathlib** — Open-source interactive theorem prover and mathematics library, serving as the formal verification backbone for many agentic math systems [citation:13].
- **Coq / Isabelle** — Established open-source proof assistants used in formalized mathematics research and AI-assisted theorem proving.
- **NuminaMath** — Open dataset and tooling for math problem solving with chain-of-thought solutions, widely used for training reasoning models.

**Frameworks for building custom systems**: Combine **ZGCM-1** or **Ring-flash-2.0** as reasoning engines, **Lean 4 / Mathlib** for formal verification, **LEAP**-style agentic frameworks for proof search, and **Hugging Face Transformers** for fine-tuning on domain-specific math datasets. Deploy with **vLLM** or **SGLang** for efficient inference.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mathematical reasoning tools should be used as learning aids; over-reliance on solvers may hinder skill development.
- Benchmark scores cited are from public sources and may not reflect performance on specific problem types or domains.
- Self-hosted open-source models require proper evaluation for accuracy, bias, and safety before deployment in educational or high-stakes contexts.

---

**Made for students, educators, researchers, and developers building transparent, verifiable mathematical AI.**  
Let's make math reasoning and chain-of-thought more open, auditable, and accessible.
