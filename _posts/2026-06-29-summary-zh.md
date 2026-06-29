---
layout: default
title: "Horizon Summary: 2026-06-29 (ZH)"
date: 2026-06-29
lang: zh
---

> 从 64 条内容中筛选出 14 条重要资讯。

---

1. [LineShine 在 ISC’26 登顶 TOP500。](#item-1) ⭐️ 8.0/10
2. [KIDS Act 引发年龄核验担忧。](#item-2) ⭐️ 8.0/10
3. [AWS 发布 Graviton5。](#item-3) ⭐️ 8.0/10
4. [GitLab 19.0 将智能体 AI 引入 DevSecOps。](#item-4) ⭐️ 8.0/10
5. [GLM 5.2 在 Semgrep 网络安全测试中超过 Claude。](#item-5) ⭐️ 7.0/10
6. [LLM 简历评分结果不稳定。](#item-6) ⭐️ 7.0/10
7. [SK 计划到 2035 年建设 15GW AI 数据中心。](#item-7) ⭐️ 7.0/10
8. [苹果推出 Core AI，支持端侧生成式 AI。](#item-8) ⭐️ 7.0/10
9. [AI 推高美国电力并购。](#item-9) ⭐️ 6.0/10
10. [百度开源长文档识别模型 Unlimited OCR](#item-10) ⭐️ 6.0/10
11. [三星计划在光州建设芯片基地。](#item-11) ⭐️ 6.0/10
12. [Firmus 与 DayOne 计划在印尼建设 AI 数据中心园区。](#item-12) ⭐️ 6.0/10
13. [AWS 发布 Blocks，服务 AI 智能体后端。](#item-13) ⭐️ 6.0/10
14. [Bedrock 上的 Fable 5 需共享数据](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LineShine 在 ISC’26 登顶 TOP500。](https://chipsandcheese.com/p/top500-at-isc26-we-have-a-new-number) ⭐️ 8.0/10

Chips and Cheese 分析了 LineShine，这是一台在 ISC’26 前后公布的 2026 年 6 月 TOP500 榜单新冠军。所提供的搜索结果称，该系统在 LINPACK 基准测试中达到 2,198 petaFLOPS。 新的 TOP500 第一名是高性能计算领域的重要里程碑，因为该榜单常被用来观察超级计算能力和国家技术战略的变化。其据称采用 ARM 处理器、芯粒和中国半导体技术，也让这一结果与处理器多样化和国产芯片能力的讨论密切相关。 TOP500 排名基于 HPL，也就是 High Performance LINPACK 基准测试，因此该成绩主要反映密集浮点线性代数性能，而不代表所有真实高性能计算或 AI 工作负载。社区补充的技术背景提到 ARMv9.2 相关设计细节，并推测可能使用 SMIC 的 7 纳米级工艺，但这些工艺判断应被视为分析而非所提供搜索结果中的已确认事实。

hackernews · rbanffy · 6月28日 19:38 · [社区讨论](https://news.ycombinator.com/item?id=48710775)

**背景**: TOP500 项目自 1993 年以来对全球最强的非分布式超级计算机进行排名，并且每年发布两次榜单，其中 6 月榜单通常与 International Supercomputing Conference 同期发布。其主要排名指标是 HPL，即面向分布式内存系统的 LINPACK 基准测试实现。LINPACK 衡量线性代数问题上的浮点性能，便于横向比较，但不能完整反映内存带宽、输入输出、网络互连或 AI 训练效率。Green500 和 HPCG 等相关榜单则用于突出能效和更偏向带宽敏感型的表现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/TOP500_Supercomputer_Sites">TOP500 Supercomputer Sites</a></li>
<li><a href="https://en.wikipedia.org/wiki/LINPACK_benchmarks">LINPACK benchmarks - Wikipedia</a></li>
<li><a href="https://www.wikiwand.com/en/Supercomputer">Supercomputer - Wikiwand</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍怀疑 TOP500 是否仍能反映实际计算能力，认为 HPL 指标过于狭窄，而且许多 AI 公司或超大规模云厂商不会提交成绩，以免暴露基础设施细节。也有人补充了关于 LineShine 架构的链接和技术背景，另有评论指出，中国可能存在未公开的系统，因此公开 TOP500 榜单可能低估了实际能力。

**标签**: `#HPC`, `#supercomputing`, `#TOP500`, `#ARM`, `#semiconductors`

---

<a id="item-2"></a>
## [KIDS Act 引发年龄核验担忧。](https://www.eff.org/deeplinks/2026/06/kids-act-would-require-age-checks-get-online) ⭐️ 8.0/10

电子前哨基金会认为，拟议中的 KIDS Act 实际上会迫使许多在线服务在允许用户访问前核验年龄。其担忧是，一项儿童安全法案可能演变成广泛的互联网身份核验要求。 如果这类强制年龄核验被广泛采用，它可能影响未成年人和成年人在网上的隐私、匿名表达以及访问合法内容的能力。它还会给平台带来合规压力，迫使平台收集敏感数据或依赖第三方核验系统。 EFF 的表述带有倡议性质，但其技术问题很具体：年龄核验可能需要证件、生物特征估算、基于账户的证明或其他系统，这些都会带来数据留存和跟踪风险。一些隐私保护方案，例如零知识证明或年龄证明，可能减少信息披露，但并不能消除关于何时应要求年龄核验的政策争议。

hackernews · bilsbie · 6月28日 11:56 · [社区讨论](https://news.ycombinator.com/item?id=48706560)

**背景**: 在线年龄核验是指在允许用户访问某项服务或内容之前，检查用户是否超过规定的年龄门槛。常见做法可能包括身份证件、支付卡检查、面部年龄估算、第三方凭证或隐私保护型证明。隐私保护型年龄核验试图在不暴露完整身份信息的情况下证明“已满 18 岁”等事实，而零知识证明是实现这一目标的一种候选技术。政策争论不仅在于这些系统能否运行，还在于如果把它们强加给大量网站，是否会抑制表达并使在线身份核验常态化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ageapp.com/blog/how-online-age-verification-works/">Complete Guide of How Online Age Verification Works</a></li>
<li><a href="https://www.newamerica.org/insights/exploring-privacy-preserving-age-verification/">Age Verification to Protect Youth Online: Using Zero Knowledge Proofs</a></li>

</ul>
</details>

**社区讨论**: 讨论整体偏怀疑，数位评论者认为该法案属于西方国家以儿童安全为理由限制互联网的更大趋势。也有人讨论法案的实际适用范围，其中一位评论者认为，如果 Hacker News 这类网站不使用个人信息进行广告、营销或推荐，可能不属于覆盖平台。评论者还提出游说影响、社交媒体与青少年心理健康伤害之间证据是否充分，以及从“不要在网上泄露个人信息”转向“按要求提供个人信息”的隐私倒退等问题。

**标签**: `#internet-regulation`, `#privacy`, `#age-verification`, `#tech-policy`, `#online-safety`

---

<a id="item-3"></a>
## [AWS 发布 Graviton5。](https://www.infoq.cn/article/ONqpdtmlUXgF32G1vqT2?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

AWS 已正式发布 Graviton5，这是面向 Amazon EC2 的新一代基于 Arm 的云处理器，具备 192 个内核，并支持经过形式化验证的虚拟机隔离。AWS 表示，该芯片面向高吞吐 CPU 工作负载，包括实时推理、代码生成和多步骤编排等智能体 AI 场景。 Graviton 是 AWS 上重要的 CPU 平台，因此新一代产品可能影响大量 EC2 用户的云端性能、成本效率和迁移决策。形式化验证同样重要，因为它提高了多租户云隔离的可信度，而这正是公有云基础设施的核心安全要求。 AWS 表示，Graviton5 拥有 192 个内核、缓存容量扩大到 5 倍，并且核间延迟最高降低 33%；Amazon 的发布信息还称其采用 3 纳米工艺，并结合裸晶冷却等系统级优化。形式化验证的隔离能力与 AWS Nitro System 中的 Nitro Isolation Engine 相关，AWS 称其使用 Isabelle/HOL 进行验证，以证明未授权实体无法跨虚拟机读取或修改客户数据。

rss · InfoQ 中文 · 6月29日 11:50

**背景**: AWS Graviton 处理器是 AWS 为 Amazon EC2 实例自研的基于 Arm 的 CPU，通常被定位为在云端工作负载中相比同类 x86 方案提供更好的性价比。Amazon EC2 是 AWS 的虚拟机服务，许多客户会在共享物理基础设施上运行彼此隔离的工作负载。Nitro System 是 AWS 用于 EC2 虚拟化、安全和卸载功能的软硬件平台。形式化验证是指使用数学方法和证明工具检查关键软件组件是否满足指定的安全属性，而不是只依赖测试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aboutamazon.com/news/aws/aws-graviton-5-cpu-amazon-ec2">AWS Graviton5 is now generally available, delivering purpose-built performance for the agentic AI era</a></li>
<li><a href="https://aws.amazon.com/ec2/graviton/">ARM Processor - Performance Processor - AWS EC2 Graviton - AWS</a></li>
<li><a href="https://www.amazon.science/blog/ec2s-formally-verified-isolation-engine-provides-mathematical-assurance-of-virtual-machine-isolation">How formal verification makes AWS Nitro the first... - Amazon Science</a></li>

</ul>
</details>

**标签**: `#AWS`, `#Graviton`, `#cloud-computing`, `#processors`, `#security`

---

<a id="item-4"></a>
## [GitLab 19.0 将智能体 AI 引入 DevSecOps。](https://www.infoq.cn/article/ICdHZotGllYog0ocIrxA?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

据报道，GitLab 19.0 在凭证管理、合并请求和软件供应链安全中引入了智能体 AI 功能。提供的新闻条目链接到 InfoQ 中文站文章，但未包含类似发布说明的详细信息，例如具体能力、可用范围或上线时间。 如果这些功能被广泛落地，GitLab 内置的智能体 AI 可能会自动化部分日常 DevSecOps 工作，例如审查变更、识别高风险凭证，以及帮助团队理解供应链暴露面。由于 GitLab 常被用作集成源码管理、CI/CD、安全扫描和协作的平台，这类功能可能同时影响开发人员和安全团队的工作流。 现有内容只点名了三个目标领域：凭证、合并请求和供应链安全；因此，模型行为、权限边界、可审计性和企业控制能力等关键技术细节尚无法从提供材料中确认。对于安全敏感的自动化而言，主要注意点在于 AI 的操作是否可解释、可审查，并且受到既有访问策略约束。

rss · InfoQ 中文 · 6月28日 09:00

**背景**: DevSecOps 指的是将安全实践融入软件开发与运维生命周期，而不是把安全当作最后的独立环节。智能体 AI 通常指能够规划多步骤任务、决定何时调用工具并在工作流中执行操作的 AI 系统，而不只是回答单次提示。软件供应链安全关注从源代码到构建产物再到部署软件的整个路径；SBOM 和 SLSA 等相关概念用于提升可见性、来源可信度以及防篡改能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.glean.com/perspectives/key-steps-for-implementing-ai-in-devsecops-workflows">Key steps for implementing AI in DevSecOps workflows</a></li>
<li><a href="https://slsa.dev/spec/v1.2/about">SLSA • About SLSA</a></li>
<li><a href="https://docs.sbom.observer/learn/topics/slsa">SLSA - A Comprehensive Approach to Software Supply Chain Security | SBOM Observer</a></li>

</ul>
</details>

**标签**: `#GitLab`, `#DevSecOps`, `#Agentic AI`, `#Supply Chain Security`, `#Software Engineering`

---

<a id="item-5"></a>
## [GLM 5.2 在 Semgrep 网络安全测试中超过 Claude。](https://semgrep.dev/blog/2026/we-have-mythos-at-home-glm-52-beats-claude-in-our-cyber-benchmarks/) ⭐️ 7.0/10

Semgrep 报告称，来自 Z.ai 的开放权重模型 GLM 5.2 在其内部网络安全基准测试中超过了运行 Opus 4.6 的 Claude Code。相关摘要称，在这项特定的漏洞发现评估中，GLM 5.2 的 F1 得分为 39%，Claude 为 37%。 这一结果表明，较新的开放权重模型可能不仅在通用编程基准测试中表现强劲，也能在实际代码安全任务上与领先的闭源大模型竞争。如果得到独立验证，这可能会影响开发者和安全团队在托管闭源工具与可自托管、可控性更强的模型之间的选择。 这一结论只适用于特定基准测试：Semgrep 的测试关注模型能否发现安全漏洞，而且公布的分数差距较小，因此方法、提示词、数据集和随机波动都很重要。GLM 5.2 被描述为具备 100 万词元上下文窗口的大型推理模型，这对长代码库和智能体式软件工程流程很有意义。

hackernews · jms703 · 6月28日 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48709670)

**背景**: Semgrep 是一种静态分析工具，用于搜索代码、发现漏洞，并执行安全编码规则。在这里，网络安全基准测试衡量的是大模型识别代码中安全缺陷的能力，而不只是解决编程题的能力。开放权重模型会在其许可条款下提供模型权重，因而可能吸引重视成本、隐私、定制化或本地控制的团队。F1 是结合精确率和召回率的指标，因此更高的 F1 通常意味着在发现真实问题和减少误报之间取得了更好的平衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aiproductivity.ai/news/glm-52-edges-claude-semgrep-security-benchmark/">GLM 5.2 vs Claude: Semgrep Cyber Benchmark | AI:PRODUCTIVITY</a></li>
<li><a href="https://openrouter.ai/z-ai/glm-5.2">GLM 5 . 2 - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://github.com/semgrep/semgrep">GitHub - semgrep / semgrep : Lightweight static analysis for many...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 评论者总体上感兴趣但保持谨慎：一些用户称赞 GLM 5.2 是很强的日常编程模型，也有人认为 DeepSeek V4 Pro 或其他开放模型在某些漏洞搜索测试中可能仍然更好。讨论还强调了一些限制，包括编程基准测试偏差、在本地运行超大模型的难度，以及结果可能会因领域不同而显著变化，例如 Windows 内核相关工作。

**标签**: `#LLMs`, `#cybersecurity`, `#benchmarks`, `#open-weight-models`, `#code-analysis`

---

<a id="item-6"></a>
## [LLM 简历评分结果不稳定。](https://danunparsed.com/p/hackerrank-open-source-ats) ⭐️ 7.0/10

一篇新的评论文章测试了 HackerRank 开源的 ATS 式简历评分工具，发现同一份简历可能得到明显不同的分数，例如 100 分制下的 90 分、74 分和 88 分。文章认为，这种波动对在招聘流程中使用基于 LLM 的评分提出了严肃质疑。 简历筛选工具可能决定谁能获得面试机会，因此非确定性的评分可能会不公平地淘汰合格候选人。这个问题也反映了更广泛的担忧：AI 招聘工具看起来客观，却可能隐藏不可靠或缺乏审计的决策过程。 讨论中提到，默认模型据称是 Gemma 3 4B，这是一个相对较小的 LLM，而 0.1 这样的低温度参数并不能保证每次输出完全相同。评论者还质疑，如果雇主并未实际使用这个特定的开源系统，那么针对它优化简历是否有意义。

hackernews · sambellll · 6月29日 01:44 · [社区讨论](https://news.ycombinator.com/item?id=48713832)

**背景**: 申请人跟踪系统，也就是 ATS，是许多雇主用来收集、筛选和排序求职申请的招聘软件，通常会依据简历、职位描述、关键词和其他条件进行处理。传统 ATS 工具往往强调格式和关键词匹配，而较新的 AI 驱动系统可能会让 LLM 判断技能、经验或岗位匹配度。LLM 以概率方式生成文本，因此即使使用旨在降低随机性的设置，只要整个推理流程没有被严格控制，输出仍可能发生变化。关于基于 LLM 的简历筛选研究也提出了有效性、是否应当拒绝判断，以及模型决策在不同人口群体之间存在差异等问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/todddong/hackerrank-resume-ats">todddong/hackerrank-resume-ats - GitHub</a></li>
<li><a href="https://www.myperfectresume.com/resume/ats-resume-checker">Free ATS Resume Checker: Scan & Score Your Resume</a></li>
<li><a href="https://arxiv.org/abs/2602.18550">[2602.18550] Measuring Validity in LLM-based Resume Screening</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体上偏怀疑和担忧。一些评论者认为，很多人低估了 LLM 的随机性；另一些人则认为，小型的 4B 模型尤其不适合做可靠的招聘判断。也有人指出，招聘中的实际压力会让不完美的自动化筛选工具变得有吸引力，即使它们会淘汰合格候选人。

**标签**: `#LLMs`, `#hiring`, `#ATS`, `#AI ethics`, `#software engineering`

---

<a id="item-7"></a>
## [SK 计划到 2035 年建设 15GW AI 数据中心。](https://36kr.com/newsflashes/3873873423062278?f=rss) ⭐️ 7.0/10

SK 集团董事长崔泰源 6 月 29 日表示，集团计划到 2035 年在韩国建成 15GW 的 AI 数据中心容量。他称该项目将成为韩国国家级基础设施和 Physical AI 时代的核心底座，预计总投资规模为 1000 万亿韩元。 15GW 目标意味着韩国可能建设规模极大的高耗电 AI 算力基础设施，并影响电力供应、电网规划、土地使用和半导体需求。如果计划落地，它可能强化韩国在全球 AI 基础设施竞争中的地位，同时让 AI 战略与国家能源和产业政策更紧密绑定。 这项宣布目前是高层目标，而不是具体实施方案，快讯未披露选址、建设阶段、电力来源、芯片供应商、客户或融资结构等细节。这里的 GW 主要表示数据中心基础设施的电力或容量规模，并不直接等同于模型性能或 GPU 数量。

rss · 36氪 · 6月29日 06:27

**背景**: AI 数据中心是用于部署大量服务器和加速器的专用计算设施，主要支撑 AI 模型的训练和推理。随着模型规模和使用量增长，头部 AI 企业和基础设施提供方越来越多地用吉瓦级电力容量讨论数据中心规模，因为电力供应已经成为关键约束。Physical AI 通常指把感知、推理和行动连接到现实物理世界的 AI 系统，例如机器人或自主机器，而不只是生成文本或数字内容。SK 集团是韩国大型企业集团，因此这一规模的计划会同时牵涉云基础设施、芯片、能源和国家产业战略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wallstreetcn.com/articles/3774490">紧跟OpenAI！ Anthropic拟签1 吉 瓦 算力租约， 中 期目标剑指10 吉 瓦</a></li>
<li><a href="https://xueqiu.com/7113191878/391960620">物理 AI 全面深度分析（定义 + 五大受益赛道 + 全产业链上市公司 + 上涨逻辑） 一、什么是物理 AI（Physical AI）一句话 ...</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#data centers`, `#SK Group`, `#compute capacity`, `#South Korea`

---

<a id="item-8"></a>
## [苹果推出 Core AI，支持端侧生成式 AI。](https://www.infoq.cn/article/x6KDPdgrdHzY7I38JK9U?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

苹果推出了 Core AI，这是一个面向 Apple 设备运行 AI 模型的新框架，并针对自研芯片进行优化。根据 Apple Developer 资料，该框架提供 Swift API，可在设备端加载和运行模型，不依赖服务器，也不产生令牌调用成本。 这可能会让 iOS、iPadOS 和 macOS 开发者更容易加入本地生成式 AI 功能，同时改善隐私、延迟和成本控制。它也表明苹果正在继续推动端侧 AI 成为其平台生态的核心能力。 搜索结果显示，Core AI 可利用 Apple 芯片的异构计算资源，包括 CPU、GPU 和神经网络引擎，并且更像是对 Core ML 的补充，而不是简单替代。当前公开细节仍然有限，因此实际性能、模型支持范围和开发者采用情况仍有待评估。

rss · InfoQ 中文 · 6月28日 11:06

**背景**: 端侧 AI 指模型直接在用户的手机、平板或电脑上运行，而不是把每次请求都发送到云端服务器。这样可以降低延迟，让更多用户数据留在本地，并避免按请求计费的云端推理成本，但也需要针对内存、功耗和专用加速器进行精细优化。苹果此前已有 Core ML 用于部署机器学习模型，而 Core AI 看起来是面向开发者的新一层能力，重点是通过偏 Swift 的 API 在本地运行 AI 模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.apple.com/core-ai/">Core AI - Apple Developer</a></li>
<li><a href="https://www.apple.com/newsroom/2026/06/apple-aids-app-development-with-new-intelligence-frameworks-and-advanced-tools/">Apple aids app development with new intelligence frameworks and advanced tools - Apple</a></li>
<li><a href="https://www.oschina.net/news/454767">苹果发布 Core AI 框架：整合 CPU、GPU 与神经网络引擎的设备端 AI 推理平台 - OSCHINA - 开源 × AI · 开发者生态社区</a></li>

</ul>
</details>

**标签**: `#Apple`, `#端侧AI`, `#生成式AI`, `#AI框架`, `#芯片优化`

---

<a id="item-9"></a>
## [AI 推高美国电力并购。](https://36kr.com/newsflashes/3873859365328133?f=rss) ⭐️ 6.0/10

报道援引德勤调研数据称，今年前五个月，美国电力及公用事业行业并购交易总额达到创纪录的 2036 亿美元。数据中心相关投资规模达到 1515 亿美元，较去年同期公布的 687 亿美元翻了一倍多。 这些数据表明，由 AI 带动的数据中心用电需求，正在成为重塑美国能源基础设施和企业并购活动的重要力量。公用事业公司、发电企业、电网运营方、数据中心开发商以及大型科技公司，都可能面临更高资本开支和更激烈的可靠电力供应竞争。 今年前五个月公布的 2036 亿美元交易规模，比去年全年 1417 亿美元的总额高出四成以上。报道还称，2025 年全年数据中心投资总额为 3210 亿美元，但未披露交易构成、融资条款或区域电网约束等细节。

rss · 36氪 · 6月29日 06:13

**背景**: AI 数据中心需要大量电力，因为它们运行高密度服务器、加速器、冷却系统和网络设备。电力及公用事业并购，通常指涉及发电企业、电网资产、公用事业公司以及相关基础设施企业的合并和收购。当数据中心需求快速增长时，企业可能通过收购资产或融资来锁定发电能力、输电接入和长期能源供应。

**标签**: `#AI infrastructure`, `#data centers`, `#energy`, `#M&A`, `#utilities`

---

<a id="item-10"></a>
## [百度开源长文档识别模型 Unlimited OCR](https://36kr.com/newsflashes/3873858183255302?f=rss) ⭐️ 6.0/10

百度近日发布并开源了 Unlimited OCR，这是一个面向长文档解析的 3B 参数端到端 OCR 模型。百度称该模型在 OmniDocBench v1.6 上取得 93.92% 的综合成绩，并在发布后登顶 GitHub 日趋势榜、GitHub Python 榜、Hugging Face 全球模型趋势榜和 Hugging Face 多模态模型趋势榜。 如果这些评测结果在独立使用中得到验证，Unlimited OCR 可能会提升大规模 PDF 和文档解析在搜索、归档、企业自动化和 AI 数据流水线中的效率。它的开源发布也让文档理解和多模态模型生态中又增加了一个来自中国大型 AI 实验室的重要模型。 该模型据称总参数规模为 3B，但推理时仅激活约 570M 参数，这表明它可能采用了稀疏化或混合专家式设计。项目页面显示它可通过 Hugging Face transformers 在 NVIDIA GPU 上推理，但其榜单成绩仍应在第三方复现前保持审慎看待。

rss · 36氪 · 6月29日 06:12

**背景**: OCR 指光学字符识别，它用于把图片、扫描件和 PDF 中的文字转换为机器可读文本。端到端 OCR 模型尝试用一个统一模型完成文字识别、版面理解和结构化输出，而不是依赖多个分离的流水线步骤。OmniDocBench 是用于评估文档解析和文档结构理解的基准，覆盖多样化 PDF 页面，以及文本提取、表格识别、公式处理和版面分析等任务。长文档解析的难点在于输出可能很长，而基于解码器的模型通常会因此增加注意力缓存占用并降低推理速度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/baidu/Unlimited-OCR">GitHub - baidu/Unlimited-OCR: Unlimited OCR Works: Welcome the Era of One-shot Long-horizon Parsing. · GitHub</a></li>
<li><a href="https://github.com/opendatalab/OmniDocBench">GitHub - opendatalab/ OmniDocBench : [CVPR 2025]...</a></li>
<li><a href="https://arxiv.org/html/2606.23050v1">Unlimited OCR Works Welcome the Era of One-shot Long-horizon Parsing</a></li>

</ul>
</details>

**标签**: `#OCR`, `#open-source`, `#AI models`, `#document parsing`, `#Baidu`

---

<a id="item-11"></a>
## [三星计划在光州建设芯片基地。](https://36kr.com/newsflashes/3873841411773447?f=rss) ⭐️ 6.0/10

三星集团会长李在镕表示，公司计划将光州打造为芯片生产基地，并计划在忠清建设 HBM 工厂。报道未披露建设时间表、投资金额或产能目标。 HBM 是 AI 加速器和其他高性能计算硬件的关键组件，因此三星新增相关产能可能影响 AI 硬件供应链。这一计划也显示韩国半导体制造生态仍在持续进行区域性投资。 该消息只是引用李在镕的简短表态，未说明该 HBM 工厂将生产当前一代还是未来一代 HBM。消息也未说明光州拟承担的芯片生产角色将如何与三星现有半导体设施配合。

rss · 36氪 · 6月29日 05:55

**背景**: HBM 即高带宽内存，是一种通过 3D 堆叠实现更高带宽的 DRAM。它通常与 TSV 等先进封装技术相关，这类技术用于在垂直堆叠的存储芯片之间建立连接。HBM 之所以重要，是因为现代 AI 芯片需要极高的内存访问速度，才能让加速器持续高效地处理数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/高頻寬記憶體">高带宽内存- 维基百科，自由的百科全书</a></li>
<li><a href="https://www.eet-china.com/mp/a366533.html">什么是HBM？来看看芯耀辉的科普视频-电子工程专辑</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#Samsung`, `#HBM`, `#AI hardware`, `#manufacturing`

---

<a id="item-12"></a>
## [Firmus 与 DayOne 计划在印尼建设 AI 数据中心园区。](https://36kr.com/newsflashes/3873834032239621?f=rss) ⭐️ 6.0/10

英伟达支持的澳大利亚数据中心运营商 Firmus 表示，将与总部位于新加坡的 DayOne 合作，在印尼巴淡岛开发一座专属 Nvidia DSX AI 工厂园区。该项目规划装机容量为 360 兆瓦，并与一项为期八年的英伟达合作相关，Firmus 称前六年协议价值最高可达 300 亿美元。 该计划为东南亚增加了一个大型 AI 基础设施项目，而该地区正越来越多地被定位为靠近新加坡的算力和数据中心枢纽。如果项目按计划建成，该园区可能会扩大区域内云服务、企业和 AI 客户对英伟达 AI 算力的获取能力。 已宣布的选址是巴淡岛，该岛与新加坡隔海相望，常被视为临近新加坡的数据中心布局地点。公告将该园区称为 Nvidia DSX AI 工厂，但未披露 GPU 型号、除八年合作以外的具体部署时间表、电力来源、冷却方案或客户承诺。

rss · 36氪 · 6月29日 05:47

**背景**: 英伟达使用 AI 工厂这一说法，指的是把大规模计算、网络、存储和软件整合成 AI 训练与推理能力的数据中心基础设施。Nvidia DSX 是一个用于在实体部署前后设计、仿真、验证和运营这类 AI 工厂的平台。360 兆瓦的数据中心园区意味着非常大的电力容量规划，因为先进 AI 集群需要大量电力来支持 GPU、网络、冷却和配套基础设施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/data-center/products/dsx/">AI Factory Design, Simulation, and Operations | NVIDIA DSX Platform</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#data centers`, `#Nvidia`, `#Indonesia`, `#cloud computing`

---

<a id="item-13"></a>
## [AWS 发布 Blocks，服务 AI 智能体后端。](https://www.infoq.cn/article/ZdA3CGtWNFGAoalSeiu8?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

AWS 推出了 Blocks，这是一个开源框架，旨在帮助开发者构建面向 AI 智能体的后端服务。现有报道未提供版本号、发布日期、架构图或代码级实现细节。 AI 智能体越来越需要可靠的后端组件来支持编排、状态处理、工具访问和服务集成，因此 AWS 推出的框架可能影响团队落地智能体应用的方式。其开源定位也可能让开发者更容易审查、改造并集成到现有云端或后端工作流中。 主要限制在于，现有信息只说明了该框架的用途，并未描述其 API、支持的运行时、部署模型、许可证条款或与现有 AWS 服务的关系。缺少这些细节时，很难判断 Blocks 是一个重要的新平台层，还是一个较轻量的开发便利框架。

rss · InfoQ 中文 · 6月29日 14:00

**背景**: AI 智能体通常是指一种使用语言模型处理任务、调用工具、连接外部服务并决定下一步操作的软件系统。面向这类智能体的后端开发通常需要处理请求、权限、记忆或状态、工具连接器、可观测性和部署等问题。开源框架可以通过提供可复用的模式和组件，减少团队重复搭建基础后端能力的工作。

**标签**: `#AWS`, `#AI Agents`, `#Open Source`, `#Backend Development`, `#Developer Tools`

---

<a id="item-14"></a>
## [Bedrock 上的 Fable 5 需共享数据](https://www.infoq.cn/article/NodhKVrhWoYF9yGwm12j?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

InfoQ 报道称，在 AWS Bedrock 上调用 Fable 5 模型的用户需要向 Anthropic 共享推理数据。现有内容仅包含标题和链接，因此具体范围、实施时间以及是否可选择退出尚未说明。 这件事重要在于，Bedrock 被定位为企业级生成式 AI 平台，客户通常希望通过它获得集中治理和受控的数据处理方式。若使用某个模型需要向模型提供方共享推理数据，可能会影响隐私审查、合规义务、供应商风险评估以及企业内部 AI 使用政策。 关键未决问题在于“推理数据”具体包含什么，例如提示词、输出内容、元数据、日志或评估信号。由于原文未提供技术细节，读者在将该模型用于敏感工作负载前，应核实 AWS 和 Anthropic 的合同条款、数据保留说明以及区域合规影响。

rss · InfoQ 中文 · 6月28日 14:00

**背景**: Amazon Bedrock 是 AWS 提供的生成式 AI 应用构建服务，开发者可以通过统一 API 访问来自多个提供方的基础模型。AI 推理是指训练完成的模型处理新的输入，例如文本或图像，并生成输出的阶段。在企业场景中，推理数据可能很敏感，因为提示词和回答可能包含客户信息、专有业务数据、源代码或受监管内容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aws.amazon.com/bedrock/">Amazon Bedrock – Build genAI applications and agents at production...</a></li>
<li><a href="https://en.wikipedia.org/wiki/AWS_Bedrock">AWS Bedrock</a></li>
<li><a href="https://cloud.google.com/discover/what-is-ai-inference">What is AI inference? How it works and examples | Google Cloud</a></li>

</ul>
</details>

**标签**: `#AI platforms`, `#AWS Bedrock`, `#Anthropic`, `#data privacy`, `#model inference`

---