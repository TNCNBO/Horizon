---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 106 items, 18 important content pieces were selected

---

1. [OpenAI debuts Jalapeño inference chip with Broadcom](#item-1) ⭐️ 9.0/10
2. [Anthropic accuses Alibaba of extracting Claude capabilities](#item-2) ⭐️ 8.0/10
3. [Qualcomm will acquire Modular.](#item-3) ⭐️ 8.0/10
4. [Google adds computer use to Gemini 3.5 Flash.](#item-4) ⭐️ 8.0/10
5. [Coinbase Outage Shows AWS Partial Failures Can Cascade](#item-5) ⭐️ 8.0/10
6. [An agent company cuts Claude costs with DeepSeek v4.](#item-6) ⭐️ 8.0/10
7. [PostgreSQL 19 beta adds graph queries.](#item-7) ⭐️ 8.0/10
8. [Swiss court evaluates Heretic for legal LLM refusals.](#item-8) ⭐️ 8.0/10
9. [NVIDIA presents 45°C liquid cooling for data centers.](#item-9) ⭐️ 7.0/10
10. [Robotics commercialization faces a reality check.](#item-10) ⭐️ 7.0/10
11. [Gefen claims lower-memory AdamW training.](#item-11) ⭐️ 7.0/10
12. [OpenMontage brings agentic AI to video production](#item-12) ⭐️ 7.0/10
13. [Apple's Swift Container Tool for Mac](#item-13) ⭐️ 7.0/10
14. [MDN compatibility data becomes a SQLite database.](#item-14) ⭐️ 6.0/10
15. [LLM-polished applications can make candidates seem anonymous.](#item-15) ⭐️ 6.0/10
16. [Jitian Xingzhou raises Series B for optical payloads.](#item-16) ⭐️ 6.0/10
17. [Light Source Capital outlines AI-era early investing.](#item-17) ⭐️ 6.0/10
18. [Hyper3D raises funding and launches Rodin Gen-2.5](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI debuts Jalapeño inference chip with Broadcom](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI unveiled Jalapeño, its first custom AI chip for LLM inference, developed with Broadcom and described as part of a multi-generation computing platform. Reports say the design-to-tape-out sprint took nine months, with manufacturing reportedly handled by TSMC. The move signals that OpenAI is trying to control more of its AI infrastructure stack as inference demand grows across ChatGPT, Codex, and API workloads. If successful, custom silicon could reduce cost per inference, improve efficiency, and increase competitive pressure on Nvidia GPUs and other hyperscaler accelerators such as Google TPUs and AWS Inferentia. Jalapeño is aimed specifically at LLM inference rather than general AI training, so its value depends on how well OpenAI can match the hardware to its deployed model workloads. The announcement also claims OpenAI models accelerated parts of the design and optimization process, but public details are limited, making it hard to assess how substantive that contribution was.

hackernews · Hacker News 热门 · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: AI inference is the stage where a trained model is used to generate outputs for users, such as answering prompts or producing code. Inference chips are specialized processors, often ASICs, optimized for the matrix and tensor operations common in neural networks. Large AI service providers increasingly pursue custom silicon because high-volume, predictable workloads can justify chips tuned for performance, power efficiency, and cost. Broadcom is a major partner in the custom AI ASIC market, while Google, AWS, and others have already built their own accelerator families.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/semiconductors/custom-ai-asics-examined-from-broadcom-to-mtia">The custom AI ASIC state of play (May 2026) — Broadcom deals ...</a></li>
<li><a href="https://aws.amazon.com/ai/machine-learning/inferentia/">AI Chip - Amazon Inferentia - AWS</a></li>

</ul>
</details>

**Discussion**: Commenters are broadly treating the announcement as a major strategic move, but several are skeptical of vague claims that OpenAI’s models accelerated chip design. Discussion also focused on whether TSMC is the manufacturer, how this compares with Google’s TPU lead, and more speculative ideas such as baking model weights directly into silicon for extreme inference throughput.

**Tags**: `#AI hardware`, `#custom silicon`, `#OpenAI`, `#inference`, `#semiconductors`

---

<a id="item-2"></a>
## [Anthropic accuses Alibaba of extracting Claude capabilities](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

Anthropic alleged that Alibaba illicitly extracted capabilities from its Claude AI models, according to a Reuters report dated June 24, 2026. The claim centers on suspected use of Claude outputs or access channels to transfer model behavior into Alibaba-related AI systems. The allegation highlights a growing industry concern: frontier AI providers can expose valuable model behavior through APIs even when model weights are not released. It could influence AI intellectual-property disputes, API monitoring, export-control enforcement, and competition between U.S. and Chinese AI labs. Model distillation can be legitimate when a developer fine-tunes a smaller model using outputs from a larger model, but it can violate terms of service or access restrictions if done without authorization. The public details provided here do not prove Alibaba’s conduct; they describe Anthropic’s allegation and the broader risk of model-extraction behavior.

hackernews · Hacker News 热门 · Jun 24, 19:48 · [Discussion](https://news.ycombinator.com/item?id=48664814)

**Background**: Knowledge distillation is a machine-learning technique in which knowledge from a larger or more capable “teacher” model is transferred to a smaller or cheaper “student” model. OpenAI describes API-based model distillation as fine-tuning cost-efficient models using outputs from more capable models so they can perform well on specific tasks at lower cost. Model extraction attacks are a related security concern in which an attacker samples a model through inputs and outputs to build a surrogate system that behaves similarly.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/api-model-distillation/">Model Distillation in the API | OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://labrai.github.io/KDD2025_Tutorial/files/KDD25_Tutorial_MEA_LLM_July_30.pdf">Model Extraction Attacks and Defenses for Large Language Models</a></li>

</ul>
</details>

**Discussion**: The discussion is split between technical explanations and ethical objections. Some commenters argue that black-box distillation, RLAIF-style training, gray-market Claude token resale, and leaked reasoning traces could make this kind of extraction practical, while others accuse Anthropic of hypocrisy because major AI labs trained on large amounts of web and copyrighted content. Several comments also note that enforcing access restrictions is difficult when resellers, pooled accounts, fraud, or cross-border availability gaps create indirect access channels.

**Tags**: `#AI`, `#LLM`, `#model-distillation`, `#AI-governance`, `#China-tech`

---

<a id="item-3"></a>
## [Qualcomm will acquire Modular.](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

Qualcomm announced that it will acquire Modular, the company behind the Mojo programming language and the MAX AI platform. The move was reported on June 24, 2026, and positions Modular’s compiler, runtime, and inference technology inside Qualcomm’s AI software strategy. The acquisition could strengthen Qualcomm’s ability to offer a fuller AI stack, especially for inference on ARM-based and other non-NVIDIA systems. It also matters because developers and enterprises are actively looking for credible alternatives to NVIDIA’s CUDA-centered ecosystem. Modular’s MAX is positioned as a high-performance, hardware-agnostic inference framework, while Mojo is designed for AI-oriented systems programming with compiled and statically typed features. A key caveat is that the provided materials do not specify how Qualcomm ownership will affect Mojo, MAX licensing, or support for non-Qualcomm hardware.

hackernews · Hacker News 热门 · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: CUDA is NVIDIA’s dominant software platform for programming accelerated computing workloads, and its mature tooling has helped reinforce NVIDIA’s position in AI. Modular has been building MAX as an inference framework intended to optimize and deploy AI workloads across different hardware types. Mojo is Modular’s programming language for AI-oriented performance work, aiming to combine Python-like usability with systems-level performance characteristics.

<details><summary>References</summary>
<ul>
<li><a href="https://mojolang.org/">Mojo - Modular</a></li>
<li><a href="https://www.modular.com/max">MAX: A high-performance inference framework for AI</a></li>
<li><a href="https://aimultiple.com/cuda-vs-rocm">GPU Software for AI: CUDA vs. ROCm in 2026</a></li>

</ul>
</details>

**Discussion**: The discussion is mixed: some commenters see the deal as strategically strong for Qualcomm and potentially important for low-cost ARM-based AI inference. Others are disappointed because they fear Mojo and MAX may become less meaningfully cross-platform after acquisition, comparing the risk to other portability efforts that failed to displace CUDA.

**Tags**: `#AI Infrastructure`, `#Compilers`, `#Qualcomm`, `#Mojo`, `#CUDA Alternatives`

---

<a id="item-4"></a>
## [Google adds computer use to Gemini 3.5 Flash.](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 8.0/10

Google introduced computer-use capabilities for Gemini 3.5 Flash, extending the model toward agentic workflows that can interact with software interfaces. The announcement positions Gemini 3.5 Flash as a faster, lower-cost model for multi-step real-world tasks. Computer-use agents aim to let AI operate ordinary software through clicks, typing, navigation, and related actions, rather than relying only on specialized APIs. If reliable, this could broaden automation across everyday tools, but the discussion shows that trust and error handling remain major blockers. Google’s own Gemini 3.5 Flash documentation describes the model as optimized for speed, cost, sub-agent deployment, multi-step workflows, and long-horizon tasks. Community reports highlight practical risks: one user said a coding agent ran `git reset --hard`, while others described failed data extraction, weak instruction following, and missing MCP support in the Gemini app.

hackernews · Hacker News 热门 · Jun 24, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48662999)

**Background**: A computer-use agent is an AI system that can operate a computer or application in ways similar to a human user, such as clicking buttons, entering text, navigating websites, and sometimes invoking command-line tools or APIs. This approach is meant to cover the “long tail” of software tasks where there is no clean, model-friendly API. Gemini 3.5 Flash is part of Google’s Gemini model family and is described by Google as a multimodal reasoning model designed for the agentic era, with a focus on lower latency and lower cost than larger models.

<details><summary>References</summary>
<ul>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3.5 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://deepmind.google/models/model-cards/gemini-3-5-flash/">Gemini 3.5 Flash - Model Card — Google DeepMind</a></li>
<li><a href="https://openai.com/index/computer-using-agent/">Computer-Using Agent | OpenAI</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion was mostly skeptical and experience-driven: commenters shared examples of Gemini failing at PDF-to-code table extraction, making destructive Git choices, and struggling to follow basic development instructions. Several users compared it unfavorably with Claude, Codex, OpenCode, Opus, and GPT models, while the broader concern was that computer-use agents are still too unreliable to trust with important local state or production work.

**Tags**: `#AI agents`, `#Gemini`, `#Google AI`, `#computer use`, `#model release`

---

<a id="item-5"></a>
## [Coinbase Outage Shows AWS Partial Failures Can Cascade](https://www.infoq.cn/article/tNJCNG5TP8JoZcY9A3MZ?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Coinbase's postmortem says a localized AWS failure triggered a trading-service outage that lasted for hours. The incident shows how a partial cloud disruption can escalate into a prolonged production outage. Coinbase is a major crypto trading platform, so any trading interruption directly affects users and market access. More broadly, the outage is a reminder that cloud dependencies can fail in partial, hard-to-predict ways that still have system-wide impact. The key point is that this was described as a localized AWS failure, not necessarily a full cloud outage. For reliability engineering, it highlights the importance of fault isolation, observability, and recovery paths that can handle nondeterministic partial failures.

rss · InfoQ 中文 · Jun 25, 13:35

**Background**: In distributed systems, a partial failure means only some components break while others continue running, which makes incidents harder to detect and debug. A postmortem is a structured review after an incident that reconstructs what happened and identifies corrective actions. The search results note that partial failures are a core distributed-systems problem and that postmortems are meant to turn incidents into follow-up improvements.

<details><summary>References</summary>
<ul>
<li><a href="https://juejin.cn/post/7131225391863169061">【DDIA笔记】第八章、分布式系统的麻烦故障与部分失效 部分失效（partial failure） ：在分布式系统中，系 - 掘金</a></li>
<li><a href="https://cloud.tencent.com.cn/developer/article/2517333">谈谈分布式系统Faults & Partial Failures-腾讯云开发者社区-腾讯云</a></li>

</ul>
</details>

**Tags**: `#事故复盘`, `#云故障`, `#AWS`, `#系统可靠性`, `#交易系统`

---

<a id="item-6"></a>
## [An agent company cuts Claude costs with DeepSeek v4.](https://www.infoq.cn/article/KfCaAKEXqDsmrDCxr4P1?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

InfoQ reports that an AI agent company moved from Claude to DeepSeek v4 and saved millions of dollars per year in model costs. The migration was far harder than expected, with the workload reportedly reaching 100 times the original estimate. The case highlights that LLM cost optimization can produce large savings for production AI-agent businesses, especially those with heavy inference usage. It also shows that switching model providers is not a simple API swap, because behavior, prompts, tool use, evaluation, and reliability assumptions may all change. The most important caveat is that the report provides a cost-saving headline but does not include enough detail here to independently verify the company, baseline usage, pricing terms, or exact migration scope. The “100 times” migration burden is consistent with broader LLM lock-in concerns, where applications become coupled to provider-specific outputs, latency, tool-calling semantics, and prompt behavior.

rss · InfoQ 中文 · Jun 25, 12:43

**Background**: Claude is Anthropic’s family of large language models, while DeepSeek is a Chinese AI model developer whose models are often discussed in the context of lower-cost, high-capability inference. AI-agent systems use LLMs not only for chat responses but also for planning, tool use, structured outputs, memory, and multi-step workflows. Because these systems often depend on subtle model behavior, switching providers can require prompt rewrites, regression tests, evaluation changes, and product-level tuning rather than just changing an endpoint.

<details><summary>References</summary>
<ul>
<li><a href="https://deepseek.ai/deepseek-v4">DeepSeek V 4 (2026) — 1T Params, Benchmarks & Pricing</a></li>
<li><a href="https://tianpan.co/blog/2026-04-12-provider-lock-in-anatomy-seven-coupling-points-switching-llm-providers">Provider Lock-In Anatomy: The Seven Coupling Points That Make...</a></li>

</ul>
</details>

**Tags**: `#LLM migration`, `#DeepSeek`, `#Claude`, `#AI infrastructure`, `#cost optimization`

---

<a id="item-7"></a>
## [PostgreSQL 19 beta adds graph queries.](https://www.infoq.cn/article/HOFzjxIov0SxEpmZccYT?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

PostgreSQL 19 Beta reportedly introduces SQL graph query support and a concurrent table repacking capability. The headline features are SQL/PGQ-style graph querying and a REPACK CONCURRENTLY-like operation for reorganizing tables while reducing disruption. This matters because PostgreSQL users may be able to model and query graph relationships without leaving the relational database. Concurrent table repacking could also make maintenance of large, heavily updated tables less disruptive for production systems. SQL/PGQ is designed to define property graphs over existing relational tables and query them through SQL-integrated graph pattern matching, including the GRAPH_TABLE operator. Because this is described as a beta announcement and the provided article content has little technical detail, exact syntax, performance characteristics, and final release behavior should be treated as subject to change.

rss · InfoQ 中文 · Jun 25, 11:03

**Background**: SQL/PGQ refers to SQL Property Graph Queries, a standard-oriented approach for representing graph structures on top of relational data. Instead of moving data into a separate graph database, users can define property graphs over existing tables and query relationships using graph pattern matching inside SQL. PostgreSQL table bloat occurs when updates and deletes leave dead space behind; repacking rewrites or reorganizes a table to reclaim space. Traditional table rewrites can block normal workloads, so concurrent maintenance features are valuable for databases that need high availability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.enterprisedb.com/blog/representing-graphs-postgresql-sqlpgq">Representing graphs in PostgreSQL with SQL/PGQ | EDB</a></li>
<li><a href="https://postgresqlhtx.com/postgresql-table-bloat-management-vacuum-full-pg_repack-and-the-coming-repack-concurrently/">PostgreSQL Table Bloat Management: VACUUM FULL, pg_repack, and the Coming REPACK CONCURRENTLY - Postgres SQL HTX</a></li>
<li><a href="https://www.postgresql.org/docs/current/sql-reindex.html">PostgreSQL : Documentation: 18: REINDEX</a></li>

</ul>
</details>

**Tags**: `#PostgreSQL`, `#Databases`, `#SQL`, `#Graph Queries`, `#Database Operations`

---

<a id="item-8"></a>
## [Swiss court evaluates Heretic for legal LLM refusals.](https://www.reddit.com/r/LocalLLaMA/comments/1ueeund/the_swiss_federal_supreme_court_is_evaluating/) ⭐️ 8.0/10

A Reddit post highlights that the Swiss Federal Supreme Court is evaluating Heretic for internal legal use, based on the paper “Measuring & Mitigating Over-Alignment for LLMs in Multilingual Criminal Law Courts.” The paper reportedly evaluates Heretic in Section 5.2 and reaches a favorable conclusion about mitigating inappropriate refusals in legitimate criminal-law prompts. This matters because it connects LLM alignment research with a high-stakes judicial setting where excessive safety refusals can block legitimate legal analysis. If validated, it could influence how courts and other regulated institutions balance safety, usefulness, and multilingual reliability in legal AI systems. Heretic is described by its project page as an open-source censorship-removal tool that implements directional ablation with TPE optimization via Optuna. The caveat is that removing or reducing refusal behavior can improve legitimate access but may also weaken safeguards, so deployment in a court context would require strict governance and evaluation.

reddit · r/LocalLLaMA · /u/-p-e-w- · Jun 24, 14:19

**Background**: Over-alignment refers to cases where a language model refuses or over-safeguards prompts that are actually legitimate, such as legal discussion of criminal conduct for professional analysis. Abliteration is a technique discussed in the LLM community for removing a model’s built-in refusal mechanism without full retraining. Heretic builds on this idea as an automated tool for censorship or refusal-behavior removal across supported model architectures.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/mlabonne/abliteration">Uncensor any LLM with abliteration - Hugging Face</a></li>
<li><a href="https://github.com/p-e-w/heretic">GitHub - p-e-w/ heretic : Fully automatic censorship removal for...</a></li>
<li><a href="https://www.heretics.fun/">HERETIC — Censorship Removal for Language Models</a></li>

</ul>
</details>

**Tags**: `#LLM alignment`, `#legal AI`, `#multilingual NLP`, `#research application`, `#LocalLLaMA`

---

<a id="item-9"></a>
## [NVIDIA presents 45°C liquid cooling for data centers.](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA outlined a warm-water liquid-cooling design that can run at 45°C and drive data-center water use close to zero. The company also frames it as a way to improve efficiency and make waste heat easier to reuse. As AI racks become denser, cooling has become a major constraint on power, cost, and sustainability. A design that reduces water demand while keeping high-performance systems cool could matter for operators facing water scarcity or high utility costs. The approach is described as warm-water liquid cooling, with the article emphasizing that favorable climates can help the system reject heat without conventional water-hungry cooling. The main caveat is that real-world savings still depend on facility design and local ambient conditions.

hackernews · Hacker News 热门 · Jun 24, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48660178)

**Background**: Traditional data centers often use air cooling, and some systems consume extra water through evaporation or chillers. Liquid cooling moves heat directly from the hardware to a coolant loop, which can make higher operating temperatures practical and can open the door to reusing waste heat for nearby buildings or district heating.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacenterdynamics.com/en/analysis/hot-water-cold-water/">What’s the right temperature for water in liquid-cooled data centers? - DCD</a></li>
<li><a href="https://www.supermicro.com/en/glossary/direct-to-chip-liquid-cooling">What Is Direct-to-Chip Liquid Cooling? - Supermicro</a></li>
<li><a href="https://www.datacenterknowledge.com/cooling/how-to-reuse-waste-heat-from-data-centers-intelligently">How to Reuse Waste Heat from Data Centers Intelligently</a></li>

</ul>
</details>

**Discussion**: Commenters were intrigued by the district-heating angle, noting that 45°C waste heat could still be useful to a local heating network. Others were skeptical about how novel the idea really is, asking how it differs from earlier liquid-cooled facilities and requesting more detail on climate and efficiency tradeoffs; one commenter also pointed to NASA Ames as an existing warm-water example.

**Tags**: `#data centers`, `#liquid cooling`, `#sustainability`, `#infrastructure`, `#energy efficiency`

---

<a id="item-10"></a>
## [Robotics commercialization faces a reality check.](https://36kr.com/p/3867998907667462?f=rss) ⭐️ 7.0/10

At 36Kr’s WAVES 2026 conference in Guangzhou, a roundtable discussed when embodied AI and robots will move from hype into real commercial scenarios. Participants included founders from Shenpu Intelligence, Lexiang Technology/Qiongming Intelligence, Qingtianzu, and investors from BV Baidu Ventures, Kailian Capital, and Yunshi Capital. The discussion reflects a key tension in China’s hard-tech market: capital is pouring into embodied AI, but shipment volume, large orders, and repeatable profit models remain uncertain. The outcome will affect robotics startups, industrial customers, investors, and the broader AI ecosystem moving from digital software into the physical world. Panelists cited early revenue opportunities in R&D services, maker and enthusiast markets, pet or IP-based products, rentals, data collection outsourcing, robot combat entertainment, and specialized industrial settings such as docks, underwater work, and heavy factories. BV Baidu Ventures’ Cui Kedi argued the sector is still early and underfunded relative to large-model AI, while others noted that some short-term profits may come from supply-demand mismatches rather than mature end-customer demand.

rss · 36氪 · Jun 25, 03:42

**Background**: Embodied AI refers to AI systems that are connected to physical bodies or devices, allowing them to perceive, act, and learn in real-world environments rather than only process digital information. In robotics, this usually means combining perception, planning, control, data collection, and hardware so a machine can perform physical tasks. The sector has become a popular investment theme because advances in large language models, multimodal AI, and autonomous driving have encouraged investors to look for AI applications in the physical world.

<details><summary>References</summary>
<ul>
<li><a href="http://www.broadview.com.cn/article/420497">被众多AI大佬看好的 具 身 智 能 到底 是 什 么 ？ 它凭 什 么 成为下一个AI...</a></li>
<li><a href="https://m.pedaily.cn/news/547928">追觅、海尔、安克都下场，「 具 身 智 能 」到底 是 噱头还 是 良方|投资界</a></li>

</ul>
</details>

**Tags**: `#具身智能`, `#机器人`, `#硬科技`, `#创业投资`, `#产业落地`

---

<a id="item-11"></a>
## [Gefen claims lower-memory AdamW training.](https://www.reddit.com/r/LocalLLaMA/comments/1uep96s/gefen_is_a_dropin_replacement_for_the_adamw/) ⭐️ 7.0/10

Gefen was announced as a drop-in replacement for the AdamW optimizer, with an arXiv paper numbered 2606.13894 and a GitHub implementation available. The project claims it can reduce optimizer-related training memory usage by up to 8x while remaining compatible with AdamW-style workflows. Optimizer state can be a major part of GPU memory consumption during deep learning training, especially for large language models. If Gefen’s results are reproducible, it could make fine-tuning or training larger models feasible on smaller or cheaper hardware. The main claim is memory reduction, not necessarily faster training or better final model quality, so benchmarks and convergence behavior will be important to inspect. Because the Reddit post provides only the paper and GitHub links, the claim still needs independent validation from users on real LLM training workloads.

reddit · r/LocalLLaMA · /u/indicava · Jun 24, 20:39

**Background**: AdamW is a widely used adaptive optimizer that applies decoupled weight decay, and it is implemented in common frameworks such as PyTorch and TensorFlow. In training, memory is used not only for model parameters but also for gradients, activations, and optimizer states maintained during update steps. Memory-efficient optimizers are an active area of LLM training research because reducing optimizer state overhead can lower the hardware barrier for large-model experimentation.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.pytorch.org/docs/2.12/generated/torch.optim.AdamW.html">AdamW — PyTorch 2.12 documentation</a></li>
<li><a href="https://huggingface.co/blog/train_memory">Visualize and understand GPU memory in PyTorch</a></li>
<li><a href="https://icml.cc/virtual/2025/51750">ICML Q-Adam-mini: Memory - Efficient 8-bit Quantized Optimizer for ...</a></li>

</ul>
</details>

**Tags**: `#machine-learning`, `#optimization`, `#llm-training`, `#memory-efficiency`, `#deep-learning`

---

<a id="item-12"></a>
## [OpenMontage brings agentic AI to video production](https://github.com/calesthio/OpenMontage) ⭐️ 7.0/10

OpenMontage, a Python-based open-source project by calesthio, gained 54 GitHub stars in the past 24 hours while presenting itself as an agentic video production system. The repo claims to package 12 production pipelines, 52 tools, and more than 500 agent skills for turning an AI coding assistant into a video production workflow. If the system works as described, it could make AI-assisted video production more programmable, reproducible, and accessible to developers who already use coding agents. It also fits a broader shift from single-purpose generative video tools toward agentic systems that orchestrate writing, design, audio, editing, and quality-control tasks. The project is still primarily represented by its GitHub repository and related write-ups, so the practical maturity, output quality, and production reliability are not yet validated by broad user discussion. The reported GitHub activity includes 3 forks gained, 3 pushes, and no listed pull requests in the observed period.

ossinsight · calesthio · Jun 25, 06:05

**Background**: Agentic AI refers to systems where an AI model does more than generate isolated outputs: it can plan steps, call tools, and coordinate a workflow toward a goal. In video production, that can mean decomposing a project into tasks such as scripting, asset preparation, audio work, editing, and review. OpenMontage describes this as an end-to-end production pipeline similar to a structured process followed by a real production team, but automated through an AI agent.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/calesthio/OpenMontage">GitHub - calesthio/OpenMontage: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio. · GitHub</a></li>
<li><a href="https://pyshine.com/OpenMontage-Agentic-Video-Production-System/">OpenMontage - Agentic Video Production System with 12 Pipelines and 500+ Skills | PyShine</a></li>
<li><a href="https://a16z.com/its-time-for-agentic-video-editing/">It's time for agentic video editing | Andreessen Horowitz</a></li>

</ul>
</details>

**Tags**: `#open-source`, `#agentic-ai`, `#video-production`, `#python`, `#automation`

---

<a id="item-13"></a>
## [Apple's Swift Container Tool for Mac](https://github.com/apple/container) ⭐️ 7.0/10

Apple's repository `apple/container` is trending with a new Swift-based tool for creating and running Linux containers on Mac. It uses lightweight virtual machines and is optimized for Apple silicon. This gives Mac developers an Apple-authored path for running Linux container workflows locally, which could simplify development and testing on macOS. Its Apple silicon focus also matters because much of Apple's recent hardware is ARM-based, making performance and compatibility especially relevant. The project is written in Swift and is described as using lightweight virtual machines on a Mac rather than running containers natively on macOS. Search results also note that it builds on macOS Virtualization.framework and can host OCI-compliant containers.

ossinsight · apple · Jun 25, 06:05

**Background**: Linux containers package applications with their dependencies so they can run consistently across environments. On macOS, containers usually need a Linux virtual machine because the host system is not Linux. Apple's new tool fits into that model by making the VM layer lighter and more integrated with Mac hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/apple/container">GitHub - apple/ container : A tool for creating and running Linux ...</a></li>
<li><a href="https://opensource.apple.com/projects/container/">Apple Open Source</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_container">Apple container - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#containers`, `#macos`, `#apple-silicon`, `#swift`, `#developer-tools`

---

<a id="item-14"></a>
## [MDN compatibility data becomes a SQLite database.](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 6.0/10

Simon Willison created simonw/browser-compat-db, a GitHub project that converts MDN’s browser-compat-data repository into a roughly 66MB SQLite database. The database is published from a dedicated GitHub branch so it can be fetched with open CORS headers and explored in Datasette Lite. This makes MDN’s browser support data easier to query, package, and use from browser-based tools without running a server. It is useful for developers building documentation tools, compatibility checkers, or AI-assisted coding workflows that need structured browser support information. The conversion script was generated with Claude Code for web using Opus 4.8 and uses Simon Willison’s sqlite-utils library. Because GitHub release assets do not provide the desired open CORS behavior, a GitHub Actions workflow force-pushes the generated database to an orphan branch named db.

rss · Simon Willison · Jun 24, 23:59

**Background**: MDN browser-compat-data is a machine-readable dataset that records support information for web technologies such as Web APIs, JavaScript features, and CSS properties across browsers and runtimes. MDN also recently introduced an MCP server that exposes MDN search, documentation, and browser compatibility data to MCP-compatible AI tools. SQLite is a lightweight embedded database format, and sqlite-utils is a Python library and command-line tool for creating and manipulating SQLite databases.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mdn/browser-compat-data">mdn/browser-compat-data - GitHub</a></li>
<li><a href="https://developer.mozilla.org/en-US/mcp">MDN MCP server - MDN Web Docs - Mozilla</a></li>
<li><a href="https://sqlite-utils.datasette.io/en/3.15/python-api.html">sqlite _ utils Python library — sqlite - utils 3.15 documentation</a></li>

</ul>
</details>

**Tags**: `#SQLite`, `#browser compatibility`, `#MDN`, `#developer tooling`, `#GitHub`

---

<a id="item-15"></a>
## [LLM-polished applications can make candidates seem anonymous.](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 6.0/10

Simon Willison quoted Tom MacWright’s June 24, 2026 essay “Accidental anonymity,” which argues that LLM-written resumes, portfolio sites, GitHub projects, and commit messages can make job applicants harder to understand as people. MacWright’s core point is that polished generated materials may reveal tool use, but not judgment, personality, taste, or lived experience. The observation highlights a growing tension in AI-assisted hiring: candidates can use LLMs to improve presentation, but overuse may flatten individuality and make evaluation less reliable. This affects applicants, recruiters, and hiring managers who rely on portfolios and written materials as signals of communication skill, authenticity, and technical taste. MacWright is not claiming that any use of LLMs in job applications is automatically dishonest; his concern is that fully generated chains of evidence can become generic and impersonal. The issue is especially relevant when portfolio sites and GitHub histories appear to be manufactured primarily as hiring artifacts rather than records of real work.

rss · Simon Willison · Jun 24, 18:13

**Background**: Large language models, or LLMs, are AI systems trained on large amounts of text to generate and analyze natural language. They are commonly used to draft resumes, cover letters, project descriptions, and other professional writing. In software hiring, GitHub projects and commit messages can serve as evidence of how a candidate thinks, builds, and communicates, so generated content can blur the signal that reviewers are trying to assess.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/large-language-models">What are large language models (LLMs)? - IBM</a></li>

</ul>
</details>

**Tags**: `#AI`, `#hiring`, `#careers`, `#LLMs`, `#authenticity`

---

<a id="item-16"></a>
## [Jitian Xingzhou raises Series B for optical payloads.](https://36kr.com/p/3868029247034371?f=rss) ⭐️ 6.0/10

Suzhou-based space-grade optical payload maker Jitian Xingzhou has completed a Series B financing round worth several hundred million yuan, according to 36Kr. The company said the funds will support next-generation ultra-high-resolution optical payloads, star sensor R&D, and expansion of intelligent manufacturing lines. The deal reflects investor interest shifting toward upstream commercial-space suppliers that can deliver critical satellite components at scale. If Jitian Xingzhou can sustain mass delivery of optical payloads and star sensors, it could benefit from low-Earth-orbit constellation deployment and demand for domestic alternatives in satellite manufacturing. The company says it has delivered 55 optical payloads, with 30 launched into orbit and a reported 100% in-orbit success rate. Its highlighted technologies include off-track single-pass curved imaging and computationally reconstructed high-geometry, high-spectral imaging, while a new off-track 0.5-meter high-resolution optical camera is expected to enter batch delivery.

rss · 36氪 · Jun 25, 03:26

**Background**: An optical payload is the imaging instrument on a remote-sensing satellite, effectively acting as the satellite’s “eyes” for Earth observation. In many remote-sensing satellites, the payload is a high-value subsystem because it determines what resolution, spectral information, and observation modes the satellite can provide. A star sensor is a precision attitude sensor that identifies star patterns to help a spacecraft determine its orientation, which is important for pointing cameras, antennas, or laser links accurately. Low-Earth-orbit constellations increase demand for components that are lighter, cheaper, reliable, and suitable for repeated production.

<details><summary>References</summary>
<ul>
<li><a href="https://news.eeany.cn/eewiki/632121-19.html">news.eeany.cn/eewiki/632121-19.html</a></li>
<li><a href="https://www.researching.cn/ArticlePdf/m00139/2025/42/5/1.pdf">低轨 遥 感 星 座信息系统技术现状与展望</a></li>

</ul>
</details>

**Tags**: `#商业航天`, `#光学载荷`, `#融资`, `#卫星制造`, `#国产替代`

---

<a id="item-17"></a>
## [Light Source Capital outlines AI-era early investing.](https://36kr.com/p/3866562600227847?f=rss) ⭐️ 6.0/10

36Kr published an edited recap of a WAVES 2026 speech by Zheng Xuanle, founder and CEO of Light Source Capital and founding partner of the L2F Light Source Founders Fund. Zheng argued that general intelligence will become less scarce as large-model companies dominate supply, and he presented L2F as an early-stage fund focused on AI and future technology industries. The speech reflects how Chinese venture investors are adapting their strategy as AI moves from model breakthroughs into industrial deployment, hard technology, and domain-specific applications. It also signals a shift in early-stage investing toward companies that can combine AI capabilities with real-world production factors and industry workflows. Zheng described AI growth through concepts such as a “dual flywheel,” a new Moore’s-law-like acceleration, and four diffusion rules: gradient expansion, industry depth, paradigm transformation, and recursion. The talk included aggressive forecasts, such as global monthly token usage reaching 1.5 quadrillion and AI potentially creating incremental enterprise and capital value on the scale of hundreds of trillions to millions of trillions of dollars, but these are strategic estimates rather than independently verified technical results.

rss · 36氪 · Jun 25, 01:00

**Background**: WAVES is a venture-capital and technology conference organized by 36Kr and An Yong, and the article frames it as an annual signal for China’s startup-investment community. In this context, “early-stage investing” refers to funding young companies before their business models, products, or markets are fully proven. Terms such as “AI For Science,” “physical AI,” and “multimodal” describe AI expanding beyond text into scientific discovery, real-world interaction, and content forms such as video, images, and audio.

**Tags**: `#AI`, `#venture capital`, `#startup investing`, `#future technology`, `#industry analysis`

---

<a id="item-18"></a>
## [Hyper3D raises funding and launches Rodin Gen-2.5](https://36kr.com/p/3865060112438533?f=rss) ⭐️ 6.0/10

Hyper3D, also known as Deemos or 影眸科技, announced a new funding round worth several hundred million RMB led by Cathay Capital and Shanghai State-owned Capital Investment Guidance Fund, with existing investors following on. Alongside the financing, it released Hyper3D Rodin Gen-2.5, a 3D generation model that the company says introduces LLM-like “thinking effort” into AI 3D asset creation. The announcement signals continued investor and commercial interest in AI tools that can generate production-ready 3D assets for games, e-commerce, 3D printing, industrial design, and embodied AI. If the controllability and quality claims hold up in real workflows, tools like Rodin could reduce manual modeling time for professional creators and expand the market for generative 3D software. Hyper3D says Rodin Gen-2.5 offers five adjustable thinking-depth modes ranging from about 4 seconds to 80 seconds, including fast generation of million-face models and an Extreme-High mode aimed at ten-million-face output. The company also claims a native 12K 3D texture model, 3D ControlNet-based shape and dimension control, natural-language local editing, and part segmentation, but the article is largely company-reported and does not include independent benchmarks.

rss · 36氪 · Jun 24, 10:06

**Background**: AI 3D generation refers to systems that create 3D assets from text prompts, images, or other inputs, often targeting formats and workflows used by games, design tools, e-commerce, and 3D printing. Many earlier approaches used a “2D-to-3D” pipeline, generating multiple 2D views first and then reconstructing geometry, which can lose information and make professional editing harder. Hyper3D’s CLAY work describes a more native 3D generation approach using neural fields and transformer-based latent-space generation, with the paper reporting a 1.5-billion-parameter 3D geometry generator trained on a large processed 3D dataset. Rodin Gen-2.5 is positioned as a productized continuation of that native 3D direction, with more emphasis on controllability and selectable generation quality.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2406.13897">[2406.13897] CLAY: A Controllable Large-scale Generative Model for Creating High-quality 3D Assets</a></li>
<li><a href="https://developer.hyper3d.ai/api-specification/rodin-gen2.5">Gen-2.5 Generation | Hyper3D API Documentation</a></li>
<li><a href="https://hyper3d.ai/?lang=zh">Hyper3D Rodin - Best AI 3D Model Generator</a></li>

</ul>
</details>

**Tags**: `#AI`, `#3D Generation`, `#Generative Models`, `#Startup Funding`, `#Computer Graphics`

---