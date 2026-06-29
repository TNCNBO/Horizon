---
layout: default
title: "Horizon Summary: 2026-06-29 (EN)"
date: 2026-06-29
lang: en
---

> From 64 items, 14 important content pieces were selected

---

1. [LineShine tops TOP500 at ISC’26.](#item-1) ⭐️ 8.0/10
2. [The KIDS Act raises age-check concerns.](#item-2) ⭐️ 8.0/10
3. [AWS launches Graviton5.](#item-3) ⭐️ 8.0/10
4. [GitLab 19.0 adds agentic AI to DevSecOps.](#item-4) ⭐️ 8.0/10
5. [GLM 5.2 tops Claude in Semgrep cyber tests.](#item-5) ⭐️ 7.0/10
6. [LLM resume scoring shows unstable results.](#item-6) ⭐️ 7.0/10
7. [SK Plans 15GW AI Data Centers by 2035.](#item-7) ⭐️ 7.0/10
8. [Apple introduces Core AI for on-device generative AI.](#item-8) ⭐️ 7.0/10
9. [AI power M&A hits a record.](#item-9) ⭐️ 6.0/10
10. [Baidu open-sources Unlimited OCR for long documents](#item-10) ⭐️ 6.0/10
11. [Samsung plans a Gwangju chip base.](#item-11) ⭐️ 6.0/10
12. [Firmus and DayOne plan an Indonesian AI data center campus.](#item-12) ⭐️ 6.0/10
13. [AWS releases Blocks for AI agent backends.](#item-13) ⭐️ 6.0/10
14. [Bedrock Fable 5 Requires Anthropic Data Sharing](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LineShine tops TOP500 at ISC’26.](https://chipsandcheese.com/p/top500-at-isc26-we-have-a-new-number) ⭐️ 8.0/10

Chips and Cheese analyzes LineShine, the new No. 1 system on the June 2026 TOP500 list announced around ISC’26. The system is reported in the provided search results as reaching 2,198 petaFLOPS on the LINPACK benchmark. A new TOP500 leader is a major HPC milestone because the list is widely used to track shifts in supercomputing capability and national technology strategy. The reported use of ARM CPUs, chiplets, and Chinese semiconductor technology also makes the result relevant to debates about processor diversity and domestic chip capability. TOP500 rankings are based on HPL, the High Performance LINPACK benchmark, so the result primarily reflects dense floating-point linear algebra performance rather than every real-world HPC or AI workload. Community-supplied technical context points to ARMv9.2-related design details and speculation about SMIC 7 nm-class processes, but those process claims should be treated as analysis rather than confirmed facts from the provided search results.

hackernews · rbanffy · Jun 28, 19:38 · [Discussion](https://news.ycombinator.com/item?id=48710775)

**Background**: The TOP500 project has ranked the world’s most powerful non-distributed supercomputers since 1993 and publishes updated lists twice a year, with the June list aligned with the International Supercomputing Conference. Its main ranking metric is HPL, a portable implementation of the LINPACK benchmark for distributed-memory systems. LINPACK measures floating-point performance on linear algebra problems, which is useful for comparability but does not fully capture memory bandwidth, I/O behavior, networking, or AI training efficiency. Related rankings such as Green500 and HPCG exist to highlight energy efficiency and more bandwidth-sensitive behavior.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/TOP500_Supercomputer_Sites">TOP500 Supercomputer Sites</a></li>
<li><a href="https://en.wikipedia.org/wiki/LINPACK_benchmarks">LINPACK benchmarks - Wikipedia</a></li>
<li><a href="https://www.wikiwand.com/en/Supercomputer">Supercomputer - Wikiwand</a></li>

</ul>
</details>

**Discussion**: Commenters were skeptical that TOP500 still reflects practical computing power, arguing that HPL is narrow and that many AI companies or hyperscalers avoid submitting results to avoid revealing infrastructure details. Others added links and technical context about LineShine’s architecture, while one commenter noted that China may have undisclosed systems whose public TOP500 presence understates actual capability.

**Tags**: `#HPC`, `#supercomputing`, `#TOP500`, `#ARM`, `#semiconductors`

---

<a id="item-2"></a>
## [The KIDS Act raises age-check concerns.](https://www.eff.org/deeplinks/2026/06/kids-act-would-require-age-checks-get-online) ⭐️ 8.0/10

The Electronic Frontier Foundation argues that the proposed KIDS Act would effectively force many online services to verify users’ ages before allowing access. The concern is that a child-safety bill could become a broad online identity-check mandate. If adopted broadly, mandatory age checks could affect privacy, anonymous speech, and access to lawful online content for both minors and adults. It also creates compliance pressure for platforms that may need to collect sensitive data or rely on third-party verification systems. The EFF’s framing is advocacy-oriented, but the technical issue is concrete: age verification can require documents, biometric estimation, account-based attestations, or other systems that introduce data-retention and tracking risks. Some privacy-preserving approaches, such as zero-knowledge proofs or age attestations, may reduce disclosure, but they do not eliminate policy concerns about when age checks should be required.

hackernews · bilsbie · Jun 28, 11:56 · [Discussion](https://news.ycombinator.com/item?id=48706560)

**Background**: Online age verification is the process of checking whether a user is above a required age threshold before granting access to a service or content. Common approaches can include identity documents, payment-card checks, facial age estimation, third-party credentials, or privacy-preserving attestations. Privacy-preserving age verification aims to prove a fact such as “over 18” without revealing full identity details, and zero-knowledge proofs are one proposed technique for doing that. The policy debate is not only about whether such systems can work, but also about whether requiring them across broad categories of websites would chill speech or normalize identity checks online.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ageapp.com/blog/how-online-age-verification-works/">Complete Guide of How Online Age Verification Works</a></li>
<li><a href="https://www.newamerica.org/insights/exploring-privacy-preserving-age-verification/">Age Verification to Protect Youth Online: Using Zero Knowledge Proofs</a></li>

</ul>
</details>

**Discussion**: The discussion is skeptical overall, with several commenters viewing the bill as part of a broader Western trend toward restricting the internet under child-safety rationales. Others debate the bill’s actual scope, with one commenter arguing that sites like Hacker News may not be covered if they do not use personal information for advertising, marketing, or recommendations. Commenters also raise lobbying concerns, question the evidence linking social media to youth mental-health harms, and object to the shift from “do not share personal information online” to “provide it on demand.”

**Tags**: `#internet-regulation`, `#privacy`, `#age-verification`, `#tech-policy`, `#online-safety`

---

<a id="item-3"></a>
## [AWS launches Graviton5.](https://www.infoq.cn/article/ONqpdtmlUXgF32G1vqT2?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

AWS has officially released Graviton5, its next-generation Arm-based cloud processor for Amazon EC2, with 192 cores and formally verified virtual-machine isolation. AWS says the chip targets high-throughput CPU workloads, including agentic AI scenarios such as real-time reasoning, code generation, and multi-step orchestration. Graviton is a major CPU platform across AWS, so a new generation can affect cloud performance, cost efficiency, and migration decisions for many EC2 users. The formal verification angle is also significant because it raises the assurance level for multi-tenant cloud isolation, a core security requirement for public-cloud infrastructure. AWS says Graviton5 has 192 cores, a 5x larger cache, and up to 33% lower inter-core latency than the prior generation, and Amazon’s announcement describes it as using 3 nm technology with system-level optimizations such as bare-die cooling. The formally verified isolation work is tied to the AWS Nitro System’s Nitro Isolation Engine, which AWS says was verified with Isabelle/HOL to help prove that unauthorized entities cannot read or modify customer data across virtual machines.

rss · InfoQ 中文 · Jun 29, 11:50

**Background**: AWS Graviton processors are custom Arm-based CPUs designed by AWS for Amazon EC2 instances, often positioned as offering better price performance for cloud workloads than comparable x86 options. Amazon EC2 is AWS’s virtual-machine service, where many customers run separate workloads on shared physical infrastructure. The Nitro System is AWS’s hardware and software platform for EC2 virtualization, security, and offload functions. Formal verification means using mathematical methods and proof tools to check that critical software components satisfy specified security properties, rather than relying only on testing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aboutamazon.com/news/aws/aws-graviton-5-cpu-amazon-ec2">AWS Graviton5 is now generally available, delivering purpose-built performance for the agentic AI era</a></li>
<li><a href="https://aws.amazon.com/ec2/graviton/">ARM Processor - Performance Processor - AWS EC2 Graviton - AWS</a></li>
<li><a href="https://www.amazon.science/blog/ec2s-formally-verified-isolation-engine-provides-mathematical-assurance-of-virtual-machine-isolation">How formal verification makes AWS Nitro the first... - Amazon Science</a></li>

</ul>
</details>

**Tags**: `#AWS`, `#Graviton`, `#cloud-computing`, `#processors`, `#security`

---

<a id="item-4"></a>
## [GitLab 19.0 adds agentic AI to DevSecOps.](https://www.infoq.cn/article/ICdHZotGllYog0ocIrxA?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

GitLab 19.0 reportedly introduces agentic AI features across credential management, merge requests, and software supply-chain security. The provided item links to an InfoQ China article but does not include release-note-level details about exact capabilities, availability, or rollout timing. If implemented broadly, agentic AI inside GitLab could automate parts of everyday DevSecOps work, such as reviewing changes, identifying risky credentials, and helping teams reason about supply-chain exposure. Because GitLab is used as an integrated platform for source control, CI/CD, security scanning, and collaboration, these features could affect both developers and security teams in the same workflow. The available content only names three target areas—credentials, merge requests, and supply-chain security—so important technical details such as model behavior, permission boundaries, auditability, and enterprise controls are not yet clear from the provided material. For security-sensitive automation, the main caveat is whether AI actions are explainable, reviewable, and constrained by existing access policies.

rss · InfoQ 中文 · Jun 28, 09:00

**Background**: DevSecOps refers to integrating security practices into the software development and operations lifecycle rather than treating security as a separate final step. Agentic AI generally describes AI systems that can plan multi-step tasks, decide when to use tools, and take actions within a workflow, rather than only answering a single prompt. Software supply-chain security focuses on protecting the path from source code to built artifacts and deployed software; related concepts such as SBOM and SLSA are used to improve visibility, provenance, and resistance to tampering.

<details><summary>References</summary>
<ul>
<li><a href="https://www.glean.com/perspectives/key-steps-for-implementing-ai-in-devsecops-workflows">Key steps for implementing AI in DevSecOps workflows</a></li>
<li><a href="https://slsa.dev/spec/v1.2/about">SLSA • About SLSA</a></li>
<li><a href="https://docs.sbom.observer/learn/topics/slsa">SLSA - A Comprehensive Approach to Software Supply Chain Security | SBOM Observer</a></li>

</ul>
</details>

**Tags**: `#GitLab`, `#DevSecOps`, `#Agentic AI`, `#Supply Chain Security`, `#Software Engineering`

---

<a id="item-5"></a>
## [GLM 5.2 tops Claude in Semgrep cyber tests.](https://semgrep.dev/blog/2026/we-have-mythos-at-home-glm-52-beats-claude-in-our-cyber-benchmarks/) ⭐️ 7.0/10

Semgrep reported that GLM 5.2, an open-weight model from Z.ai, outperformed Claude Code running Opus 4.6 on its internal cybersecurity benchmark. A cited summary says GLM 5.2 scored 39% F1 versus 37% for Claude in this specific bug-finding evaluation. The result suggests that newer open-weight models may be competitive with leading proprietary LLMs on practical code-security tasks, not just general coding benchmarks. If validated independently, this could affect how developers and security teams choose between hosted proprietary tools and self-hosted or more controllable models. The claim is benchmark-specific: Semgrep’s test focuses on whether models can find security bugs, and the reported scores are close enough that methodology, prompts, datasets, and variance matter. GLM 5.2 is described as a large reasoning model with a 1M-token context window, which is relevant for long codebases and agent-style software engineering workflows.

hackernews · jms703 · Jun 28, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48709670)

**Background**: Semgrep is a static analysis tool used to search code, find bugs, and enforce secure coding rules. In this context, a cybersecurity benchmark measures how well an LLM can identify security-relevant defects in code rather than simply solve programming puzzles. Open-weight models make their weights available for deployment or inspection under their licensing terms, which can appeal to teams that care about cost, privacy, customization, or local control. F1 is a combined precision-and-recall metric, so a higher F1 generally means a better balance between finding real issues and avoiding false positives.

<details><summary>References</summary>
<ul>
<li><a href="https://aiproductivity.ai/news/glm-52-edges-claude-semgrep-security-benchmark/">GLM 5.2 vs Claude: Semgrep Cyber Benchmark | AI:PRODUCTIVITY</a></li>
<li><a href="https://openrouter.ai/z-ai/glm-5.2">GLM 5 . 2 - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://github.com/semgrep/semgrep">GitHub - semgrep / semgrep : Lightweight static analysis for many...</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were broadly interested but cautious: several users praised GLM 5.2 as a strong daily programming model, while others argued that DeepSeek V4 Pro or other open models may still be better on some bug-hunting tests. The discussion also emphasized caveats, including coding-benchmark bias, the difficulty of running very large models locally, and the possibility that results vary sharply by domain such as Windows kernel work.

**Tags**: `#LLMs`, `#cybersecurity`, `#benchmarks`, `#open-weight-models`, `#code-analysis`

---

<a id="item-6"></a>
## [LLM resume scoring shows unstable results.](https://danunparsed.com/p/hackerrank-open-source-ats) ⭐️ 7.0/10

A new critique tested HackerRank’s open-source ATS-style resume scorer and found that the same resume could receive sharply different scores, such as 90, 74, and 88 out of 100. The article argues that this variability raises serious questions about using LLM-based scoring in hiring workflows. Resume screeners can affect who gets interviews, so nondeterministic scoring may unfairly filter out qualified candidates. The issue fits a broader concern that AI hiring tools can look objective while hiding unreliable or poorly audited decision-making. The discussion highlights that the default model is reportedly Gemma 3 4B, a relatively small LLM, and that a low temperature such as 0.1 does not guarantee identical outputs. Commenters also questioned whether optimizing a resume for this specific open-source system is useful if employers are not actually using it.

hackernews · sambellll · Jun 29, 01:44 · [Discussion](https://news.ycombinator.com/item?id=48713832)

**Background**: An applicant tracking system, or ATS, is hiring software used by many employers to collect, filter, and rank applications based on resumes, job descriptions, keywords, and other criteria. Traditional ATS tools often emphasize formatting and keyword matching, while newer AI-powered systems may ask an LLM to judge skills, experience, or fit. LLMs generate text probabilistically, so even with settings intended to reduce randomness, outputs can vary unless the entire inference pipeline is tightly controlled. Research on LLM-based resume screening has also raised concerns about validity, abstention, and demographic differences in model decisions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/todddong/hackerrank-resume-ats">todddong/hackerrank-resume-ats - GitHub</a></li>
<li><a href="https://www.myperfectresume.com/resume/ats-resume-checker">Free ATS Resume Checker: Scan & Score Your Resume</a></li>
<li><a href="https://arxiv.org/abs/2602.18550">[2602.18550] Measuring Validity in LLM-based Resume Screening</a></li>

</ul>
</details>

**Discussion**: The community reaction was mostly skeptical and concerned. Several commenters argued that many people underestimate the stochastic nature of LLMs, while others said a small 4B model is especially unsuitable for reliable hiring judgments. Some also noted the practical hiring pressure that makes imperfect automated filters tempting, even if they reject valid candidates.

**Tags**: `#LLMs`, `#hiring`, `#ATS`, `#AI ethics`, `#software engineering`

---

<a id="item-7"></a>
## [SK Plans 15GW AI Data Centers by 2035.](https://36kr.com/newsflashes/3873873423062278?f=rss) ⭐️ 7.0/10

SK Group Chairman Chey Tae-won said on June 29 that the group plans to build 15GW of AI data center capacity in South Korea by 2035. He described the project as national infrastructure for Korea and a core foundation for the Physical AI era, with total investment projected at 1,000 trillion KRW. A 15GW target would imply an unusually large buildout of power-hungry AI computing infrastructure, affecting electricity supply, grid planning, land use, and semiconductor demand in South Korea. If executed, it could strengthen Korea’s position in the global AI infrastructure race while tying AI strategy more closely to national energy and industrial policy. The announcement is a high-level target rather than an implementation plan, and the newsflash does not specify site locations, construction phases, power sources, chip suppliers, customers, or financing structure. The use of GW here refers to power or capacity scale for data center infrastructure, not a direct measure of model performance or GPU count.

rss · 36氪 · Jun 29, 06:27

**Background**: AI data centers are specialized computing facilities that host large numbers of servers and accelerators used to train and run AI models. As model sizes and usage grow, leading AI companies and infrastructure providers increasingly discuss capacity in gigawatts because power availability has become a central constraint. Physical AI generally refers to AI systems that connect perception, reasoning, and action in the physical world, such as robots or autonomous machines, rather than only producing text or digital outputs. SK Group is a major South Korean conglomerate, so a plan of this scale would sit at the intersection of cloud infrastructure, chips, energy, and national industrial strategy.

<details><summary>References</summary>
<ul>
<li><a href="https://wallstreetcn.com/articles/3774490">紧跟OpenAI！ Anthropic拟签1 吉 瓦 算力租约， 中 期目标剑指10 吉 瓦</a></li>
<li><a href="https://xueqiu.com/7113191878/391960620">物理 AI 全面深度分析（定义 + 五大受益赛道 + 全产业链上市公司 + 上涨逻辑） 一、什么是物理 AI（Physical AI）一句话 ...</a></li>

</ul>
</details>

**Tags**: `#AI infrastructure`, `#data centers`, `#SK Group`, `#compute capacity`, `#South Korea`

---

<a id="item-8"></a>
## [Apple introduces Core AI for on-device generative AI.](https://www.infoq.cn/article/x6KDPdgrdHzY7I38JK9U?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

Apple introduced Core AI, a new framework designed to run AI models on Apple devices and optimized for Apple silicon. According to Apple Developer materials, it provides a Swift API for loading and running models entirely on device without server dependencies or token costs. This could make it easier for iOS, iPadOS, and macOS developers to add local generative AI features while improving privacy, latency, and cost control. It also signals Apple’s continued push to make on-device AI a core part of its platform ecosystem. Search results describe Core AI as a framework that can use Apple silicon’s heterogeneous compute resources, including CPU, GPU, and the Neural Engine, and as complementary to Core ML rather than simply replacing it. Available public details are still limited, so real-world performance, model support, and developer adoption remain to be evaluated.

rss · InfoQ 中文 · Jun 28, 11:06

**Background**: On-device AI means the model runs locally on the user’s phone, tablet, or computer instead of sending every request to a cloud server. This can reduce latency, preserve more user data on the device, and avoid per-request cloud inference costs, but it also requires careful optimization for memory, power, and specialized accelerators. Apple already has Core ML for deploying machine-learning models, while Core AI appears positioned as a newer developer-facing layer for running AI models locally with Swift-oriented APIs.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.apple.com/core-ai/">Core AI - Apple Developer</a></li>
<li><a href="https://www.apple.com/newsroom/2026/06/apple-aids-app-development-with-new-intelligence-frameworks-and-advanced-tools/">Apple aids app development with new intelligence frameworks and advanced tools - Apple</a></li>
<li><a href="https://www.oschina.net/news/454767">苹果发布 Core AI 框架：整合 CPU、GPU 与神经网络引擎的设备端 AI 推理平台 - OSCHINA - 开源 × AI · 开发者生态社区</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#端侧AI`, `#生成式AI`, `#AI框架`, `#芯片优化`

---

<a id="item-9"></a>
## [AI power M&A hits a record.](https://36kr.com/newsflashes/3873859365328133?f=rss) ⭐️ 6.0/10

Deloitte data cited in the report says U.S. power and utilities M&A reached a record $203.6 billion in the first five months of the year. Data-center-related investment rose to $151.5 billion, more than doubling from $68.7 billion announced in the same period last year. The figures show that AI-driven data center demand is becoming a major force reshaping U.S. energy infrastructure and corporate dealmaking. Utilities, power producers, grid operators, data center developers, and large technology companies may all face higher capital spending and stronger competition for reliable electricity supply. The reported $203.6 billion in deals for the first five months is more than 40% above the $141.7 billion total for all of last year. The item also states that full-year 2025 data center investment is expected to reach $321 billion, but it does not provide details on deal composition, financing terms, or regional grid constraints.

rss · 36氪 · Jun 29, 06:13

**Background**: AI data centers require large amounts of electricity because they run dense clusters of servers, accelerators, cooling systems, and networking equipment. Power and utilities M&A refers to mergers and acquisitions involving electricity producers, grid assets, utilities, and related infrastructure companies. When data center demand rises quickly, companies may buy assets or raise capital to secure generation capacity, transmission access, and long-term energy supply.

**Tags**: `#AI infrastructure`, `#data centers`, `#energy`, `#M&A`, `#utilities`

---

<a id="item-10"></a>
## [Baidu open-sources Unlimited OCR for long documents](https://36kr.com/newsflashes/3873858183255302?f=rss) ⭐️ 6.0/10

Baidu has released and open-sourced Unlimited OCR, a 3B-parameter end-to-end OCR model designed for long-document parsing. The company says it reached 93.92% on OmniDocBench v1.6 and topped GitHub Daily Trending, GitHub Python Trending, Hugging Face global model trending, and Hugging Face multimodal model trending shortly after release. If the benchmark results hold up in independent use, Unlimited OCR could make large-scale PDF and document parsing more efficient for search, archiving, enterprise automation, and AI data pipelines. Its open-source release also adds another major Chinese AI lab model to the fast-moving ecosystem of document-understanding and multimodal models. The model is reported to have 3B total parameters but only about 570M active parameters during inference, suggesting a sparse or mixture-of-experts-style design. The project page says inference is supported through Hugging Face transformers on NVIDIA GPUs, while the claimed leaderboard results should still be treated as promotional until reproduced by third parties.

rss · 36氪 · Jun 29, 06:12

**Background**: OCR means optical character recognition, a technology that converts text in images, scans, and PDFs into machine-readable text. End-to-end OCR models try to perform recognition, layout understanding, and structured output generation in a unified model rather than through many separate pipeline stages. OmniDocBench is a benchmark for document parsing and structure understanding, covering diverse PDF pages and tasks such as text extraction, tables, formulas, and layout analysis. Long-document parsing is difficult because generated output can be very long, which often increases attention-cache memory and slows inference in decoder-based models.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/baidu/Unlimited-OCR">GitHub - baidu/Unlimited-OCR: Unlimited OCR Works: Welcome the Era of One-shot Long-horizon Parsing. · GitHub</a></li>
<li><a href="https://github.com/opendatalab/OmniDocBench">GitHub - opendatalab/ OmniDocBench : [CVPR 2025]...</a></li>
<li><a href="https://arxiv.org/html/2606.23050v1">Unlimited OCR Works Welcome the Era of One-shot Long-horizon Parsing</a></li>

</ul>
</details>

**Tags**: `#OCR`, `#open-source`, `#AI models`, `#document parsing`, `#Baidu`

---

<a id="item-11"></a>
## [Samsung plans a Gwangju chip base.](https://36kr.com/newsflashes/3873841411773447?f=rss) ⭐️ 6.0/10

Samsung Group Chairman Lee Jae-yong said the company plans to make Gwangju a chip production base and build an HBM factory in Chungcheong. The report did not provide a timeline, investment amount, or capacity targets. HBM is a key component for AI accelerators and other high-performance computing hardware, so any new Samsung capacity could matter for AI hardware supply chains. The plan also signals continued regional investment in South Korea’s semiconductor manufacturing ecosystem. The item is a brief statement attributed to Lee Jae-yong and does not specify whether the HBM factory would produce current-generation or future-generation HBM. It also does not clarify how Gwangju’s planned chip production role would relate to Samsung’s existing semiconductor facilities.

rss · 36氪 · Jun 29, 05:55

**Background**: HBM, or High Bandwidth Memory, is a type of DRAM that uses 3D stacking to provide much higher bandwidth than conventional memory. It is commonly associated with advanced packaging techniques such as TSV, which helps vertically connect stacked memory dies. HBM has become important because modern AI chips need extremely fast memory access to keep accelerators efficiently fed with data.

<details><summary>References</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/高頻寬記憶體">高带宽内存- 维基百科，自由的百科全书</a></li>
<li><a href="https://www.eet-china.com/mp/a366533.html">什么是HBM？来看看芯耀辉的科普视频-电子工程专辑</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#Samsung`, `#HBM`, `#AI hardware`, `#manufacturing`

---

<a id="item-12"></a>
## [Firmus and DayOne plan an Indonesian AI data center campus.](https://36kr.com/newsflashes/3873834032239621?f=rss) ⭐️ 6.0/10

Nvidia-backed Australian data center operator Firmus said it will work with Singapore-based DayOne to develop a dedicated Nvidia DSX AI factory campus on Batam Island, Indonesia. The project is planned for 360MW of installed capacity and is tied to an eight-year Nvidia collaboration, with agreements worth up to $30 billion over the first six years. The plan adds another large AI infrastructure project in Southeast Asia, a region increasingly positioned as a compute and data center hub near Singapore. If built as planned, the campus could expand access to Nvidia-based AI compute capacity for cloud, enterprise, and AI customers in the region. The announced site is Batam Island, which sits across the strait from Singapore and is often discussed as a nearby data center location. The announcement describes the campus as a Nvidia DSX AI factory, but it does not disclose GPU types, deployment timeline beyond the eight-year collaboration, power sourcing, cooling design, or customer commitments.

rss · 36氪 · Jun 29, 05:47

**Background**: Nvidia uses the term AI factory to describe data center infrastructure designed to turn large-scale compute, networking, storage, and software into AI training and inference capacity. Nvidia DSX is a platform for designing, simulating, validating, and operating such AI factories before and after physical deployment. A 360MW data center campus refers to a very large power-capacity plan, because advanced AI clusters require substantial electricity for GPUs, networking, cooling, and supporting infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/data-center/products/dsx/">AI Factory Design, Simulation, and Operations | NVIDIA DSX Platform</a></li>

</ul>
</details>

**Tags**: `#AI infrastructure`, `#data centers`, `#Nvidia`, `#Indonesia`, `#cloud computing`

---

<a id="item-13"></a>
## [AWS releases Blocks for AI agent backends.](https://www.infoq.cn/article/ZdA3CGtWNFGAoalSeiu8?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

AWS has introduced Blocks, an open-source framework intended to help developers build backend services for AI agents. The provided report does not include a version number, release date, architecture diagram, or code-level implementation details. AI agents increasingly need reliable backend components for orchestration, state handling, tool access, and service integration, so a framework from AWS could influence how teams operationalize agent-based applications. Its open-source positioning may also make it easier for developers to inspect, adapt, and integrate the framework into existing cloud or backend workflows. The main caveat is that the available item only states the framework’s purpose and does not describe its APIs, supported runtimes, deployment model, licensing terms, or relationship to existing AWS services. Without those details, it is difficult to assess whether Blocks is a substantial new platform layer or a smaller developer convenience framework.

rss · InfoQ 中文 · Jun 29, 14:00

**Background**: An AI agent is typically a software system that uses a language model to reason over a task, call tools, interact with external services, and decide on next steps. Backend development for such agents often involves managing requests, permissions, memory or state, tool connectors, observability, and deployment. Open-source frameworks can reduce repeated infrastructure work by giving developers reusable patterns and components instead of requiring each team to build the same backend plumbing from scratch.

**Tags**: `#AWS`, `#AI Agents`, `#Open Source`, `#Backend Development`, `#Developer Tools`

---

<a id="item-14"></a>
## [Bedrock Fable 5 Requires Anthropic Data Sharing](https://www.infoq.cn/article/NodhKVrhWoYF9yGwm12j?utm_source=rss&utm_medium=article) ⭐️ 6.0/10

InfoQ reports that AWS Bedrock users invoking the Fable 5 model must share inference data with Anthropic. The report is limited to a headline and link, so the exact scope, timing, and opt-out options are not specified in the provided content. This matters because Bedrock is positioned as an enterprise generative AI platform, and customers often choose it expecting centralized governance and controlled data handling. Any requirement to share inference data with a model provider can affect privacy reviews, compliance obligations, vendor risk assessments, and internal AI usage policies. The key unresolved issue is what “inference data” includes, such as prompts, outputs, metadata, logs, or evaluation signals. Without the original article’s technical details, readers should verify AWS and Anthropic contract terms, data retention language, and regional compliance implications before using the model for sensitive workloads.

rss · InfoQ 中文 · Jun 28, 14:00

**Background**: Amazon Bedrock is an AWS service for building generative AI applications through a unified API that provides access to foundation models from multiple providers. AI inference is the stage where a trained model processes new input, such as text or images, and produces an output. In enterprise settings, inference data can be sensitive because prompts and responses may contain customer information, proprietary business data, source code, or regulated content.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/bedrock/">Amazon Bedrock – Build genAI applications and agents at production...</a></li>
<li><a href="https://en.wikipedia.org/wiki/AWS_Bedrock">AWS Bedrock</a></li>
<li><a href="https://cloud.google.com/discover/what-is-ai-inference">What is AI inference? How it works and examples | Google Cloud</a></li>

</ul>
</details>

**Tags**: `#AI platforms`, `#AWS Bedrock`, `#Anthropic`, `#data privacy`, `#model inference`

---