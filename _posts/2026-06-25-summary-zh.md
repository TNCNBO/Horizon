---
layout: default
title: "Horizon Summary: 2026-06-25 (ZH)"
date: 2026-06-25
lang: zh
---

> 从 106 条内容中筛选出 18 条重要资讯。

---

1. [OpenAI 联合 Broadcom 推出 Jalapeño 推理芯片](#item-1) ⭐️ 9.0/10
2. [Anthropic 指控阿里巴巴提取 Claude 能力](#item-2) ⭐️ 8.0/10
3. [Qualcomm 将收购 Modular。](#item-3) ⭐️ 8.0/10
4. [Google 为 Gemini 3.5 Flash 加入计算机使用能力。](#item-4) ⭐️ 8.0/10
5. [Coinbase 事故揭示 AWS 局部故障连锁影响](#item-5) ⭐️ 8.0/10
6. [一家智能体公司用 DeepSeek v4 降低 Claude 成本。](#item-6) ⭐️ 8.0/10
7. [PostgreSQL 19 Beta 增加图查询功能。](#item-7) ⭐️ 8.0/10
8. [瑞士法院正在评估 Heretic 以减少法律 LLM 拒答。](#item-8) ⭐️ 8.0/10
9. [NVIDIA 提出 45°C 数据中心液冷方案。](#item-9) ⭐️ 7.0/10
10. [机器人商业化面临现实检验。](#item-10) ⭐️ 7.0/10
11. [Gefen 声称可降低 AdamW 训练内存。](#item-11) ⭐️ 7.0/10
12. [OpenMontage 将智能体 AI 引入视频制作](#item-12) ⭐️ 7.0/10
13. [Apple 的 Mac 容器工具](#item-13) ⭐️ 7.0/10
14. [MDN 兼容性数据变成了 SQLite 数据库。](#item-14) ⭐️ 6.0/10
15. [LLM 润色的申请材料会让候选人显得匿名。](#item-15) ⭐️ 6.0/10
16. [吉天星舟完成光学载荷 B 轮融资。](#item-16) ⭐️ 6.0/10
17. [光源资本阐述 AI 时代早期投资。](#item-17) ⭐️ 6.0/10
18. [影眸融资并发布 Rodin Gen-2.5](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OpenAI 联合 Broadcom 推出 Jalapeño 推理芯片](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI 发布了 Jalapeño，这是其首款面向 LLM 推理的定制 AI 芯片，由 Broadcom 合作开发，并被描述为多代计算平台的一部分。有报道称，该芯片从设计到流片用了九个月，制造环节据称由 TSMC 承担。 这一举动表明，随着 ChatGPT、Codex 和 API 等推理工作负载增长，OpenAI 正试图掌握更多 AI 基础设施栈。如果成功，定制芯片可能降低单次推理成本、提升效率，并加大对 Nvidia GPU 以及 Google TPU、AWS Inferentia 等超大规模云厂商加速器的竞争压力。 Jalapeño 专门面向 LLM 推理，而不是通用 AI 训练，因此它的价值取决于 OpenAI 能否让硬件很好地匹配其线上模型工作负载。公告还称 OpenAI 模型加速了部分设计和优化流程，但公开细节有限，因此很难判断这一贡献到底有多实质性。

hackernews · Hacker News 热门 · 6月24日 17:47 · [社区讨论](https://news.ycombinator.com/item?id=48663324)

**背景**: AI 推理是指使用已经训练好的模型为用户生成输出，例如回答提示词或生成代码。推理芯片是专用处理器，通常属于 ASIC，针对神经网络中常见的矩阵和张量计算进行优化。大型 AI 服务提供商越来越多地采用定制芯片，因为高规模、相对稳定的工作负载可以支撑为性能、能效和成本专门调优的芯片。Broadcom 是定制 AI ASIC 市场的重要合作方，而 Google、AWS 等公司也已经构建了自己的加速器系列。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip | OpenAI</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/semiconductors/custom-ai-asics-examined-from-broadcom-to-mtia">The custom AI ASIC state of play (May 2026) — Broadcom deals ...</a></li>
<li><a href="https://aws.amazon.com/ai/machine-learning/inferentia/">AI Chip - Amazon Inferentia - AWS</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为这是一次重大战略举措，但也有人质疑“OpenAI 模型加速芯片设计”的说法过于笼统，可能只是营销表述。讨论还集中在 TSMC 是否负责制造、它与 Google TPU 领先优势的比较，以及将模型权重直接固化进芯片以获得极高推理吞吐量等更具设想性的方案。

**标签**: `#AI hardware`, `#custom silicon`, `#OpenAI`, `#inference`, `#semiconductors`

---

<a id="item-2"></a>
## [Anthropic 指控阿里巴巴提取 Claude 能力](https://www.reuters.com/world/china/anthropic-says-alibaba-illicitly-extracted-claude-ai-model-capabilities-2026-06-24/) ⭐️ 8.0/10

据路透社 2026 年 6 月 24 日报道，Anthropic 指控阿里巴巴非法提取其 Claude 人工智能模型的能力。该指控的核心是，阿里巴巴相关人工智能系统可能利用 Claude 的输出或访问渠道来转移模型行为。 这一指控凸显了行业日益关注的问题：即使模型权重没有公开，前沿人工智能提供商仍可能通过接口暴露有价值的模型行为。它可能影响人工智能知识产权争议、接口监控、出口管制执行，以及中美人工智能实验室之间的竞争。 模型蒸馏在开发者使用较大模型的输出微调较小模型时可以是合法用途，但如果未经授权进行，就可能违反服务条款或访问限制。这里提供的公开信息并不能证明阿里巴巴的行为，只说明了 Anthropic 的指控以及模型提取行为带来的更广泛风险。

hackernews · Hacker News 热门 · 6月24日 19:48 · [社区讨论](https://news.ycombinator.com/item?id=48664814)

**背景**: 知识蒸馏是一种机器学习技术，指把较大或能力更强的“教师”模型中的知识转移到较小或成本更低的“学生”模型中。OpenAI 将基于接口的模型蒸馏描述为使用更强模型的输出微调更具成本效率的模型，使其能以更低成本在特定任务上表现良好。模型提取攻击是相关的安全问题，攻击者通过输入和输出反复采样模型，从而构建行为相似的替代系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/api-model-distillation/">Model Distillation in the API | OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Knowledge_distillation">Knowledge distillation - Wikipedia</a></li>
<li><a href="https://labrai.github.io/KDD2025_Tutorial/files/KDD25_Tutorial_MEA_LLM_July_30.pdf">Model Extraction Attacks and Defenses for Large Language Models</a></li>

</ul>
</details>

**社区讨论**: 讨论主要分为技术解释和伦理质疑两类。一些评论者认为，黑盒蒸馏、类似 RLAIF 的训练、灰色市场上的 Claude 令牌转售以及泄露的推理轨迹，都可能让这种提取变得可行；另一些人则指责 Anthropic 虚伪，因为大型人工智能实验室本身也使用了大量网络内容和受版权保护的内容进行训练。还有评论指出，当转售商、共享账户、欺诈行为或跨境可用性差异形成间接访问渠道时，访问限制很难执行。

**标签**: `#AI`, `#LLM`, `#model-distillation`, `#AI-governance`, `#China-tech`

---

<a id="item-3"></a>
## [Qualcomm 将收购 Modular。](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

Qualcomm 宣布将收购 Modular，后者是 Mojo 编程语言和 MAX 人工智能平台背后的公司。该消息于 2026 年 6 月 24 日报道，这一交易将把 Modular 的编译器、运行时和推理技术纳入 Qualcomm 的人工智能软件战略。 这项收购可能增强 Qualcomm 提供更完整人工智能技术栈的能力，尤其是在基于 ARM 和其他非 NVIDIA 系统上进行推理方面。它也很重要，因为开发者和企业正在寻找能够替代以 NVIDIA 的 CUDA 为中心的生态系统的可信方案。 Modular 的 MAX 被定位为高性能、硬件无关的推理框架，而 Mojo 面向人工智能系统编程，具备编译型和静态类型等特性。一个关键的不确定点是，现有材料并未说明 Qualcomm 入主后会如何影响 Mojo、MAX 的许可方式，或对非 Qualcomm 硬件的支持。

hackernews · Hacker News 热门 · 6月24日 13:49 · [社区讨论](https://news.ycombinator.com/item?id=48659798)

**背景**: CUDA 是 NVIDIA 用于加速计算工作负载的主导性软件平台，其成熟的工具链帮助巩固了 NVIDIA 在人工智能领域的地位。Modular 一直在构建 MAX，将其作为一个用于在不同硬件类型上优化和部署人工智能工作负载的推理框架。Mojo 是 Modular 面向人工智能性能工作的编程语言，目标是结合类似 Python 的易用性和系统级性能特征。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mojolang.org/">Mojo - Modular</a></li>
<li><a href="https://www.modular.com/max">MAX: A high-performance inference framework for AI</a></li>
<li><a href="https://aimultiple.com/cuda-vs-rocm">GPU Software for AI: CUDA vs. ROCm in 2026</a></li>

</ul>
</details>

**社区讨论**: 社区讨论呈现出复杂态度：一些评论者认为这笔交易对 Qualcomm 具有很强的战略意义，并可能推动低成本、基于 ARM 的人工智能推理。另一些人则感到失望，因为他们担心 Mojo 和 MAX 在被收购后可能不再真正保持跨平台属性，并把这种风险与其他未能取代 CUDA 的可移植性方案相比较。

**标签**: `#AI Infrastructure`, `#Compilers`, `#Qualcomm`, `#Mojo`, `#CUDA Alternatives`

---

<a id="item-4"></a>
## [Google 为 Gemini 3.5 Flash 加入计算机使用能力。](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-computer-use-gemini-3-5-flash/) ⭐️ 8.0/10

Google 为 Gemini 3.5 Flash 引入了计算机使用能力，使该模型更接近能够与软件界面交互的智能体工作流。该公告将 Gemini 3.5 Flash 定位为面向多步骤现实任务的更快、成本更低的模型。 计算机使用型智能体的目标是让 AI 通过点击、输入、导航等操作使用普通软件，而不只是依赖专门的 API。如果可靠性足够高，它可能扩大日常工具中的自动化范围，但讨论显示，信任与错误处理仍是主要障碍。 Google 的 Gemini 3.5 Flash 文档称该模型针对速度、成本、子智能体部署、多步骤工作流和长程任务进行了优化。社区反馈突出了实际风险：有用户称一个编程智能体执行了 `git reset --hard`，也有人提到数据提取失败、遵循指令能力不足，以及 Gemini 应用缺少 MCP 支持。

hackernews · Hacker News 热门 · 6月24日 17:21 · [社区讨论](https://news.ycombinator.com/item?id=48662999)

**背景**: 计算机使用型智能体是一类可以像人类用户一样操作计算机或应用程序的 AI 系统，例如点击按钮、输入文本、浏览网站，有时还会调用命令行工具或 API。这种方式旨在覆盖大量没有清晰、适合模型调用的 API 的软件任务。Gemini 3.5 Flash 属于 Google 的 Gemini 模型系列，Google 将其描述为面向智能体时代的多模态推理模型，重点是相比更大模型提供更低延迟和更低成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3.5 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://deepmind.google/models/model-cards/gemini-3-5-flash/">Gemini 3.5 Flash - Model Card — Google DeepMind</a></li>
<li><a href="https://openai.com/index/computer-using-agent/">Computer-Using Agent | OpenAI</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论总体偏怀疑，并且主要基于实际使用经历：评论者举例说 Gemini 在从 PDF 提取表格并转成代码时失败、做出破坏性的 Git 操作，并且难以遵循基本开发指令。多位用户将其与 Claude、Codex、OpenCode、Opus 和 GPT 模型作了不利比较，核心担忧是计算机使用型智能体目前仍不够可靠，难以托付重要的本地状态或生产工作。

**标签**: `#AI agents`, `#Gemini`, `#Google AI`, `#computer use`, `#model release`

---

<a id="item-5"></a>
## [Coinbase 事故揭示 AWS 局部故障连锁影响](https://www.infoq.cn/article/tNJCNG5TP8JoZcY9A3MZ?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Coinbase 的事后分析报告称，一次 AWS 的局部故障引发了持续数小时的交易服务中断。这个事故表明，看似局部的云端扰动也可能升级为长时间的生产故障。 Coinbase 是一家重要的加密交易平台，因此任何交易中断都会直接影响用户和市场访问。更广泛地说，这次事故提醒人们，云服务依赖可能以局部且难以预测的方式失效，但仍会对整个系统造成影响。 关键点在于，这次事件被描述为 AWS 的局部故障，而不一定是整个云服务全面宕机。对于可靠性工程来说，这说明故障隔离、可观测性，以及能够应对非确定性局部失效的恢复路径都非常重要。

rss · InfoQ 中文 · 6月25日 13:35

**背景**: 在分布式系统中，局部故障是指只有部分组件失效，而其他组件仍在运行，这会让事故更难被发现和排查。事后分析报告是一种结构化复盘，用来还原事故经过并找出改进措施。搜索结果也说明，局部失效是分布式系统中的核心问题，而复盘的目标就是把事故转化为后续改进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://juejin.cn/post/7131225391863169061">【DDIA笔记】第八章、分布式系统的麻烦故障与部分失效 部分失效（partial failure） ：在分布式系统中，系 - 掘金</a></li>
<li><a href="https://cloud.tencent.com.cn/developer/article/2517333">谈谈分布式系统Faults & Partial Failures-腾讯云开发者社区-腾讯云</a></li>

</ul>
</details>

**标签**: `#事故复盘`, `#云故障`, `#AWS`, `#系统可靠性`, `#交易系统`

---

<a id="item-6"></a>
## [一家智能体公司用 DeepSeek v4 降低 Claude 成本。](https://www.infoq.cn/article/KfCaAKEXqDsmrDCxr4P1?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

InfoQ 报道称，一家人工智能智能体公司从 Claude 迁移到 DeepSeek v4 后，每年节省了数百万美元的模型成本。此次迁移远比预期困难，工作量据称达到原先估计的 100 倍。 这个案例表明，对于推理调用量很大的生产级人工智能智能体业务来说，优化大语言模型成本可能带来显著节省。它也说明，更换模型供应商并不是简单替换 API，因为模型行为、提示词、工具调用、评估方式和可靠性假设都可能随之变化。 最重要的限制是，现有信息只给出了成本节省的结论，但没有足够细节来独立核验公司身份、原始用量、价格条款或具体迁移范围。“100 倍”的迁移负担与更广泛的大语言模型锁定问题相吻合，因为应用往往会与特定供应商的输出风格、延迟、工具调用语义和提示词行为深度耦合。

rss · InfoQ 中文 · 6月25日 12:43

**背景**: Claude 是 Anthropic 的大语言模型系列，而 DeepSeek 是中国的人工智能模型开发者，其模型常被放在低成本、高能力推理的语境中讨论。人工智能智能体系统使用大语言模型并不只是生成聊天回复，还会用于规划、工具调用、结构化输出、记忆和多步骤工作流。由于这些系统经常依赖模型行为中的细微差异，更换供应商往往需要重写提示词、进行回归测试、调整评估方式并做产品级调优，而不只是更改一个接口地址。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepseek.ai/deepseek-v4">DeepSeek V 4 (2026) — 1T Params, Benchmarks & Pricing</a></li>
<li><a href="https://tianpan.co/blog/2026-04-12-provider-lock-in-anatomy-seven-coupling-points-switching-llm-providers">Provider Lock-In Anatomy: The Seven Coupling Points That Make...</a></li>

</ul>
</details>

**标签**: `#LLM migration`, `#DeepSeek`, `#Claude`, `#AI infrastructure`, `#cost optimization`

---

<a id="item-7"></a>
## [PostgreSQL 19 Beta 增加图查询功能。](https://www.infoq.cn/article/HOFzjxIov0SxEpmZccYT?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

据报道，PostgreSQL 19 Beta 引入了 SQL 图查询支持和并发数据表重打包能力。此次重点功能包括类似 SQL/PGQ 的图查询，以及用于在减少业务中断的情况下重组数据表的 REPACK CONCURRENTLY 类操作。 这很重要，因为 PostgreSQL 用户可能无需离开关系型数据库，就能建模和查询图关系。并发数据表重打包也可能让大型、高频更新数据表的生产维护变得更少中断。 SQL/PGQ 的设计目标是在现有关系表之上定义属性图，并通过与 SQL 集成的图模式匹配进行查询，其中包括 GRAPH_TABLE 操作符。由于这被描述为 Beta 公告，且提供的文章内容缺少技术细节，具体语法、性能特征和最终发布行为都应视为仍可能变化。

rss · InfoQ 中文 · 6月25日 11:03

**背景**: SQL/PGQ 指的是 SQL 属性图查询，是一种面向标准的方式，用于在关系数据之上表示图结构。用户不必把数据迁移到单独的图数据库，而是可以在现有数据表之上定义属性图，并在 SQL 内通过图模式匹配查询关系。PostgreSQL 的数据表膨胀通常发生在更新和删除留下无效空间之后；重打包会重写或重组数据表以回收空间。传统的数据表重写可能阻塞正常负载，因此并发维护功能对需要高可用性的数据库很有价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.enterprisedb.com/blog/representing-graphs-postgresql-sqlpgq">Representing graphs in PostgreSQL with SQL/PGQ | EDB</a></li>
<li><a href="https://postgresqlhtx.com/postgresql-table-bloat-management-vacuum-full-pg_repack-and-the-coming-repack-concurrently/">PostgreSQL Table Bloat Management: VACUUM FULL, pg_repack, and the Coming REPACK CONCURRENTLY - Postgres SQL HTX</a></li>
<li><a href="https://www.postgresql.org/docs/current/sql-reindex.html">PostgreSQL : Documentation: 18: REINDEX</a></li>

</ul>
</details>

**标签**: `#PostgreSQL`, `#Databases`, `#SQL`, `#Graph Queries`, `#Database Operations`

---

<a id="item-8"></a>
## [瑞士法院正在评估 Heretic 以减少法律 LLM 拒答。](https://www.reddit.com/r/LocalLLaMA/comments/1ueeund/the_swiss_federal_supreme_court_is_evaluating/) ⭐️ 8.0/10

一篇 Reddit 帖子指出，瑞士联邦最高法院正在根据论文《衡量并缓解多语言刑事法院场景中 LLM 的过度对齐》评估 Heretic 用于内部法律用途。据称该论文在第 5.2 节评估了 Heretic，并对其缓解合法刑法提示中的不当拒答给出了较为正面的结论。 这件事重要，因为它把 LLM 对齐研究与司法这种高风险应用场景联系起来，而过度安全拒答可能会阻碍合法的法律分析。如果评估结果得到验证，它可能影响法院和其他受监管机构如何在法律 AI 系统中平衡安全性、实用性和多语言可靠性。 Heretic 的项目页面将其描述为一种开源的审查移除工具，它通过 Optuna 的 TPE 优化实现方向性消融。需要注意的是，减少拒答行为可能提升合法请求的可用性，但也可能削弱安全防护，因此在法院场景部署时需要严格治理和评估。

reddit · r/LocalLLaMA · /u/-p-e-w- · 6月24日 14:19

**背景**: 过度对齐指的是语言模型对实际上合法的提示进行拒答或过度安全处理，例如法律专业人员为了分析而讨论犯罪行为。消融去拒答是 LLM 社区讨论的一类技术，用于在不完整重新训练模型的情况下移除模型内置的拒答机制。Heretic 建立在这一思路之上，是一种面向受支持模型架构的自动化审查或拒答行为移除工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/mlabonne/abliteration">Uncensor any LLM with abliteration - Hugging Face</a></li>
<li><a href="https://github.com/p-e-w/heretic">GitHub - p-e-w/ heretic : Fully automatic censorship removal for...</a></li>
<li><a href="https://www.heretics.fun/">HERETIC — Censorship Removal for Language Models</a></li>

</ul>
</details>

**标签**: `#LLM alignment`, `#legal AI`, `#multilingual NLP`, `#research application`, `#LocalLLaMA`

---

<a id="item-9"></a>
## [NVIDIA 提出 45°C 数据中心液冷方案。](https://blogs.nvidia.com/blog/liquid-cooling-ai-factories/) ⭐️ 7.0/10

NVIDIA 介绍了一种可在 45°C 下运行的温水液冷设计，并声称它能将数据中心用水降到接近零。该方案还被定位为提升效率、并让废热更容易回收利用。 随着 AI 机架密度不断提高，散热已经成为电力、成本和可持续性的重要约束。若一种方案能在保持高性能系统冷却的同时显著减少用水，就会对面临缺水或高公用事业成本的数据中心运营商很有价值。 这一方案被描述为温水液冷，文章强调在适宜气候下，系统可以更容易散热，而不必依赖传统的高耗水冷却方式。主要限制在于，实际节水效果仍取决于机房设计和当地环境条件。

hackernews · Hacker News 热门 · 6月24日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48660178)

**背景**: 传统数据中心通常使用风冷，而一些系统会通过蒸发或冷水机组消耗额外的水。液冷则是把热量直接从硬件带到冷却回路中，这样可以让更高的运行温度变得可行，也为向附近建筑或区域供热回收废热创造条件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.datacenterdynamics.com/en/analysis/hot-water-cold-water/">What’s the right temperature for water in liquid-cooled data centers? - DCD</a></li>
<li><a href="https://www.supermicro.com/en/glossary/direct-to-chip-liquid-cooling">What Is Direct-to-Chip Liquid Cooling? - Supermicro</a></li>
<li><a href="https://www.datacenterknowledge.com/cooling/how-to-reuse-waste-heat-from-data-centers-intelligently">How to Reuse Waste Heat from Data Centers Intelligently</a></li>

</ul>
</details>

**社区讨论**: 评论者对区域供热这个方向很感兴趣，认为 45°C 的废热仍然可能对本地供热网络有价值。也有人质疑这项思路到底有多新，追问它与早期液冷数据中心的区别，并希望看到更多关于气候和效率权衡的细节；还有评论提到了 NASA Ames 作为已有的温水冷却案例。

**标签**: `#data centers`, `#liquid cooling`, `#sustainability`, `#infrastructure`, `#energy efficiency`

---

<a id="item-10"></a>
## [机器人商业化面临现实检验。](https://36kr.com/p/3867998907667462?f=rss) ⭐️ 7.0/10

在广州举行的 36 氪 WAVES 2026 大会上，一场圆桌讨论聚焦具身智能和机器人何时从热潮走向真实商业场景。参与者包括深朴智能、乐享科技与穹明智能、擎天租的创业者，以及来自 BV 百度风投、凯联资本和云时资本的投资人。 这场讨论反映了中国硬科技市场的核心矛盾：资本正在涌入具身智能，但出货量、大订单和可复制盈利模式仍不确定。其走向将影响机器人创业公司、产业客户、投资机构，以及从数字软件走向物理世界的 AI 生态。 与会者提到，早期收入机会包括研发服务、极客和创客市场、宠物或 IP 属性产品、租赁、数据采集外包、机器人格斗娱乐，以及船坞、水下作业和重工厂房等特种工业场景。BV 百度风投的崔轲迪认为，相比大模型 AI，具身智能仍处早期且投入不足；也有嘉宾指出，一些短期利润可能来自供需错配，而不一定代表成熟的终端客户需求。

rss · 36氪 · 6月25日 03:42

**背景**: 具身智能指的是与物理身体或设备相结合的 AI 系统，使其能够在真实环境中感知、行动和学习，而不只是处理数字信息。在机器人领域，这通常意味着把感知、规划、控制、数据采集和硬件结合起来，让机器完成物理任务。这个赛道成为投资热点，是因为大语言模型、多模态 AI 和自动驾驶的发展，让投资人更加关注 AI 在物理世界中的应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://www.broadview.com.cn/article/420497">被众多AI大佬看好的 具 身 智 能 到底 是 什 么 ？ 它凭 什 么 成为下一个AI...</a></li>
<li><a href="https://m.pedaily.cn/news/547928">追觅、海尔、安克都下场，「 具 身 智 能 」到底 是 噱头还 是 良方|投资界</a></li>

</ul>
</details>

**标签**: `#具身智能`, `#机器人`, `#硬科技`, `#创业投资`, `#产业落地`

---

<a id="item-11"></a>
## [Gefen 声称可降低 AdamW 训练内存。](https://www.reddit.com/r/LocalLLaMA/comments/1uep96s/gefen_is_a_dropin_replacement_for_the_adamw/) ⭐️ 7.0/10

Gefen 被发布为 AdamW 优化器的直接替代方案，并提供了编号为 2606.13894 的 arXiv 论文和 GitHub 实现。该项目声称在保持与 AdamW 式工作流兼容的同时，最多可将优化器相关的训练内存使用量降低 8 倍。 优化器状态可能占据深度学习训练中 GPU 内存的重要部分，尤其是在大型语言模型训练中。如果 Gefen 的结果能够复现，它可能让在更小或更便宜的硬件上微调或训练更大模型变得可行。 其主要主张是降低内存使用，而不一定是提升训练速度或最终模型质量，因此基准测试和收敛表现值得重点检查。由于 Reddit 帖子只提供了论文和 GitHub 链接，这一主张仍需要用户在真实 LLM 训练负载上进行独立验证。

reddit · r/LocalLLaMA · /u/indicava · 6月24日 20:39

**背景**: AdamW 是一种广泛使用的自适应优化器，它采用解耦的权重衰减，并已在 PyTorch 和 TensorFlow 等常见框架中实现。训练时的内存不仅用于模型参数，还用于梯度、激活值以及在更新步骤中维护的优化器状态。降低内存占用的优化器是 LLM 训练研究中的活跃方向，因为减少优化器状态开销可以降低大模型实验的硬件门槛。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.pytorch.org/docs/2.12/generated/torch.optim.AdamW.html">AdamW — PyTorch 2.12 documentation</a></li>
<li><a href="https://huggingface.co/blog/train_memory">Visualize and understand GPU memory in PyTorch</a></li>
<li><a href="https://icml.cc/virtual/2025/51750">ICML Q-Adam-mini: Memory - Efficient 8-bit Quantized Optimizer for ...</a></li>

</ul>
</details>

**标签**: `#machine-learning`, `#optimization`, `#llm-training`, `#memory-efficiency`, `#deep-learning`

---

<a id="item-12"></a>
## [OpenMontage 将智能体 AI 引入视频制作](https://github.com/calesthio/OpenMontage) ⭐️ 7.0/10

calesthio 开源的 Python 项目 OpenMontage 在过去 24 小时内新增了 54 个 GitHub 星标，并将自己定位为一个智能体式视频制作系统。该仓库声称整合了 12 条制作流水线、52 个工具和 500 多项智能体技能，用于把 AI 编程助手转变为视频制作工作流。 如果该系统如描述那样可用，它可能让 AI 辅助视频制作变得更可编程、更可复现，并让已经使用编程智能体的开发者更容易进入视频制作流程。它也符合一个更广泛的趋势：视频 AI 工具正在从单一生成能力转向能够编排写作、视觉设计、音频、剪辑和质量检查任务的智能体系统。 该项目目前主要通过 GitHub 仓库和相关文章展示，因此其实用成熟度、输出质量和生产可靠性还没有通过广泛的用户讨论得到验证。观察期内的 GitHub 活动包括新增 3 个复刻、3 次推送，并且未列出拉取请求。

ossinsight · calesthio · 6月25日 06:05

**背景**: 智能体 AI 指的是一种不只是生成单个结果的系统：它可以规划步骤、调用工具，并围绕目标协调工作流。在视频制作中，这可能意味着把一个项目拆分为脚本编写、素材准备、音频处理、剪辑和审核等任务。OpenMontage 将其描述为一种端到端制作流水线，类似真实制作团队遵循的结构化流程，但由 AI 智能体自动执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/calesthio/OpenMontage">GitHub - calesthio/OpenMontage: World's first open-source, agentic video production system. 12 pipelines, 52 tools, 500+ agent skills. Turn your AI coding assistant into a full video production studio. · GitHub</a></li>
<li><a href="https://pyshine.com/OpenMontage-Agentic-Video-Production-System/">OpenMontage - Agentic Video Production System with 12 Pipelines and 500+ Skills | PyShine</a></li>
<li><a href="https://a16z.com/its-time-for-agentic-video-editing/">It's time for agentic video editing | Andreessen Horowitz</a></li>

</ul>
</details>

**标签**: `#open-source`, `#agentic-ai`, `#video-production`, `#python`, `#automation`

---

<a id="item-13"></a>
## [Apple 的 Mac 容器工具](https://github.com/apple/container) ⭐️ 7.0/10

Apple 的 `apple/container` 仓库正在走红，这是一个用 Swift 编写的新工具，可在 Mac 上创建和运行 Linux 容器。它使用轻量级虚拟机，并针对 Apple silicon 进行了优化。 这为 Mac 开发者提供了一个由 Apple 官方推出的本地 Linux 容器工作流方案，有望简化 macOS 上的开发和测试。它对 Apple silicon 的优化也很重要，因为 Apple 近年的硬件大多基于 ARM，这让性能和兼容性格外关键。 该项目用 Swift 编写，描述为在 Mac 上通过轻量级虚拟机运行容器，而不是在 macOS 上原生运行容器。搜索结果还提到它基于 macOS 的 Virtualization.framework，并可承载符合 OCI 标准的容器。

ossinsight · apple · 6月25日 06:05

**背景**: Linux 容器会把应用及其依赖一起打包，从而让它们在不同环境中尽量保持一致运行。由于 macOS 本身不是 Linux，容器在 Mac 上通常需要依赖一个 Linux 虚拟机。Apple 的新工具正是在这个模型下工作，目标是让虚拟机层更轻量，并与 Mac 硬件更紧密集成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/apple/container">GitHub - apple/ container : A tool for creating and running Linux ...</a></li>
<li><a href="https://opensource.apple.com/projects/container/">Apple Open Source</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_container">Apple container - Wikipedia</a></li>

</ul>
</details>

**标签**: `#containers`, `#macos`, `#apple-silicon`, `#swift`, `#developer-tools`

---

<a id="item-14"></a>
## [MDN 兼容性数据变成了 SQLite 数据库。](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 6.0/10

Simon Willison 创建了 simonw/browser-compat-db，这是一个把 MDN 的 browser-compat-data 仓库转换为约 66MB SQLite 数据库的 GitHub 项目。该数据库通过专门的 GitHub 分支发布，因此可以用开放的 CORS 头获取，并可在 Datasette Lite 中浏览。 这让 MDN 的浏览器支持数据更容易被查询、打包，并能在无需自建服务器的浏览器端工具中使用。它对构建文档工具、兼容性检查器或需要结构化浏览器支持信息的 AI 辅助编程流程的开发者很有用。 转换脚本由 Claude Code for web 使用 Opus 4.8 生成，并使用 Simon Willison 的 sqlite-utils 库。由于 GitHub 发布资产不提供所需的开放 CORS 行为，一个 GitHub Actions 工作流会把生成的数据库强制推送到名为 db 的孤立分支。

rss · Simon Willison · 6月24日 23:59

**背景**: MDN browser-compat-data 是一个机器可读的数据集，记录了 Web API、JavaScript 特性、CSS 属性等 Web 技术在不同浏览器和运行时中的支持情况。MDN 最近还推出了一个 MCP 服务器，用于向兼容 MCP 的 AI 工具提供 MDN 搜索、文档和浏览器兼容性数据。SQLite 是一种轻量级嵌入式数据库格式，而 sqlite-utils 是用于创建和操作 SQLite 数据库的 Python 库和命令行工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/mdn/browser-compat-data">mdn/browser-compat-data - GitHub</a></li>
<li><a href="https://developer.mozilla.org/en-US/mcp">MDN MCP server - MDN Web Docs - Mozilla</a></li>
<li><a href="https://sqlite-utils.datasette.io/en/3.15/python-api.html">sqlite _ utils Python library — sqlite - utils 3.15 documentation</a></li>

</ul>
</details>

**标签**: `#SQLite`, `#browser compatibility`, `#MDN`, `#developer tooling`, `#GitHub`

---

<a id="item-15"></a>
## [LLM 润色的申请材料会让候选人显得匿名。](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 6.0/10

Simon Willison 引用了 Tom MacWright 于 2026 年 6 月 24 日发表的文章《Accidental anonymity》，文中认为由 LLM 撰写的简历、作品集网站、GitHub 项目和提交信息会让招聘方更难了解申请者本人。MacWright 的核心观点是，精致的生成式材料也许能显示候选人会使用某些工具，却无法呈现其判断力、个性、品味或真实经历。 这一观察凸显了 AI 辅助求职中的一个日益明显的矛盾：候选人可以用 LLM 改善表达，但过度使用可能会抹平个人特征，使评估更不可靠。这会影响申请者、招聘人员和用人经理，因为他们常把作品集和文字材料当作沟通能力、真实性和技术品味的信号。 MacWright 并不是说在求职材料中使用 LLM 就一定是不诚实的；他的担忧是，完全由生成式内容串起来的证明材料会变得千篇一律且缺乏个人气息。当作品集网站和 GitHub 历史看起来主要是为了求职而制造，而不是实际工作的记录时，这个问题尤其突出。

rss · Simon Willison · 6月24日 18:13

**背景**: 大型语言模型，即 LLM，是在大量文本上训练、用于生成和分析自然语言的 AI 系统。它们常被用来起草简历、求职信、项目说明和其他职业写作内容。在软件招聘中，GitHub 项目和提交信息可以作为候选人如何思考、构建和沟通的证据，因此生成式内容可能会模糊评审者想要判断的真实信号。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/large-language-models">What are large language models (LLMs)? - IBM</a></li>

</ul>
</details>

**标签**: `#AI`, `#hiring`, `#careers`, `#LLMs`, `#authenticity`

---

<a id="item-16"></a>
## [吉天星舟完成光学载荷 B 轮融资。](https://36kr.com/p/3868029247034371?f=rss) ⭐️ 6.0/10

据 36 氪报道，苏州宇航级光学载荷制造商吉天星舟已完成数亿元 B 轮融资。本轮资金将主要用于新一代超高分辨率光学载荷、星敏感器研发，以及智能制造产线扩建。 这笔融资显示，商业航天投资正在向能够规模化交付关键卫星部件的上游供应商延伸。如果吉天星舟能够持续批量交付光学载荷和星敏感器，它将受益于低轨星座部署和卫星制造国产替代需求。 吉天星舟称，其已累计交付 55 台光学载荷，其中 30 台发射入轨，并实现 100%的在轨成功率。公司重点提到的技术包括非沿轨一次过境曲线成像，以及计算重构高几何高光谱成像；其新一代非沿轨 0.5 米高分辨率光学相机也即将批量交付。

rss · 36氪 · 6月25日 03:26

**背景**: 光学载荷是遥感卫星上的成像设备，相当于卫星用于对地观测的“眼睛”。在许多遥感卫星中，载荷是高价值子系统，因为它决定了卫星能提供怎样的分辨率、光谱信息和观测方式。星敏感器是一类高精度姿态敏感器，可通过识别星空图案帮助航天器确定自身姿态，这对相机、天线或激光链路的精确指向很重要。低轨星座的规模化部署会增加对轻量化、低成本、高可靠、可批量生产部件的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.eeany.cn/eewiki/632121-19.html">news.eeany.cn/eewiki/632121-19.html</a></li>
<li><a href="https://www.researching.cn/ArticlePdf/m00139/2025/42/5/1.pdf">低轨 遥 感 星 座信息系统技术现状与展望</a></li>

</ul>
</details>

**标签**: `#商业航天`, `#光学载荷`, `#融资`, `#卫星制造`, `#国产替代`

---

<a id="item-17"></a>
## [光源资本阐述 AI 时代早期投资。](https://36kr.com/p/3866562600227847?f=rss) ⭐️ 6.0/10

36 氪整理发布了光源资本创始人兼 CEO、L2F 光源创业者基金创始合伙人郑烜乐在 WAVES 2026 上的演讲内容。郑烜乐认为，随着大模型公司主导智能供给，通用智能本身将不再稀缺，并将 L2F 定位为面向 AI 与未来科技产业的早期基金。 这场演讲反映了中国创投机构在 AI 从模型突破走向产业落地、硬科技和垂直应用时如何调整投资策略。它也显示，早期投资正在转向那些能把 AI 能力与现实生产要素、行业工作流结合起来的公司。 郑烜乐用“双飞轮”、类似新摩尔定律的加速机制，以及梯度律、纵深律、范式律、递归律四条扩散规律来描述 AI 增长。他还提出全球每月 Token 使用量已达 1.5 千万亿、AI 未来可能创造数十万亿到数百万亿美元级增量企业和资本价值等判断，但这些属于战略性估算，并非独立验证的技术成果。

rss · 36氪 · 6月25日 01:00

**背景**: WAVES 是由 36 氪和暗涌主办的创投与科技会议，文章将其描述为中国创投圈的年度风向标。在这里，“早期投资”指的是在创业公司的商业模式、产品或市场尚未完全验证时进行投资。“AI For Science”“物理 AI”和“多模态”等概念，分别指 AI 向科学发现、真实世界交互，以及视频、图片、声音等多种内容形态扩展。

**标签**: `#AI`, `#venture capital`, `#startup investing`, `#future technology`, `#industry analysis`

---

<a id="item-18"></a>
## [影眸融资并发布 Rodin Gen-2.5](https://36kr.com/p/3865060112438533?f=rss) ⭐️ 6.0/10

影眸科技宣布完成数亿元人民币新一轮融资，本轮由凯辉基金和上海国投先导领投，老股东继续跟投。公司同时发布 Hyper3D Rodin Gen-2.5，称其把类似大语言模型“先思考再生成”的机制引入 AI 3D 资产生成。 这项发布显示，面向游戏、电商、3D 打印、工业设计和具身智能等场景的 AI 3D 生产工具仍受到资本和商业市场关注。如果其可控性和质量主张能在真实工作流中成立，Rodin 这类工具可能减少专业创作者的手工建模时间，并扩大生成式 3D 软件的市场。 影眸称 Rodin Gen-2.5 提供五档可调“思考深度”，耗时约 4 秒到 80 秒不等，可快速生成百万面模型，并在 Extreme-High 模式下支持千万面级输出。公司还宣称推出原生 12K 3D 贴图模型，并提供基于 3D ControlNet 的形状和尺寸控制、自然语言局部编辑以及分件能力，但原文主要来自公司叙述，并未给出独立基准测试。

rss · 36氪 · 6月24日 10:06

**背景**: AI 3D 生成是指从文本提示、图像或其他输入中生成 3D 资产的系统，常面向游戏、设计工具、电商和 3D 打印等工作流。许多早期方案采用“2D 升维 3D”流程，先生成多个二维视角，再重建几何形状，这可能造成信息丢失，并增加专业编辑难度。影眸的 CLAY 研究描述了一种更原生的 3D 生成路线，使用神经场和基于 Transformer 的潜空间生成方法，论文称其训练了一个 15 亿参数的 3D 几何生成器。Rodin Gen-2.5 被定位为这一原生 3D 路线的产品化延续，并更强调可控性和可选择的生成质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2406.13897">[2406.13897] CLAY: A Controllable Large-scale Generative Model for Creating High-quality 3D Assets</a></li>
<li><a href="https://developer.hyper3d.ai/api-specification/rodin-gen2.5">Gen-2.5 Generation | Hyper3D API Documentation</a></li>
<li><a href="https://hyper3d.ai/?lang=zh">Hyper3D Rodin - Best AI 3D Model Generator</a></li>

</ul>
</details>

**标签**: `#AI`, `#3D Generation`, `#Generative Models`, `#Startup Funding`, `#Computer Graphics`

---